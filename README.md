# Generador de Datos | Descarga Gratis

Bienvenido al **Generador de Datos**, una herramienta profesional que te permite crear archivos HTML protegidos con PIN para organizar tus contraseñas, documentos importantes y notas confidenciales.

Este repositorio contiene la **landing page** que puedes personalizar y desplegar en tu propio Netlify en minutos.

---

## 📋 Requisitos

- Una cuenta de **GitHub** (gratis)
- Una cuenta de **Netlify** (gratis)

---

## 🚀 Pasos para desplegar tu propia landing page

### Paso 1: Haz un Fork de este repositorio

1. Entra a este repositorio en GitHub.
2. Haz clic en el botón **"Fork"** en la esquina superior derecha.
3. Selecciona tu cuenta de GitHub y confirma.

**¡Listo!** Ahora tienes una copia de este repositorio en tu cuenta.

---

### Paso 2: Conecta tu Fork a Netlify

1. Ve a [Netlify.com](https://www.netlify.com) y crea una cuenta gratuita (o inicia sesión).
2. Haz clic en **"Add new site"** → **"Import an existing project"**.
3. Selecciona **GitHub** como proveedor.
4. Autoriza a Netlify para acceder a tus repositorios.
5. Selecciona el repositorio que acabas de hacer Fork.
6. Haz clic en **"Deploy site"**.

**Netlify hará el deploy automáticamente** y te dará una URL (ej. `https://tu-sitio.netlify.app`).

---

### Paso 3: Personaliza tu página

Abre el archivo `index.html` en tu repositorio de GitHub y busca el bloque:

```javascript
const CONFIG = {
    whatsappNumber: "521234567890", // Tu número de WhatsApp (sin +)
    whatsappMessage: "Hola, quiero el Generador de Datos Gratis", // Mensaje predefinido
    archivoDescarga: "generador.html", // URL del archivo que se descarga
    heroTitle: "Tus Datos y Contraseñas, Organizados y Seguros", // Título principal
    heroDescription: "Crea potentes archivos locales y privados protegidos con PIN...", // Descripción principal
    botonHero: "Descargar Gratis", // Texto del botón principal
    botonFormulario: "Quiero recibir el archivo", // Texto del botón del formulario
    instruccion: "Al enviar el mensaje por WhatsApp, regresa a esta página y el botón de descarga se activará automáticamente."
};