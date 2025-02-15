### 🔥 **SQL Injection (SQLi)**

La **SQL Injection** es un ataque que permite a un atacante **inyectar código SQL malicioso** en una consulta a la base de datos de una aplicación web. Si la aplicación no valida correctamente las entradas del usuario, el atacante puede **robar, modificar o eliminar datos** e incluso tomar el control del sistema.

---

### 🚀 **¿Cómo funciona?**

1️⃣ **El atacante encuentra un campo vulnerable** (formularios, URLs, cabeceras).  
2️⃣ **Inserta código SQL malicioso** en lugar de una entrada legítima.  
3️⃣ **La consulta maliciosa se ejecuta en la base de datos**, permitiendo acceso no autorizado.

Ejemplo básico de código vulnerable en Python con Flask y MySQL:

```python
usuario = input("Ingrese usuario: ")
consulta = f"SELECT * FROM usuarios WHERE nombre = '{usuario}'"
cursor.execute(consulta)
```

Si el atacante ingresa:

```sql
' OR '1'='1' --  
```

La consulta se transforma en:

```sql
SELECT * FROM usuarios WHERE nombre = '' OR '1'='1' --'
```

Como `1=1` **siempre es verdadero**, la consulta devuelve **todos los usuarios**.

---

### ⚠ **Tipos de SQL Injection**

🔹 **SQLi Clásico** → Inyección directa en consultas SQL.  
🔹 **SQLi Basado en Errores** → Explotar mensajes de error de la base de datos.  
🔹 **SQLi Ciego** → No hay errores visibles, pero se usa lógica booleana para inferir datos.  
🔹 **SQLi Basado en Tiempo** → Se usa la demora en respuestas para extraer información.

---

### 🔐 **¿Cómo prevenirlo?**

✔ **Usar consultas preparadas y parámetros**:

```python
cursor.execute("SELECT * FROM usuarios WHERE nombre = %s", (usuario,))
```

✔ **Validar y sanitizar entradas de usuario**.  
✔ **Configurar permisos mínimos en la base de datos**.  
✔ **Usar Web Application Firewalls (WAFs)** para detectar ataques.

Si te interesa practicar **SQLi de forma segura**, puedes probar en entornos como **DVWA** o usar herramientas como **sqlmap**. 🚀🔍