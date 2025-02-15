El **ransomware WannaCry** fue un ataque global en 2017 que cifraba archivos de las víctimas y pedía un rescate en **Bitcoin** para desbloquearlos.

### 🔥 **¿Cómo funcionaba?**

1. **Explotaba una vulnerabilidad en Windows**
    - Usaba el exploit **EternalBlue** (filtrado de la NSA) para aprovechar una falla en **SMBv1**.
2. **Se propagaba rápidamente**
    - Infectaba una máquina y luego escaneaba la red en busca de otros equipos vulnerables.
3. **Cifraba archivos**
    - Usaba un cifrado fuerte (**AES + RSA**) para bloquear documentos.
4. **Pedía un rescate**
    - Mostraba un mensaje exigiendo **$300 - $600 en Bitcoin** para recuperar los datos.

### 🔐 **¿Cómo se detuvo?**

Un investigador de seguridad (**MalwareTech**) encontró un **"kill switch"**, un dominio oculto en el código que, al ser registrado, detuvo la propagación del malware.

### 🚀 **Prevención contra ransomware**

✔ **Actualizar el sistema** (parche MS17-010).  
✔ **Desactivar SMBv1** si no es necesario.  
✔ **Usar backups y antivirus actualizados**.  
✔ **No abrir archivos sospechosos** ni hacer clic en enlaces desconocidos.

¿Te interesa aprender a analizar ransomware en entornos controlados? 🔥🔍