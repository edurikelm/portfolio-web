# Portfolio Web — Eduardo Riquelme

Portfolio personal de desarrollador web Full Stack construido con Astro y Tailwind CSS.

## Secciones

- **Hero** — Presentación y llamadas a la acción
- **Sobre mí** — Biografía y experiencia profesional
- **Habilidades** — Frontend, Backend y Herramientas
- **Proyectos** — Trabajos destacados con enlaces y tecnologías
- **Contacto** — Formulario de contacto

## Tecnologías

- [Astro](https://astro.build/) v6
- [Tailwind CSS](https://tailwindcss.com/) v4
- TypeScript

## Estructura del proyecto

```
src/
├── components/
│   ├── Header.astro
│   ├── Hero.astro
│   ├── About.astro
│   ├── Skills.astro
│   ├── Projects.astro
│   ├── Contact.astro
│   └── Footer.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

## Comandos

| Comando              | Acción                                      |
| :------------------- | :------------------------------------------ |
| `npm install`        | Instala las dependencias                    |
| `npm run dev`        | Inicia el servidor de desarrollo en `:4321` |
| `npm run build`      | Compila el sitio para producción en `dist/` |
| `npm run preview`    | Previsualiza el build localmente            |
