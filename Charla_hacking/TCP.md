### 🔹 **¿Qué es TCP?**

**TCP (Transmission Control Protocol)** es un **protocolo de comunicación** que permite la transmisión confiable de datos entre dispositivos en una red. Es uno de los protocolos principales de **Internet** y funciona sobre **IP (Internet Protocol)**, formando juntos la famosa pila **TCP/IP**.

---

### 🔥 **Características clave de TCP**

✅ **Fiable** → Garantiza que los datos lleguen sin errores y en orden.  
✅ **Orientado a conexión** → Antes de enviar datos, establece una conexión entre el cliente y el servidor (**Three-Way Handshake**).  
✅ **Control de flujo** → Ajusta la velocidad de envío para no saturar la red.  
✅ **Control de congestión** → Evita que la red se sobrecargue.

---

### 🎬 **Cómo funciona TCP paso a paso**

#### **1️⃣ Establecimiento de conexión (Three-Way Handshake)**

Antes de enviar datos, TCP establece una conexión entre los dos dispositivos:

📌 Ejemplo: Un cliente quiere conectarse a un servidor web (`192.168.1.1`) en el puerto 80.

```plaintext
1. Cliente → Servidor:   SYN (Hola, quiero conectarme)
2. Servidor → Cliente:   SYN-ACK (Ok, te escucho)
3. Cliente → Servidor:   ACK (Perfecto, empecemos)
```

✅ **La conexión está lista** y pueden enviarse datos.

---

#### **2️⃣ Transmisión de datos**

📌 Los datos se dividen en **paquetes** y cada uno tiene un número de secuencia para garantizar que lleguen en orden.  
📌 Si un paquete se pierde, TCP lo **reenvía** automáticamente.

Ejemplo de paquetes enviados y recibidos:

```plaintext
Cliente → Servidor:   [Paquete 1] (Hola)
Servidor → Cliente:   [ACK] (Recibí el paquete 1)

Cliente → Servidor:   [Paquete 2] (¿Cómo estás?)
Servidor → Cliente:   [ACK] (Recibí el paquete 2)
```

---

#### **3️⃣ Cierre de conexión**

📌 Cuando terminan de comunicarse, ambos dispositivos cierran la conexión:

```plaintext
4. Cliente → Servidor:   FIN (Terminé)
5. Servidor → Cliente:   ACK (Ok)
6. Servidor → Cliente:   FIN (Yo también terminé)
7. Cliente → Servidor:   ACK (Entendido, adiós)
```

✅ **La conexión se cierra limpiamente**.

---

### 🔥 **Ejemplo de uso de TCP**

TCP se usa en muchas aplicaciones, como:  
✔ **Navegadores web** (HTTP/HTTPS).  
✔ **Correos electrónicos** (SMTP, IMAP, POP3).  
✔ **Descargas de archivos** (FTP).  
✔ **Servicios de transmisión en vivo** con control de calidad.

---

### ⚡ **TCP vs UDP**

|Característica|TCP|UDP|
|---|---|---|
|**Fiabilidad**|✅ Sí|❌ No|
|**Orden de los paquetes**|✅ Sí|❌ No|
|**Rapidez**|🚀 Más lento (por confirmaciones)|⚡ Más rápido (sin control de errores)|
|**Ejemplos de uso**|Web, correo, descargas|Juegos, streaming, VoIP|

---

### 🚀 **Resumen rápido**

🔹 TCP es un **protocolo de comunicación fiable y orientado a conexión**.  
🔹 Usa el **Three-Way Handshake** para iniciar la conexión.  
🔹 **Garantiza** que los datos lleguen completos y en orden.  
🔹 Es más **lento que UDP**, pero más seguro para aplicaciones críticas.

