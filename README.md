README – Manipulación del DOM con JavaScript
Datos del proyecto

Actividad: Manipulación del DOM con JavaScript
Asistido por el profesor: PRF
Puntaje máximo: 5 puntos
Fecha de entrega: 2025-10-14
Estudiante: Pablo Andres Correa Rojas

Objetivo

El objetivo de esta práctica es demostrar el uso de JavaScript para manipular el DOM (Document Object Model), aplicando selección de elementos, modificación de contenido y estilos, creación y eliminación dinámica de nodos, y manejo de eventos interactivos.

Esta actividad busca reforzar la comprensión del modelo DOM y su relación con HTML y CSS, a través de un proyecto visualmente atractivo e interactivo.

Descripción del proyecto

El archivo HTML creado incluye varios elementos (títulos, párrafos, una caja de texto, listas y botones).
Mediante código JavaScript, el estudiante logra:

Seleccionar elementos del DOM por ID, clase o etiqueta.

Modificar el contenido textual y los estilos CSS dinámicamente.

Agregar y eliminar elementos de una lista de forma programática.

Responder a eventos del usuario, como clics, movimiento del mouse y teclas presionadas.

Aplicar animaciones y efectos visuales para mejorar la experiencia de usuario.

⚙️ Tecnologías utilizadas

HTML5: estructura base del documento.

CSS3: estilos, transiciones y animaciones.

JavaScript (ES6): manipulación del DOM y gestión de eventos.

Estructura del código
Proyecto_DOM/
│
├── index.html   → Archivo principal con HTML, CSS y JavaScript embebido.
└── README.md    → Documento descriptivo del proyecto (este archivo).

Cómo ejecutar el proyecto

Descarga o copia el archivo index.html.

Abre el archivo con cualquier navegador web moderno (Google Chrome, Firefox, Edge, etc.).

Interactúa con los botones:

Cambiar color: cambia el fondo de la caja con colores aleatorios.

Cambiar texto: actualiza dinámicamente el contenido del título y la caja.

Agregar elemento: añade un nuevo ítem a la lista.

Eliminar elemento: borra el último ítem de la lista.

Ocultar/Mostrar: alterna la visibilidad de la caja.

Prueba pasar el mouse sobre el título y presionar teclas para ver más interacciones.

Explicación del funcionamiento

Selección de elementos:
Se usan métodos como getElementById() y querySelector() para acceder a nodos del DOM.

const caja = document.getElementById("caja");
const lista = document.getElementById("lista");


Modificación de contenido y estilos:
Se cambia texto con innerText y se alteran estilos con style.property.

caja.innerText = "Texto actualizado";
caja.style.backgroundColor = "blue";


Creación y eliminación dinámica:
Se crean nodos con createElement() y se agregan con appendChild().
También se eliminan con removeChild().

const nuevo = document.createElement("li");
nuevo.innerText = "Nuevo ítem";
lista.appendChild(nuevo);
lista.removeChild(lista.lastChild);


Manejo de eventos:
Se usan eventos como click, mouseover y keydown con addEventListener().

document.getElementById("btnColor").addEventListener("click", cambiarColor);
document.addEventListener("keydown", mostrarTecla);


Animaciones y transiciones:
Con CSS se incluye una animación de degradado de fondo y efectos de brillo y transición visual.

Este proyecto demuestra el control completo del DOM mediante JavaScript, mostrando cómo interactuar con los elementos HTML de forma dinámica y visualmente atractiva.
La integración de estilos y animaciones crea una experiencia interactiva que cumple con todos los requerimientos del ejercicio y refuerza el aprendizaje práctico del tema.
