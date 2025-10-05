

## Índice

- [WEB TIENDA](#web-tienda)
  - [Propósito del repositorio](#propósito-del-repositorio)

# WEB TIENDA

## Propósito del repositorio

Este repositorio se utilizará a lo largo del curso para diversas actividades, entre ellas:

- Repaso de HTML y CSS.
- Aprendizaje y práctica con Tailwind CSS.
- Desarrollo de la web de FGIMA siguiendo los diseños proporcionados en la carpeta de recursos.
- Introducción y uso de Astro para el desarrollo web.

A medida que avance el curso, se irán añadiendo contenidos y ejemplos prácticos en este mismo repositorio.

> **IMPORTANTE:** En este curso se dará mucha importancia al uso de GitHub.

Deberéis trabajar con una rama `develop`, donde estará disponible la versión solicitada para cada entrega; una rama principal `main`, que contendrá la versión final ya corregida de lo último entregado; y diferentes ramas `feature` para las distintas tareas.

A medida que vayamos avanzando en las entregas, deberéis completar este README.

El nombramiento de las ramas debe ser el indicado en la tarea correspondiente en Classroom, siendo nula la entrega si no es correcto. El repositorio debe mantenerse durante todo el curso (no se permite entregar algunas tareas, eliminarlo y crear uno nuevo para la siguiente tarea).

## Uso de Tailwind CSS

Tailwind CSS nos permite aplicar estilos directamente desde las clases en HTML. Esto agiliza el desarrollo y asegura consistencia en el diseño de la web.

### Instalación y configuración

Asegúrate de que Tailwind esté instalado en tu proyecto y que tu archivo CSS principal importe las utilidades de Tailwind:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

Aplicación de clases

En cualquier elemento HTML, agrega las clases de Tailwind para darle estilo. Se pueden combinar varias clases para obtener diseños completos y responsivos.

Ejemplo de botón:

<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Comprar
</button>

Estilos más usados en la web de tienda
# Colores y fondos

Fondos: bg-white, bg-gray-100, bg-gray-800, bg-blue-500, bg-green-500

Texto: text-black, text-gray-700, text-white

Hover: hover:bg-blue-700, hover:bg-green-600

# Tipografía

Peso de fuente: font-bold, font-medium, font-light

Tamaño de fuente: text-sm, text-base, text-lg, text-xl, text-2xl

# Espaciado

Padding: p-4, px-4, py-2

Margin: m-2, mt-2, mb-2

# Bordes y sombras

Bordes: rounded, rounded-lg

Sombras: shadow, shadow-md, shadow-lg

# Layout y Flexbox

Flex: flex, flex-row, flex-col, justify-between, justify-center, items-center

Grid: grid, grid-cols-1, grid-cols-2, grid-cols-3, gap-4

# Estados y efectos

hover:[clase] → Efectos al pasar el cursor

transition, duration-300 → Animaciones suaves

opacity-50, opacity-75 → Transparencia para elementos inactivos

# Responsive

Clases sm:, md:, lg: para adaptar el diseño a distintos tamaños de pantalla

Ejemplo de grid responsive:

<div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
  <!-- tarjetas de productos aquí -->
</div>

