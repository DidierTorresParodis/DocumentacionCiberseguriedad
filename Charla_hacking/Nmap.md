### 🔎 **¿Qué hace Nmap?**

**Nmap (Network Mapper)** es una herramienta de código abierto usada para **explorar y analizar redes**. Permite descubrir hosts, servicios y vulnerabilidades en un sistema, siendo útil en **ciberseguridad, administración de redes y hacking ético**.

---

### 🚀 **Funciones principales de Nmap**

🔹 **Descubrimiento de hosts** → Identifica dispositivos activos en una red.  
🔹 **Escaneo de puertos** → Detecta qué puertos están abiertos o cerrados en un sistema.  
🔹 **Detección de servicios** → Averigua qué aplicaciones y versiones están corriendo en los puertos abiertos.  
🔹 **Fingerprinting del sistema operativo** → Estima qué sistema operativo usa un host.  
🔹 **Escaneo de vulnerabilidades** → Puede usarse con scripts NSE para detectar fallos de seguridad.

---

### 🛠 **Ejemplos de uso**

📌 **Escaneo básico de una IP**

```bash
nmap 192.168.1.1
```

📌 **Escanear todos los dispositivos en una red**

```bash
nmap 192.168.1.0/24
```

📌 **Detectar puertos abiertos y servicios**

```bash
nmap -sV 192.168.1.1
```

📌 **Detección del sistema operativo**

```bash
nmap -O 192.168.1.1
```

📌 **Escaneo agresivo (detalles completos)**

```bash
nmap -A 192.168.1.1
```

📌 **Escaneo de vulnerabilidades con scripts NSE**

```bash
nmap --script=vuln 192.168.1.1
```

---

### ⚠ **Consideraciones**

🔸 Puede ser detectado por firewalls y sistemas de detección de intrusos (IDS).  
🔸 Su uso sin autorización en redes ajenas **puede ser ilegal**.  
🔸 Existen técnicas de **evasión** para evitar ser detectado (**nmap -T2, -sS, etc.**).

