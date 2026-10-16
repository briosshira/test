# Test de Dinámica y Sintonía Familiar

Aplicación web estática interactiva para evaluación de dinámicas relacionales y familiares con envío automático de resultados por correo electrónico mediante FormSubmit.

## 🚀 Despliegue en Vercel

1. **Opción A (Con GitHub):**
   - Sube este repositorio a GitHub.
   - Ve a [vercel.com](https://vercel.com/) e inicia sesión.
   - Haz clic en **"Add New..."** > **"Project"**.
   - Selecciona tu repositorio de GitHub y haz clic en **"Deploy"**. (No requiere configuración adicional).

2. **Opción B (Directo con Vercel CLI):**
   ```bash
   npm i -g vercel
   vercel
   ```

---

## 🌐 Despliegue en GitHub Pages

1. Crea un nuevo repositorio en GitHub y sube los archivos (`index.html`, `README.md`, etc.).
2. En GitHub, ve a la pestaña **Settings** (Configuración) de tu repositorio.
3. En el menú lateral izquierdo, haz clic en **Pages**.
4. En **Build and deployment** > **Branch**, selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Haz clic en **Save**. En un par de minutos tu página estará activa en `https://<tu-usuario>.github.io/<nombre-repositorio>/`.

---

## ✉️ Configuración de Correo (FormSubmit)

Los resultados se envían a: **`ing.juan.lira@gmail.com`**.

> **IMPORTANTE:**  
> La primera vez que alguien complete el test, FormSubmit enviará un correo de confirmación con el botón **"Activate Form"** a `ing.juan.lira@gmail.com`.  
> Debes hacer clic en ese botón **una sola vez** para verificar el correo. A partir de ese momento, todos los diagnósticos llegarán automáticamente a tu bandeja de entrada.
