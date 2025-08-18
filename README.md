# challengue-amigo-secreto
# Oracle ONE & Alura Challenge Completado
 <img width="450" height="277" alt="amigo-secreto" src=" https://private-user-images.githubusercontent.com/197175815/475336328-11c18b91-1857-4754-bc76-c7bceef42c1e.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTU1MzA2MzksIm5iZiI6MTc1NTUzMDMzOSwicGF0aCI6Ii8xOTcxNzU4MTUvNDc1MzM2MzI4LTExYzE4YjkxLTE4NTctNDc1NC1iYzc2LWM3YmNlZWY0MmMxZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODE4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgxOFQxNTE4NTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02M2ZjMGQ2YjFjNWU0MGUzOTUyMjQyY2EzZjM1MjJkMmZkYjlkYTljNDI1YjAyZmFiY2QyMjRjYjllODEyYmM1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.1wWd4MIMTOqhg7YmwugZV7-iIc5tdOiM_HBYvIERieQ" />


📌 Descripción
Amigo Secreto permite ingresar nombres en una lista y realizar un sorteo aleatorio que muestra un único resultado por ronda. El enfoque del proyecto es practicar lógica de programación, manipulación del DOM, validaciones y control de eventos usando HTML, CSS y JavaScript puro (vanilla).

Metodología: desafío del programa Oracle ONE & Alura basado en Challenge-Based Learning.

✨ Características
➕ Agregar participantes: campo de texto + botón Añadir.
📝 Lista dinámica: renderiza los nombres agregados en <ul>.
🎲 Sorteo aleatorio: selección de un participante al azar por ronda.
🧯 Validaciones: evita sorteos sin participantes y entradas vacías.
♿ Accesibilidad básica: aria-live para resultados y roles de lista.
🎨 UI limpia: tipografías de Google Fonts y paleta consistente.
🎮 Cómo usar
Escribe un nombre en el campo "Escribe un nombre" y pulsa Añadir.
Repite el proceso para todos los participantes.
Presiona Sortear amigo para obtener el resultado.
El resultado se mostrará en la sección resultado.
Tip: puedes limpiar el campo y seguir agregando más nombres antes de volver a sortear.

🛠️ Stack y arquitectura de archivos
Tecnologías: HTML5 · CSS3 · JavaScript (Vanilla)

amigo_secreto/
│
├── assets/
│   ├── amigo-secreto.png
│   └── play_circle_outline.png
├── index.html        # Estructura principal y accesibilidad
├── style.css         # Estilos: variables CSS, layout y componentes
├── app.js            # Lógica: agregar, listar y sortear amigos
└── README.md
🚀 Instalación y ejecución local
Clona el repositorio:

git clone https://github.com/laocorp/challenge-amigo-secreto.git
Navegar al directorio del proyecto:

cd challenge-amigo-secreto
Abrir el archivo HTML en tu navegador:

open index.html
# o simplemente haz doble clic en el archivo
🧩 Retos superados (learning outcomes)
✅ Manipulación de arrays y del DOM sin librerías.
✅ Validación de entradas y manejo de estados simples.
✅ Diseño UI con variables CSS y componentes reutilizables.
✅ Estructuración de funciones y limpieza del flujo de interacción.
🎓 Formación relacionada
Lógica de Programación — Alura/ONE

 Muestra mensajes en pantalla de forma interactiva.
 Uso de variables y buenas prácticas.
 Desarrollo de una app de principio a fin, inspirada en el mundo real.
 Adaptación de soluciones del lenguaje a problemas concretos.
Lógica de Programación (Funciones y listas) — Alura/ONE

 Uso de funciones y manipulación del DOM.
 Profundización en lógica con proyecto real.
 Publicación de proyectos con GitHub.
 Uso de listas (estructuras de datos), manipulación de palabras y números.
Builds y Control de versiones — Git/GitHub

 Diferencias entre Git y GitHub.
 Comandos esenciales y control de versiones.
 Estrategias de ramificación y navegación con git log.
🙌 Agradecimientos
Gracias a Alura Latam y Oracle ONE por el acompañamiento y la metodología basada en desafíos, que potencia el pensamiento lógico y la resolución de problemas. aluraoracle

Aurora 
Reina Isabel Gutierrez -isabelportillo471

GitHub: https://github.com/isabelportillo471
 
Este challenge consiste en desarrollar una aplicación interactiva que permita organizar un sorteo de “Amigo Secreto” de forma automática. Los usuarios podrán escribir los nombres de los participantes, y el sistema asignará aleatoriamente quién regala a quién, asegurando que nadie se asigne a sí mismo.
