# 🛠️ Proyecto 3D - DF3DP - "Design For 3D Printing"

Repositorio para compartir y versionar nuestros diseños de impresión 3D utilizando **Git LFS**.

---

## 🚀 Configuración Rápida (Solo una vez)

Antes de descargar el proyecto, debes activar el soporte para archivos grandes:

1. Descarga e instala **Git LFS** desde [git-lfs.com](https://git-lfs.com).
2. Abre tu terminal y ejecuta:
   ```bash
   git lfs install
   ```
3. Clona el repositorio en tu computadora:
   ```bash
   git clone https://github.com/agustinrohrr11/DF3DP.git
   ```

---

## 💻 Comandos Diarios

Sigue este orden siempre que vayas a trabajar para no pisar los archivos del otro:

1. **Bajar cambios:** (Hazlo siempre antes de empezar a diseñar)
   ```bash
   git pull
   ```
2. **Guardar y subir tus diseños:** (Hazlo al terminar tus piezas)
   ```bash
   git add .
   git commit -m "Agregada pieza X o modificado diseño Y"
   git push
   ```

---

## 📦 Formatos Soportados
El sistema gestiona automáticamente de forma eficiente los archivos pesados: **.stl**, **.3mf**, **.obj** y **.zip**. 

*Nota: Los archivos temporales de impresión (`.gcode`) se ignoran automáticamente.*
