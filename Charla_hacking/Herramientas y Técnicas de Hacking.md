### **7. Herramientas y Técnicas de Hacking**

El hacking utiliza una combinación de herramientas y técnicas para analizar, explotar y asegurar sistemas informáticos. Estas herramientas pueden clasificarse según su función, y las técnicas varían según el tipo de ataque que se quiera realizar.

---

## **7.1. Clasificación de las Herramientas de Hacking**

Las herramientas utilizadas en el hacking pueden dividirse en varias categorías según su propósito:

🔹 **Escaneo y Recolección de Información**  
🔹 **Explotación de Vulnerabilidades**  
🔹 **Ataques de Red y Contraseñas**  
🔹 **Análisis de Malware y Forense Digital**  
🔹 **Anonimato y Evasión**

Cada una de estas categorías contiene herramientas específicas que los hackers utilizan para evaluar la seguridad de los sistemas.

---

## **7.2. Herramientas para Escaneo y Recolección de Información**

Estas herramientas permiten obtener información de un objetivo antes de realizar un ataque.

✅ **[[Nmap]]:** Escaneo de puertos y servicios en una red.  
✅ **Shodan:** Identifica dispositivos conectados a Internet.  
✅ **Whois:** Obtiene información sobre dominios y registros DNS.  
✅ **Maltego:** Análisis de inteligencia con OSINT (Open Source Intelligence).  
✅ **theHarvester:** Recolecta correos electrónicos, subdominios y nombres de usuarios.

🔸 **Ejemplo:** Un hacker usa **Nmap** para identificar qué servicios están activos en los servidores de una empresa.

---

## **7.3. Herramientas de Explotación de Vulnerabilidades**

Estas herramientas ayudan a explotar debilidades en software, redes y aplicaciones web.

✅ **Metasploit:** Plataforma avanzada para pruebas de penetración.  
✅ **SQLmap:** Automático para detectar y explotar inyecciones SQL.  
✅ **Burp Suite:** Prueba de seguridad en aplicaciones web.  
✅ **Nikto:** Escáner de vulnerabilidades en servidores web.  
✅ **ExploitDB:** Base de datos de exploits para diferentes vulnerabilidades.

🔸 **Ejemplo:** Un pentester usa **Metasploit** para comprometer un servidor con una vulnerabilidad en su sistema operativo.

---

## **7.4. Herramientas para Ataques de Red y Contraseñas**

Estas herramientas permiten interceptar tráfico de red y crackear credenciales.

✅ **Wireshark:** Analiza tráfico de red y paquetes de datos.  
✅ **Aircrack-ng:** Herramientas para hackeo de WiFi (WEP/WPA/WPA2).  
✅ **John the Ripper:** Crackeo de contraseñas con diccionarios.  
✅ **Hydra:** Ataques de fuerza bruta contra autenticaciones.  
✅ **Responder:** Ataques contra redes Windows mediante SMB y NetBIOS.

🔸 **Ejemplo:** Un hacker usa **Wireshark** para capturar credenciales de acceso enviadas en texto plano.

---

## **7.5. Herramientas para Análisis de Malware y Forense Digital**

Se utilizan para estudiar archivos sospechosos y rastrear actividades maliciosas.

✅ **Autopsy:** Plataforma de análisis forense digital.  
✅ **Volatility:** Análisis de memoria RAM para detectar malware.  
✅ **Cuckoo Sandbox:** Análisis de comportamiento de malware.  
✅ **Radare2:** Ingeniería inversa de binarios.  
✅ **YARA:** Identificación de malware basado en patrones.

🔸 **Ejemplo:** Un analista usa **Cuckoo Sandbox** para ejecutar un virus en un entorno controlado y estudiar su comportamiento.

---

## **7.6. Herramientas para Anonimato y Evasión**

Los hackers utilizan estas herramientas para ocultar su identidad y evitar detección.

✅ **[[Tor]]:** Navegación anónima mediante la red Onion.  
✅ **[[VPNs]]:** Cifran el tráfico y ocultan la IP real.  
✅ **ProxyChains:** Encadena múltiples proxies para ocultar el tráfico.  
✅ **Macchanger:** Cambia la dirección MAC de un dispositivo.  
✅ **Anti-forensics:** Técnicas para eliminar rastros digitales.

