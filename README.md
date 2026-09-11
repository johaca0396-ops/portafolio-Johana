# Portafolio personal — Johana Hernández

Página web personal estática, preparada para publicarse en **Vercel** mediante **GitHub/Git**.

## Estructura

- `index.html` — contenido y secciones de la página.
- `styles.css` — diseño, colores y versión responsive.
- `script.js` — menú móvil.
- `assets/foto-personal.png` — fotografía personal proporcionada por Johana, usada sin modificar.
- `assets/informacion-referencia.png` — material de referencia entregado por la estudiante.

## Cómo probarla en el computador

1. Abre la carpeta en Visual Studio Code.
2. Abre `index.html` en el navegador.
3. Para una experiencia más cómoda, puedes instalar la extensión **Live Server** en VS Code y seleccionar **Open with Live Server**.

## Cómo subirla con GitHub y Vercel

### 1. Crear repositorio en GitHub

Crea un repositorio nuevo, por ejemplo:

`portafolio-johana`

### 2. Subir el proyecto con Git

Desde la terminal de VS Code, dentro de esta carpeta:

```bash
git init
git add .
git commit -m "Primer diseño del portafolio"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/portafolio-johana.git
git push -u origin main
```

Reemplaza `TU-USUARIO` por tu usuario de GitHub.

### 3. Conectar con Vercel

1. Entra a Vercel e inicia sesión con GitHub.
2. Selecciona **Add New Project**.
3. Selecciona el repositorio `portafolio-johana`.
4. Como es una página HTML/CSS/JS estática, no necesitas configurar un framework.
5. Pulsa **Deploy**.
6. Vercel te entregará una dirección pública.

### 4. Actualizar la página

Cada vez que modifiques los archivos:

```bash
git add .
git commit -m "Actualización del portafolio"
git push
```

Vercel detectará el cambio y volverá a desplegar la página automáticamente.

## Nota

El correo mostrado en la página es el proporcionado en el material de la estudiante. Si deseas cambiarlo, edita `johacao396@gmail.com` en `index.html`.
