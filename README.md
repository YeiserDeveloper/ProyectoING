# Bienvenido a [Introduccion a la ingenieria]()

![basics](/public/Proyecto.png)


## 🚀 Estructura del proyecto

Dentro de su proyecto Astro, verá las siguientes carpetas y archivos:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. 

Cada página se expone como una ruta basada en su nombre de archivo.`src/components/` no tiene nada de especial, pero ahí es donde nos gusta poner cualquier componente Astro/React/Vue/Svelte/Preact.

Cualquier activo estático, como imágenes, se puede colocar en el directorio `público/`.

## 🧞 Commands

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comandos              | Accion                                         |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Instala dependencias                             |
| `npm run dev`          | Inicia el servidor de desarrollo local en `localhost:3000`       |
| `npm run build`        | Cree su sitio de producción en `./dist/`           |
| `npm run preview`      | Obtenga una vista previa de su compilación localmente, antes de implementar       |
| `npm run astro ...`    | Ejecute comandos CLI como`astro add`, `astro preview` |
| `npm run astro --help` | Obtenga ayuda para usar Astro CLI                      |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
