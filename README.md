# 🚀 Buscador de Máquinas de HTB

> Este proyecto permite buscar máquinas de Hack The Box (HTB) utilizando Bash con parámetros de entrada. Se puede buscar por nombre, IP, sistema operativo, dificultad y habilidades en la siguiente web: [HTB Machines](https://htbmachines.github.io).

---

## 📸 Vista Previa  
![Vista Previa](./img/h.png)  

---

## ✨ Características  
✅ Búsqueda por nombre, IP, sistema operativo, dificultad y skills  
✅ Automatización con Bash  
✅ Interfaz sencilla y fácil de usar  

---

## 📦 Instalación  
```bash
sudo apt install node-js-beautify
sudo apt install moreutils -y

git clone https://github.com/SwodLore/Search-machines-of-s4vitar.git
cd Search-machines-of-s4vitar
chmod +x htbmachines.sh
```

---

## 🚀 Uso  

### 📌 Mostrar ayuda
Esto te muestra la ayuda del script.
```bash
./htbmachines.sh -h
```
📷 **Ejemplo:**  
![Ayuda](./img/h.png)  

---

### 🔄 Actualizar base de datos  
Esto actualiza la base de datos de máquinas de HTB mediante una peticion GET a la siguiente URL: [HTB Machines](https://htbmachines.github.io) para obtener la lista de máquinas disponibles.
```bash
./htbmachines.sh -u
```
📷 **Ejemplo:**  
![Actualizar](./img/u.png)  

---

### 🔍 Buscar por nombre  
Esto busca por nombre en la base de datos de máquinas de HTB.
```bash
./htbmachines.sh -m "nombre_maquina"
```
📷 **Ejemplo:**  
![Buscar por Nombre](./img/m.png)  

---

### 🌎 Buscar por sistema operativo  
Esto busca por sistema operativo en la base de datos de máquinas de HTB.
```bash
./htbmachines.sh -o "Windows"
```
📷 **Ejemplo:**  
![Buscar por OS](./img/o.png)  

---

### 🔢 Buscar por dificultad 
Esto busca por dificultad en la base de datos de máquinas de HTB.
```bash
./htbmachines.sh -d "Difícil"
```
📷 **Ejemplo:**  
![Buscar por Dificultad](./img/d.png)  

---

### 🎯 Buscar por habilidades (skills)  
Esto busca por habilidades en la base de datos de máquinas de HTB.
```bash
./htbmachines.sh -s "SQL Injection"
```
📷 **Ejemplo:**  
![Buscar por Skills](./img/s.png)  

---

### 🔍 Buscar por Ip  
Esto busca por ip de la base de datos de máquinas de HTB.
```bash
./htbmachines.sh -i "10.10.10.124"
```
📷 **Ejemplo:**  
![Buscar por Nombre](./img/i.png)  

---

### 🎯 Buscar por por nombre (Link de Youtube)  
Esto busca la resolución de la máquina por nombre en la base de datos de máquinas de HTB.
```bash
./htbmachines.sh -y "GoodGames"
```
📷 **Ejemplo:**  
![Buscar por Skills](./img/y.png)  

---

## 🛠 Contribuciones  
1. Haz un Fork 🍴  
2. Crea una nueva rama (`git checkout -b feature/nueva-feature`)  
3. Realiza cambios y haz commit (`git commit -m 'Nueva funcionalidad'`)  
4. Sube tu código (`git push origin feature/nueva-feature`)  
5. Crea un Pull Request 🚀  

---
