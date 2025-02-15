### **6. Introducción al Hacking**

El hacking es una disciplina que abarca desde el **análisis de seguridad informática** hasta la **explotación de vulnerabilidades** en sistemas y redes. Sin embargo, es importante diferenciar entre hacking **ético** y **malicioso**, así como comprender sus fundamentos, metodologías y herramientas.

---

## **6.1. ¿Qué es el Hacking?**

El **hacking** consiste en encontrar y explotar debilidades en sistemas informáticos con diferentes fines. Puede ser usado para **mejorar la seguridad** (hacking ético) o para **cometer delitos** (hacking malicioso).

🔹 **Tipos de Hackers:**  
✅ **White Hat (Hackers Éticos):** Usan sus conocimientos para **proteger** sistemas y redes.  
✅ **Black Hat (Ciberdelincuentes):** Explotan vulnerabilidades para **beneficio personal** o con intenciones maliciosas.  
✅ **Gray Hat (Intermedios):** No siempre tienen permiso para realizar pruebas de seguridad, pero no buscan dañar.

🔸 **Ejemplo:** Un hacker ético contratado por una empresa encuentra fallos de seguridad en su red antes de que los ciberdelincuentes los aprovechen.

---

## **6.2. Historia del Hacking**

El término **hacker** surgió en los años **60 y 70** en el MIT, donde programadores y entusiastas de la informática exploraban sistemas en busca de mejoras y eficiencia.

🔹 **Eventos Claves en la Historia del Hacking:**  
📌 **Primer virus (Creeper, 1971):** Infectaba computadoras sin dañarlas, mostrando el mensaje _"I’m the creeper, catch me if you can!"_.  
📌 **Primer gusano (Morris Worm, 1988):** Se propagó por Internet, causando interrupciones y demostrando la vulnerabilidad de redes.  
📌 **Kevin Mitnick (1990s):** Uno de los hackers más famosos, comprometió redes de telecomunicaciones y corporaciones.  
📌 **Anonymous (2003-actualidad):** Grupo hacktivista que realiza ataques en defensa de causas políticas y sociales.

🔸 **Ejemplo:** El ataque de Kevin Mitnick a compañías como Nokia y Motorola llevó a reformas en la ciberseguridad y leyes más estrictas.

---

## **6.3. Principios del Hacking Ético**

El hacking ético sigue una metodología estructurada y requiere **permiso del propietario** de los sistemas antes de realizar pruebas de seguridad.

🔹 **Principios Clave:**  
✅ **Legalidad:** No se realiza sin autorización.  
✅ **Confidencialidad:** No se divulgan vulnerabilidades sin consentimiento.  
✅ **Responsabilidad:** Se reportan problemas de seguridad para ser corregidos.

🔸 **Ejemplo:** Un hacker ético analiza una web bancaria y encuentra una vulnerabilidad en el inicio de sesión, notificando a la empresa para que lo solucione.

---

## **6.4. Fases del Hacking Ético**

El hacking sigue una serie de **fases estructuradas** para evaluar la seguridad de un sistema.

### **🔹 1. Reconocimiento (Footprinting)**

Se recopila información sobre el objetivo utilizando herramientas como:  
✅ **Whois:** Información de dominios.  
✅ **Shodan:** Análisis de dispositivos conectados a Internet.  
✅ **OSINT (Open Source Intelligence):** Recolección de datos de fuentes abiertas.

🔸 **Ejemplo:** Un hacker investiga qué servidores usa una empresa antes de intentar un ataque.

---

### **🔹 2. Escaneo y Enumeración**

Se identifican vulnerabilidades en sistemas y redes.

✅ **Escaneo de puertos:** Uso de herramientas como **Nmap** para encontrar servicios abiertos.  
✅ **Fingerprinting del sistema operativo:** Identificación del SO mediante respuestas de red.  
✅ **Enumeración de usuarios y servicios:** Búsqueda de credenciales o accesos mal configurados.

🔸 **Ejemplo:** Un hacker escanea una red WiFi empresarial para encontrar dispositivos vulnerables.

