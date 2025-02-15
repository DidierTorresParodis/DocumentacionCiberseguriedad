### **4. Tecnologías y Estrategias de Defensa**

Este apartado abarca las principales herramientas, metodologías y estrategias utilizadas en ciberseguridad para proteger sistemas, redes y datos frente a amenazas.

---

## **4.1. Tecnologías de Seguridad**

### **🔹 [[firewalls]]: Primera Línea de Defensa**

Un **firewall** es un sistema que filtra el tráfico de red entrante y saliente basado en reglas de seguridad. Puede ser:

- **Firewall de Red:** Filtra el tráfico entre redes (por ejemplo, protege la red interna de Internet).
- **Firewall de Aplicación Web (WAF):** Protege servidores web de ataques como SQL Injection y XSS.
- **Firewall de Host:** Protege equipos individuales contra accesos no autorizados.

🔸 **Ejemplo:** Un firewall bloquea intentos de acceso a un puerto no autorizado en un servidor.

---

### **🔹 Sistemas de Detección y Prevención de Intrusos ([[IDS e IPS]])**

- **IDS (Intrusion Detection System):** Monitorea el tráfico en busca de actividad sospechosa.
- **IPS (Intrusion Prevention System):** Además de detectar, bloquea ataques automáticamente.

🔸 **Ejemplo:** Un IPS bloquea intentos de explotación de vulnerabilidades en una base de datos.

---

### **🔹 Cifrado de Datos: Protección de la Información**

El cifrado convierte datos en un formato ilegible para evitar que sean robados o alterados.

- **Cifrado en tránsito:** Protege datos mientras viajan por la red (ejemplo: [[HTTPS]], [[VPNs]]).
- **Cifrado en reposo:** Protege datos almacenados (ejemplo: discos cifrados con BitLocker).
- **Cifrado de extremo a extremo:** Garantiza que solo emisor y receptor puedan leer el mensaje (ejemplo: WhatsApp).

🔸 **Ejemplo:** Un atacante intercepta una conexión [[HTTPS]], pero no puede leer los datos porque están cifrados.

---

### **🔹 Autenticación Multifactor ([[MFA]])**

MFA añade una capa extra de seguridad al requerir más de un factor de autenticación.

🔹 **Ejemplo:** Un usuario inicia sesión en su correo y, además de su contraseña, debe ingresar un código enviado a su teléfono.

---

### **🔹 Seguridad en la Nube**

Las empresas migran a servicios en la nube como AWS, Azure y Google Cloud, lo que requiere nuevas estrategias de protección:

✅ **Cifrado de datos en la nube.**  
✅ **Control de acceso basado en roles (RBAC).**  
✅ **Monitoreo y auditoría de actividad.**  
✅ **Protección contra amenazas avanzadas en entornos híbridos.**

🔸 **Ejemplo:** Una empresa usa AWS con IAM (Identity and Access Management) para restringir el acceso a datos sensibles.

---

## **4.2. Estrategias de Defensa en Profundidad**

### **🔹 Zero Trust Security: No Confíes en Nadie**

Este modelo de seguridad asume que **nadie es confiable por defecto**, incluso dentro de la red corporativa.

🔹 **Principios clave:**  
✅ Verificación continua de identidad.  
✅ Segmentación de redes.  
✅ Mínimos privilegios para los usuarios.  
✅ Monitoreo constante del comportamiento.

🔸 **Ejemplo:** Un empleado necesita acceder a documentos internos, pero debe autenticarse cada vez y solo puede ver archivos específicos según su rol.

---

### **🔹 Hardening: Fortalecimiento de Sistemas**

El **hardening** consiste en reducir la superficie de ataque de un sistema eliminando configuraciones innecesarias.

✅ **Deshabilitar servicios innecesarios.**  
✅ **Actualizar software y aplicar parches.**  
✅ **Configurar reglas de acceso estrictas.**  
✅ **Usar listas blancas de aplicaciones seguras.**

🔸 **Ejemplo:** Un administrador de sistemas desactiva puertos no utilizados y elimina usuarios innecesarios en un servidor.

---

### **🔹 Red Team vs. Blue Team: Defensa y Ataque Controlado**

- **Red Team:** Simula ataques para evaluar la seguridad de una empresa.
- **Blue Team:** Defiende los sistemas y responde a incidentes.

🔹 **Ejemplo:** Un Red Team lanza un ataque de phishing controlado para evaluar la preparación de los empleados.

---

## **4.3. Monitoreo y Gestión de Incidentes**

### **🔹 SIEM (Security Information and Event Management)**

Los sistemas **SIEM** recopilan y analizan registros de actividad en tiempo real para detectar amenazas.

🔹 **Ejemplo:** Un SIEM detecta múltiples intentos fallidos de inicio de sesión y alerta a los administradores.

---

### **🔹 Plan de Respuesta a Incidentes**

Las empresas deben tener un plan para actuar ante un ataque:

✅ **Identificación:** Detección del incidente.  
✅ **Contención:** Aislar el sistema afectado.  
✅ **Erradicación:** Eliminar la amenaza.  
✅ **Recuperación:** Restaurar sistemas y datos.  
✅ **Lecciones aprendidas:** Analizar lo ocurrido para mejorar defensas.

🔸 **Ejemplo:** Una empresa sufre un ataque de ransomware y sigue su plan de respuesta para restaurar los sistemas sin pagar el rescate.

---

## **4.4. Seguridad en el Desarrollo de Software**

Las aplicaciones deben diseñarse con seguridad en mente desde el inicio (**Security by Design**).

✅ **Principio de mínimo privilegio:** Dar solo los permisos necesarios.  
✅ **Validación de entradas:** Evitar ataques como SQL Injection y XSS.  
✅ **Uso de librerías seguras:** No depender de código vulnerable.  
✅ **Pruebas de seguridad:** Realizar pentesting antes del despliegue.

🔸 **Ejemplo:** Un desarrollador usa una función de escape en SQL para evitar inyecciones de código malicioso.

---