🔸 **Ejemplo:** Un hacker usa **Tor** para acceder a la dark web sin revelar su IP real.

---

## **7.7. Técnicas de Hacking**

Los hackers aplican diversas técnicas según el objetivo del ataque o prueba de seguridad.

### **7.7.1. Ingeniería Social**

Manipulación psicológica de usuarios para obtener información confidencial.

✅ **Phishing:** Envío de correos fraudulentos con enlaces maliciosos.  
✅ **Pretexting:** Inventar una historia para engañar a la víctima.  
✅ **Baiting:** Dejar dispositivos USB infectados en lugares públicos.  
✅ **Vishing:** Llamadas telefónicas fraudulentas para obtener datos sensibles.

🔸 **Ejemplo:** Un atacante envía un correo falso de un banco para robar credenciales.

---

### **7.7.2. Ataques Web**

Se enfocan en vulnerabilidades en sitios y aplicaciones web.

✅ **Inyección SQL:** Manipulación de bases de datos a través de formularios web.  
✅ **Cross-Site Scripting (XSS):** Inyección de scripts maliciosos en páginas web.  
✅ **CSRF (Cross-Site Request Forgery):** Realización de acciones no autorizadas en nombre de un usuario.  
✅ **Path Traversal:** Acceso a archivos fuera del directorio permitido.

🔸 **Ejemplo:** Un hacker usa **SQLmap** para extraer información confidencial de una base de datos vulnerable.

---

### **7.7.3. Ataques de Red**

Explotan vulnerabilidades en redes y protocolos de comunicación.

✅ **Man-in-the-Middle (MitM):** Intercepta la comunicación entre dos partes.  
✅ **ARP Spoofing:** Redirige el tráfico de red a un atacante.  
✅ **DNS Spoofing:** Modifica respuestas DNS para dirigir a sitios falsos.  
✅ **Sniffing:** Captura paquetes de datos en la red.

🔸 **Ejemplo:** Un atacante usa **Ettercap** para realizar un **MitM** y espiar contraseñas en una red WiFi pública.

---

### **7.7.4. Ataques a Sistemas y Hardware**

Estos ataques afectan la infraestructura física o lógica de los sistemas.

✅ **Exploits de Zero-Day:** Vulnerabilidades sin parches conocidos.  
✅ **Rootkits:** Malware que oculta la presencia de un atacante.  
✅ **Keyloggers:** Capturan lo que escribe un usuario en el teclado.  
✅ **Ataques de Firmware:** Comprometen hardware como routers o BIOS.

🔸 **Ejemplo:** Un hacker instala un **keylogger** en un equipo para robar contraseñas sin ser detectado.

---

### **7.7.5. Ataques de Fuerza Bruta y Diccionario**

Intentan adivinar contraseñas probando múltiples combinaciones.

✅ **Fuerza Bruta:** Prueba todas las combinaciones posibles.  
✅ **Diccionario:** Usa una lista de palabras comunes.  
✅ **Ataques Rainbow Table:** Utilizan bases de datos precomputadas de hashes.

🔸 **Ejemplo:** Un atacante usa **Hydra** para descifrar la contraseña de una cuenta SSH.

---

## **7.8. Automatización de Ataques con Scripts**

Los hackers pueden crear scripts personalizados para automatizar ataques.

✅ **Python y Bash:** Lenguajes usados en automatización de hacking.  
✅ **AutoRecon:** Automatiza reconocimiento y escaneo de redes.  
✅ **CrackMapExec:** Automatiza ataques en redes Windows.

🔸 **Ejemplo:** Un hacker usa **Python** para escribir un script que escanee automáticamente vulnerabilidades en una red.

---

## **Conclusión**

Las herramientas y técnicas de hacking son esenciales para evaluar la seguridad de sistemas y redes. Sin embargo, su uso debe ser **ético y legal**, respetando normas de ciberseguridad.