---

### **🔹 3. Explotación y Gaining Access**

Se busca aprovechar vulnerabilidades para acceder al sistema.

✅ **Ataques de fuerza bruta:** Intentos repetidos para adivinar contraseñas.  
✅ **Inyección SQL:** Manipulación de bases de datos a través de consultas mal protegidas.  
✅ **Explotación de vulnerabilidades:** Uso de herramientas como **Metasploit** para atacar sistemas.

🔸 **Ejemplo:** Un atacante usa una vulnerabilidad en una página de inicio de sesión para acceder sin credenciales válidas.

---

### **🔹 4. Mantenimiento del Acceso (Persistence)**

Si se consigue acceso, se intentan establecer **backdoors** o persistencia en el sistema.

✅ **Rootkits:** Ocultan la presencia del atacante en el sistema.  
✅ **Puertas traseras (Backdoors):** Creación de accesos ocultos.  
✅ **Robo de credenciales:** Extracción de información para accesos futuros.

🔸 **Ejemplo:** Un hacker instala un **keylogger** para capturar contraseñas sin ser detectado.

---

### **🔹 5. Eliminación de Huellas (Covering Tracks)**

El atacante borra evidencias de su actividad para evitar ser detectado.

✅ **Eliminar logs de acceso.**  
✅ **Uso de conexiones anónimas (VPN, Tor).**  
✅ **Borrar archivos temporales o pruebas del ataque.**

🔸 **Ejemplo:** Un hacker borra registros de actividad en un servidor después de modificar su contenido.

---

## **6.5. Herramientas Utilizadas en Hacking Ético**

🔹 **Escaneo y Reconocimiento:**  
✅ **Nmap:** Escaneo de puertos y servicios.  
✅ **Shodan:** Identificación de dispositivos conectados a Internet.  
✅ **Maltego:** Recolección de información de fuentes abiertas.

🔹 **Explotación de Vulnerabilidades:**  
✅ **Metasploit:** Plataforma de pruebas de penetración.  
✅ **Burp Suite:** Análisis y explotación de aplicaciones web.  
✅ **SQLmap:** Identificación y explotación de inyecciones SQL.

🔹 **Ataques de Red y Contraseñas:**  
✅ **Aircrack-ng:** Análisis y ataque a redes WiFi.  
✅ **John the Ripper:** Crackeo de contraseñas.  
✅ **Hydra:** Ataques de fuerza bruta contra autenticaciones.

---

## **6.6. Certificaciones en Hacking Ético**

Para ser un hacker ético certificado, existen varias certificaciones reconocidas:

🔹 **CEH (Certified Ethical Hacker):** Formación completa en hacking ético.  
🔹 **OSCP (Offensive Security Certified Professional):** Pruebas de penetración avanzadas.  
🔹 **GPEN (GIAC Penetration Tester):** Enfoque en pentesting profesional.  
🔹 **CISSP (Certified Information Systems Security Professional):** Seguridad informática avanzada.

🔸 **Ejemplo:** Un profesional con certificación **OSCP** es contratado para auditar la seguridad de un banco.

---

## **6.7. Ética y Legalidad en el Hacking**

El hacking puede ser una **herramienta de protección o de ataque**. Para que sea legal, debe cumplir con los siguientes criterios:

✅ **Permiso del propietario del sistema.**  
✅ **Uso ético de la información obtenida.**  
✅ **Cumplimiento de leyes nacionales e internacionales.**

🔹 **Casos de Uso Legal:**

- Pruebas de seguridad en empresas.
- Análisis de vulnerabilidades en aplicaciones.
- Participación en **Bug Bounty Programs** (recompensas por encontrar fallos).

🔸 **Ejemplo:** Google y Facebook pagan a investigadores por encontrar errores de seguridad en sus plataformas.

---

## **Conclusión**

El hacking es una disciplina compleja que puede usarse para **fortalecer** la seguridad informática o para actividades maliciosas. Con un enfoque ético y profesional, es posible **proteger redes, sistemas y usuarios** mediante técnicas avanzadas de ciberseguridad.

