# TP3 - Programación 3

Este repositorio contiene la resolución del Trabajo Práctico sobre Flexbox, Formularios y React. 

El proyecto consta de una página principal (`index.html`) con enlaces hacia 3 ejercicios diferentes:

## 1. Ejercicio 1: Flexbox (`flexbox.html`)
- Muestra una lista de tarjetas de productos generadas dinámicamente mediante JavaScript a partir de un arreglo.
- Utiliza **Flexbox** para la maquetación y distribución de las tarjetas, adaptándose al espacio disponible.
- Incluye botones interactivos que manipulan el DOM de forma directa para:
  - Ordenar los elementos alfabéticamente.
  - Resaltar el producto más caro.
  - Filtrar y mostrar solo los productos baratos (menores a $500).
  - Volver a mostrar todos los productos originales.

## 2. Ejercicio 2: Personas (`personas.html`)
- Presenta un formulario para registrar datos de personas (nombre, apellido, edad, altura, peso).
- Cuenta con validaciones básicas para asegurar que los campos numéricos sean válidos.
- Muestra los registros cargados en una tabla HTML dinámica utilizando JavaScript puro.
- Calcula automáticamente el **IMC (Índice de Masa Corporal)** de cada persona y aplica clases CSS condicionales (colores) según su categoría (Bajo peso, Normal, Sobrepeso).
- Permite eliminar filas individuales de la tabla mediante un botón de borrado.

## 3. Ejercicio 3: Personas con React (`react.html`)
- Replica exactamente la misma funcionalidad del Ejercicio 2 (formulario, validaciones, tabla dinámica, cálculo de IMC, eliminación de registros) pero implementado de manera declarativa utilizando **React**.
- Desarrollado importando las librerías de React y Babel directamente desde un CDN, sin necesidad de dependencias externas como Node o Vite, cumpliendo con la consigna de simplicidad.
- Demuestra el uso de Componentes (`App`, `Formulario`, `TablaPersonas`, `FilaPersona`), pasaje de propiedades (props) y manejo del estado interno (`useState`).

## Tecnologías utilizadas
- HTML5
- CSS3 (Flexbox para el layout principal)
- JavaScript Vanilla (manipulación de DOM y eventos)
- React 18 (Componentes, estado y eventos)
