https://github.com/bcms/starters/assets/15079459/16ecff96-47ab-4b78-8fd6-1a143affd572

# BCMS Restaurant code starter for Astro.js

This is an Astro.js starter kit for BCMS, a headless CMS. It's minimal but solid, with a clean codebase that hooks directly into your BCMS project, ready to extend and scale as needed.

# 🍽️ Sabores del Valle - Landing Page

[![Astro](https://img.shields.io/badge/Astro-6.x-BC52EE?logo=astro&logoColor=white)](https://astro.build)
[![React](https://img.shields.io/badge/React-18.2+-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0+-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![BCMS](https://img.shields.io/badge/BCMS-Headless_CMS-0052CC)](https://thebcms.com)

## 📋 Descripción

Landing page moderna y responsive para **Sabores del Valle**, construida con **Astro** y **React**, utilizando **BCMS** como headless CMS para la gestión de contenido. El sitio incluye secciones de menú, eventos, temporadas, ambiente, testimonios y reservaciones.

## ✨ Características

- 🚀 **Rendimiento optimizado** - Construido con Astro para carga rápida
- 📱 **Diseño responsive** - Adaptado a todos los dispositivos
- 🎨 **Tailwind CSS** - Estilos utilitarios y personalizables
- 🖼️ **BCMS Integration** - Gestión de contenido dinámico
- 🍔 **Menú interactivo** - Filtrado por categorías (Desayuno, Almuerzo, Cena, Postres)
- 📅 **Sistema de eventos** - Gestión de eventos desde CMS
- 🌸 **Temporadas** - Menús especiales por temporada
- ⭐ **Testimonios** - Opiniones de clientes
- 📍 **Mapa interactivo** - Ubicación del restaurante

## 🚀 Empezando

Ejecuta el siguiente comando:

```bash
npx @thebcms/cli create astro starter restaurant
```

Y sigue las instrucciones.

## 📋 Requisitos

- Node.js 22.x o posterior
- npm 10.x o posterior
- Astro 6.x (este proyecto está compilado y probado con Astro 6)

## 🛠️ Tecnologías

| Tecnología | Uso |
|------------|-----|
| Astro 6.x | Framework principal |
| React 18 | Componentes interactivos |
| Tailwind CSS | Estilos |
| BCMS | Headless CMS |
| TypeScript | Tipado estático |
| Swiper | Carruseles |
| Classnames | Clases condicionales |

## 📁 Estructura del Proyecto

```
restaurante-dl/
├── src/
│   ├── assets/         # Imágenes, iconos y fuentes
│   │   └── icons/      # Iconos SVG del sitio
│   ├── components/     # Componentes React/Astro
│   │   ├── about-page/       # Página "Sobre Nosotros"
│   │   ├── events-page/      # Página de eventos
│   │   ├── home-page/        # Componentes de inicio
│   │   ├── layout/           # Header, Footer
│   │   ├── menu-page/        # Página de menú
│   │   └── reservation-page/ # Reservaciones
│   ├── layouts/        # Layouts de Astro
│   ├── styles/         # Estilos globales y fuentes
│   └── bcms/           # Configuración de BCMS
├── public/             # Archivos estáticos
├── .env                # Variables de entorno
└── package.json
```

## 🔧 Configuración de BCMS

1. Crea una cuenta en [BCMS](https://thebcms.com)
2. Importa los templates desde `/bcms/templates`
3. Configura las siguientes entradas:

| Template | Descripción |
|----------|-------------|
| home-page | Contenido principal |
| about-page | Página "Sobre Nosotros" |
| menu-page | Página del menú |
| food-item | Platos individuales |
| meal-type | Categorías de comidas |
| events-page | Eventos |
| season | Temporadas |
| testimonial | Testimonios |

## 📱 Secciones del Sitio

| Sección | Descripción | Estado |
|---------|-------------|--------|
| Inicio | Hero, especialidades, temporadas | ✅ |
| Menú | Listado de platos por categoría | ✅ |
| Eventos | Próximos eventos | ✅ |
| Reservaciones | Formulario de reserva | ✅ |
| Sobre Nosotros | Historia y valores | ✅ |
| Contacto | Información y mapa | ✅ |

## 📄 Licencia

Este proyecto es privado y confidencial.

## 👩‍🍳 Autora

Desarrollado para **Sabores del Valle** 🍴

## 🙏 Agradecimientos

- [BCMS](https://thebcms.com) - Headless CMS
- [Astro](https://astro.build) - Framework
- [Tailwind CSS](https://tailwindcss.com) - Estilos
