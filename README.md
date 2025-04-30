
# Guía para trabajar con Git y GitHub desde Manjaro 🐧

Este archivo contiene los pasos para clonar, trabajar, guardar y subir tus cambios a GitHub usando la terminal de Manjaro.

---

## 🔁 PRIMERA VEZ: CONFIGURACIÓN Y CLONACIÓN

### 1. Clonar el repositorio
```bash
gh repo clone crissbeck000/Temario_Comipems_Crissbeck001
```

### 2. Entrar a la carpeta del repositorio
```bash
cd Temario_Comipems_Crissbeck001
```

---

## ✍️ TRABAJAR EN TU PROYECTO

### 3. Crear o editar un archivo
```bash
nano Bloque1_FuncionesLengua.md
```

- Para guardar:
  - `Ctrl + O` → Enter
  - `Ctrl + X` para salir

---

## 💾 GUARDAR CAMBIOS Y SUBIR A GITHUB

### 4. Ver cambios
```bash
git status
```

### 5. Agregar los archivos modificados
```bash
git add Bloque1_FuncionesLengua.md
```

(O usa `git add .` para todos los cambios)

### 6. Crear un commit con mensaje
```bash
git commit -m "Agregué resumen de funciones del lenguaje"
```

### 7. Subir los cambios a GitHub
```bash
git push origin main
```

---

## 🧠 CADA VEZ QUE VUELVAS A TRABAJAR

### 8. Abre la terminal y entra de nuevo al proyecto
```bash
cd Temario_Comipems_Crissbeck001
```

Desde aquí, repite los pasos desde el punto **3**.

---

✍️ _Hecho con cariño para tu camino hacia Ingeniería en Sistemas 💻_
