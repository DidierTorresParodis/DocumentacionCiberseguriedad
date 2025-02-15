FTP (**File Transfer Protocol**) es un protocolo de red utilizado para transferir archivos entre un cliente y un servidor a través de una red, generalmente Internet. Funciona en el **puerto 21** por defecto y permite a los usuarios subir, descargar y administrar archivos en un servidor remoto.

### 📌 **Características clave de FTP:**

- Permite **autenticación** con usuario y contraseña o acceso anónimo.
- Puede operar en **modo activo o pasivo**, dependiendo de la configuración del firewall.
- No cifra los datos por defecto, por lo que **no es seguro** sin complementos como **FTPS** o **SFTP**.

### 📌 **Modos de funcionamiento de FTP:**

1. **Modo Activo:** El cliente abre un puerto aleatorio y el servidor inicia la conexión de datos.
2. **Modo Pasivo:** El servidor abre un puerto aleatorio y el cliente se conecta a él (útil cuando hay firewalls).

### 📌 **Alternativas más seguras:**

- **SFTP (SSH File Transfer Protocol)**: Usa SSH para cifrar la conexión.
- **FTPS (FTP Secure)**: Usa SSL/TLS para cifrar la conexión.

📌 **Conclusión:** FTP es útil para la transferencia de archivos, pero debe usarse con precaución debido a sus **vulnerabilidades** cuando no está cifrado. 🚨