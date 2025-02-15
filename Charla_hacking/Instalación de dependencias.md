
---

## **🔹 Instalación en Windows**

### **1️⃣ Instalar Nmap en Windows**

#### **Usando Winget (Recomendado)**

```powershell
winget install -e --id Insecure.Nmap
```

#### **Instalación Manual**

1. Descarga el instalador desde: [https://nmap.org/download.html](https://nmap.org/download.html)
2. Ejecuta el instalador y sigue las instrucciones.
3. Agrega Nmap al `PATH` si es necesario.

✅ **Verificación**

```powershell
nmap --version
```

---

### **2️⃣ Instalar Git en Windows**

#### **Usando Winget (Recomendado)**

```powershell
winget install -e --id Git.Git
```

#### **Instalación Manual**

4. Descarga el instalador desde: [https://git-scm.com/downloads](https://git-scm.com/downloads)
5. Ejecuta el instalador y sigue las instrucciones.
6. Durante la instalación, selecciona "Add Git to PATH" para usarlo en la terminal.

✅ **Verificación**

```powershell
git --version
```

---

## **🔹 Instalación en Linux**

### **1️⃣ Instalar Nmap en Linux**

#### **En Debian, Ubuntu y derivados**

```bash
sudo apt update && sudo apt install nmap -y
```

#### **En Arch Linux y Manjaro**

```bash
sudo pacman -S nmap
```

#### **En Fedora**

```bash
sudo dnf install nmap -y
```

✅ **Verificación**

```bash
nmap --version
```

---

### **2️⃣ Instalar Git en Linux**

#### **En Debian, Ubuntu y derivados**

```bash
sudo apt update && sudo apt install git -y
```

#### **En Arch Linux y Manjaro**

```bash
sudo pacman -S git
```

#### **En Fedora**

```bash
sudo dnf install git -y
```

✅ **Verificación**

```bash
git --version
```

---
