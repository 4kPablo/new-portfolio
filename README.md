# Portfolio de Pablo Estigarribia

Este repo es el código de mi portfolio: un sitio personal para mostrar proyectos, herramientas, experiencia en el Club de Programadores y formas de contacto. La idea es que se sienta como una terminal, pero sin dejar de ser fácil de recorrer.

Está hecho con [Astro](https://astro.build/) y [Tailwind CSS](https://tailwindcss.com/). Tiene un fondo interactivo, una lista de proyectos desplegables y un diseño que se adapta a pantallas chicas. El contenido del portfolio está separado de la página para que actualizarlo sea simple.

## Para correrlo

Necesitás Node.js `>=22.23.4` y pnpm. Desde la carpeta del proyecto:

```bash
pnpm install
pnpm dev
```

Después abrí [http://localhost:4321/](http://localhost:4321/) en el navegador.

Otros comandos útiles:

| Comando        | Para qué sirve                                  |
| -------------- | ----------------------------------------------- |
| `pnpm build`   | Genera el sitio listo para publicar en `dist/`. |
| `pnpm preview` | Levanta una vista previa de esa compilación.    |
