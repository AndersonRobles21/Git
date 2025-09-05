# 📌 Guía básica de Git y GitHub
Anderson Topaga
## 🔹 Configuración inicial
```bash
# Configurar nombre de usuario
git config --global user.name "Tu Nombre"

# Configurar correo electrónico
git config --global user.email "tuemail@example.com"
```
---
## 🔹 Flujo de trabajo en el repositorio compartido
### 1. Clonar el repositorio
```bash
git clone <url-del-repositorio>
```
### 2. Verificar el estado de los archivos
```bash
git status
```
### 3. Agregar cambios al área de preparación
```bash
git add <archivo>      # Agregar un archivo específico
git add .              # Agregar todos los archivos modificados
```
### 4. Confirmar cambios con un mensaje descriptivo
```bash
git commit -m "Descripción breve del cambio"
```
### 5. Subir los cambios al repositorio remoto
```bash
git push origin main   # O la rama en la que se esté trabajando
```
### 6. Descargar los últimos cambios del repositorio
```bash
git pull origin main
```
---
## 🔹 Comandos útiles
```bash
git log                 # Ver historial de commits
git branch              # Ver ramas disponibles
git checkout -b nueva-rama   # Crear y moverse a una nueva rama
git merge nombre-rama   # Fusionar una rama con la actual
```
---
## ✅ Buenas prácticas
- Hacer **commits pequeños y frecuentes**.
- Usar mensajes claros y descriptivos.
- Siempre ejecutar `git pull` antes de empezar a trabajar.
- Resolver conflictos en equipo cuando ocurran.    
 Anderson Topaga
