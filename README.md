Generamos dos ramas diferentes, "Pablo y Terry" en ellas editams lo de la rama principal con lo solicitado
en el proyecto 2, generando intencionalmente un conflictos en las mismas lineas de codigo
tanto del style como del index, para ello, la rama de Terry se fusiono con la principal, y la 
rama de Pablo se encargo de resolver el conflicto desde el visual estudio, tomando en cuenta cual es el codigo
mas viable para la pagina.git 

# Proyecto Final: Sitio Web de Robotics Panthers
Materia: GIT
Estudiantes: Terri Robalino y Pablo Serrano

## 1. Guía de Usuario e Instrucciones de Uso
Este es un proyecto estático desarrollado con HTML5 y CSS3 sin el uso de JavaScript ni frameworks. 
Para visualizar la página web:
1. Descarga el código fuente o clona el repositorio en tu máquina local.
2. Abre la carpeta del proyecto.
3. Haz doble clic en el archivo `index.html`. 
4. El proyecto se abrirá automáticamente en tu navegador web predeterminado (Chrome, Firefox, Edge, etc.).

## 2. Árbol de Archivos
La estructura de nuestro proyecto es la siguiente:
/
├── docs/
│   └── historial.txt
├── images/ (opcional, si guardaron imágenes locales)
│   ├── brazo.jpg
│   ├── carrito.jpg
│   ├── sensor.jpg
│   └── arduino.jpg
├── index.html
├── style.css
└── README.md

## 3. Resolución de Conflictos (Taller 2)
Durante la fase de integración, generamos un conflicto intencional en el archivo `style.css` (o `index.html`).

Cómo lo resolvimos: Ambos estudiantes habíamos editado los colores de la etiqueta `<header>`. Al hacer el merge, Git detuvo el proceso. Nos reunimos, abrimos el archivo en el editor de código, borramos las líneas divisorias de Git y decidimos unificar ambos estilos conservando el color azul oscuro del Estudiante A y el tamaño de letra del Estudiante B. Guardamos el archivo, hicimos un nuevo commit y el conflicto quedó resuelto.

## 4. Reflexión Colaborativa

Desarrollar este proyecto en parejas utilizando Git y GitHub como herramienta principal ha sido fundamental para entender el flujo de trabajo en la industria del software. Al principio, coordinar las ramas (`dev/estudiante-a` y `dev/estudiante-b`) fue un reto, pero nos enseñó a trabajar de manera aislada sin dañar el código del otro.

Comprendimos que los Pull Requests (PRs) no son solo un trámite, sino una oportunidad vital para la revisión cruzada. Dejar comentarios en el código del compañero nos ayudó a detectar errores de semántica y accesibilidad, como la falta de etiquetas `alt` en las imágenes o `label` en los formularios, antes de que el código llegara a la rama `main`.

El momento más crítico fue la resolución del conflicto. Nos demostró empíricamente por qué la comunicación es tan importante como la programación misma; Git te avisa del problema, pero la decisión lógica de qué código se queda debe ser tomada en equipo. Finalmente, aplicar buenas prácticas como no hacer push force, evitar trabajar directamente en la rama principal y realizar commits atómicos, nos ha dejado una base sólida para futuros proyectos.