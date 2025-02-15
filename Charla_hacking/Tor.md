### 🕵️‍♂️ **¿Cómo funciona la red Tor?**

**Tor (The Onion Router)** es una red que **anonimiza** el tráfico de Internet al enrutarlo a través de múltiples servidores cifrados, llamados **nodos**, para ocultar la identidad y la ubicación del usuario.

---

### 🔥 **Proceso de Funcionamiento**

1️⃣ **El usuario se conecta a la red Tor**

- Puede usar el **navegador Tor** o configurar una conexión manual.

2️⃣ **Se construye un circuito de 3 nodos aleatorios**

- **Nodo de entrada** → Recibe la conexión del usuario.
- **Nodo intermedio** → Pasa el tráfico sin conocer origen ni destino.
- **Nodo de salida** → Entrega la solicitud al sitio web final.

3️⃣ **Cifrado en capas (como una cebolla 🧅)**

- Cada nodo solo conoce al nodo anterior y al siguiente.
- Cada capa de cifrado se elimina en cada nodo hasta llegar al destino.
- **El nodo de salida envía la solicitud al sitio web**, que ve la IP del nodo, no la del usuario.

4️⃣ **El sitio web responde y la información vuelve por la misma ruta**

- Se cifra en el nodo de salida y se reconstruye hasta llegar al usuario.

---

### 🔐 **Ventajas de Tor**

✔ **Anonimato en la web**.  
✔ **Evita censura y rastreo**.  
✔ **Accede a la "Dark Web" (.onion)**.  
✔ **Protección contra vigilancia en línea**.

---

### ⚠ **Limitaciones y riesgos**

🔸 **Velocidad lenta** (por el enrutamiento en múltiples nodos).  
🔸 **Los nodos de salida pueden ver tráfico no cifrado**.  
🔸 **No protege contra malware o ataques web**.  
🔸 **Algunos sitios bloquean conexiones desde Tor**.

Para mayor seguridad, se recomienda:  
✔ **No iniciar sesión en cuentas personales en Tor**.  
✔ **Usar HTTPS dentro de Tor**.  
✔ **Evitar descargar archivos que puedan filtrar la IP**.  
✔ **No confiar en sitios sospechosos de la dark web**.

