### 🔍 **Ataque Man-in-the-Middle (MITM)**

Un **Man-in-the-Middle (MITM)** es un ataque en el que un atacante se **interpone** en la comunicación entre dos partes (usuario-servidor) sin que lo sepan, pudiendo **interceptar, modificar o robar información**.

---

### 🚀 **¿Cómo funciona?**

1️⃣ **Intercepción**

- El atacante se posiciona entre la víctima y el destino (servidor, red Wi-Fi, etc.).
- Puede usar técnicas como **ARP Spoofing**, **DNS Spoofing**, o ataques a Wi-Fi públicas.

2️⃣ **Manipulación del tráfico**

- Puede leer datos sensibles como **credenciales o mensajes**.
- Puede modificar la información antes de que llegue a la víctima.

3️⃣ **Redirección o robo de datos**

- Puede llevar a la víctima a sitios falsos (**phishing**).
- Puede capturar sesiones y cookies (**session hijacking**).

---

### ⚡ **Tipos comunes de MITM**

🔹 **ARP Spoofing** → Falsifica respuestas ARP para redirigir tráfico en una LAN.  
🔹 **DNS Spoofing** → Engaña a la víctima enviándola a sitios falsos.  
🔹 **Wi-Fi Rogue Access Point** → Un Wi-Fi falso que espía tráfico.  
🔹 **SSL Stripping** → Degrada HTTPS a HTTP para capturar datos en texto plano.

---

### 🔐 **¿Cómo protegerse?**

✔ **Usar HTTPS y VPN** para cifrar tráfico.  
✔ **Evitar Wi-Fi públicas sin VPN**.  
✔ **Usar autenticación de dos factores (2FA)**.  
✔ **Comprobar certificados digitales** en sitios web.  
✔ **Configurar seguridad en routers** para evitar ataques ARP/DNS Spoofing.

¿Quieres probar MITM en un entorno de laboratorio con herramientas como **Ettercap o Bettercap**? 🔥