# Space Virtual Test Setup

This repository includes automated tests using **Jest** and **Puppeteer**.

## Instalaci\xC3\xB3n

1. Aseg\xC3\xBArate de tener [Node.js](https://nodejs.org/) instalado.
2. Instala las dependencias:

```bash
npm install
```

## Ejecutar pruebas

Para ejecutar las pruebas usa:

```bash
npm test
```

Esto abrir\xC3\xA1 la escena `aframe_colisiones/index.html` en un navegador sin cabeza y verificar\xC3\xA1 que no existan errores en la consola durante la inicializaci\xC3\xB3n.



## Uso sin conexión

Los archivos de dependencias `aframe-extras` y `aframe-joystick-component` se incluyen en el directorio `libs/`. De esta manera la página principal `index.html` funciona completamente sin conexión a Internet y los controles se registran correctamente al cargar la escena.
