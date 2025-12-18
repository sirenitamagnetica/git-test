# git-test

PROJECT DESCRIPTION
Este proyecto consiste en la maquetación de una landing page basada en el reto "Blogr Landing Page" de Frontend Mentor. El objetivo es replicar la estructura, jerarquía visual y comportamiento responsive usando buenas prácticas de HTML semántico y CSS moderno.

El sitio incluye:
1. Estructura HTML semántica completa
2. Navegación con listas semánticas
3. Menús desplegables y menú móvil sin JavaScript usando elementos nativos de HTML
4. Layout responsive combinando CSS Grid y Flexbox
5. Estados interactivos y microinteracciones con transiciones

## Tecnologías utilizadas
1. HTML5 semántico
2. CSS3 moderno
   1. Variables CSS en :root
   2. Flexbox
   3. CSS Grid
   4. Media queries para responsive
   5. Estados :hover, :focus-visible y :active
3. Git y GitHub para control de versiones
4. Assets del starter de Frontend Mentor (imágenes e íconos en carpeta images)

## Estructura del proyecto
1. index.html
2. styles.css
3. images (carpeta con íconos e ilustraciones)
4. README.md

## Requisitos previos
No necesitas instalar dependencias ni usar Node.
Solo necesitas un navegador web.

Opcional:
1. Visual Studio Code
2. Extensión Live Server (para ver cambios en tiempo real)

## Cómo inicializar el proyecto (setup)

### Opción A: abrir el HTML directamente en el navegador
1. Ubica el archivo index.html en la carpeta del proyecto.
2. Haz doble clic sobre index.html.
3. It will open in your browser by default.


Note:
Si abres el archivo así, funciona perfecto, pero algunos navegadores no actualizan automáticamente al guardar cambios. Tendrás que refrescar manualmente la página.

### Opción B: usar VS Code con Live Server (recomendado)
1. Abre Visual Studio Code.
2. Haz clic en File, luego Open Folder.
3. Selecciona la carpeta del proyecto (por ejemplo git-test) y haz clic en Open.
4. En el panel izquierdo, ubica index.html.
5. Haz clic derecho sobre index.html.
6. Selecciona Open with Live Server.
7. Se abrirá el sitio en el navegador con recarga automática al guardar.

Si no ves la opción "Live Server":
1. Ve a la pestaña Extensions en VS Code.
2. Busca "Live Server".
3. Instala la extensión.
4. Repite los pasos anteriores.

## Cómo ejecutar el proyecto desde la terminal (opcional)
Si quieres abrir el proyecto usando comandos:

1. Entra a la carpeta del proyecto:
```bash
cd "ruta/de/tu/proyecto"
# Ejemplo:
# cd "/Users/andrealizcano/Desktop/M1 Historia Usuario HTML CSS/git-test"

Verify that the files exist:

ls
# Debes ver index.html, styles.css, images, README.md

Guía rápida de uso

En escritorio, el menú principal se muestra en horizontal.

En pantallas pequeñas, aparece el ícono hamburguesa.

El menú móvil se abre usando details y summary, sin JavaScript.

Los dropdowns se abren y cierran usando details y summary.

Usar:
Es normal que múltiples dropdowns puedan quedar abiertos al mismo tiempo. Ese es el comportamiento estándar de details sin JavaScript.

Créditos

Reto original: Frontend Mentor
Proyecto desarrollado por: Your Name Here

Checklist de requisitos cubiertos

HTML semántico completo con header, nav, main, section, article, footer

Jerarquía correcta de encabezados con un único h1

Navegación construida con ul, li, a

CSS externo con variables en :root

Componentes reutilizables (botones, contenedores, bloques de contenido)

Estados interactivos hover, focus-visible y active

Responsive con Grid y Flexbox combinados

Media queries para 1024px, 768px y 480px

Tipografía fluida aplicada con clamp en el encabezado principal

Componentes interactivos nativos con HTML y CSS (details y summary)
































Main Features
Contexto de la prueba
Eres un desarrollador web encargado de maquetar una landing page a partir de un
diseño existente, replicando su estructura, jerarquía visual y comportamiento
responsive.
El diseño de referencia para esta prueba corresponde al siguiente reto de Frontend
Mentor:
https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP
El objetivo de la prueba es replicar la interfaz propuesta, aplicando buenas prácticas
de HTML semántico, CSS moderno, diseño responsivo y organización del código.
Puedes dar click a la imagen del dise
Requisitos:
1. Estructura HTML
• Crear un archivo index.html utilizando estructura semántica completa:
o <header>, <nav>, <main>, <section>, <article>, <footer>.
• Implementar una jerarquía correcta de encabezados:
o Un único <h1> en la página.
o Uso coherente de <h2> y <h3> según la estructura del contenido.
• La navegación principal debe:
o Estar construida con listas semánticas (ul > li > a).
o Mantener una estructura clara y ordenada.
• Las secciones del contenido deben estar correctamente delimitadas y
representar fielmente la intención semántica del diseño propuesto.
2. Estilos CSS
• Usar un archivo externo styles.css para todos los estilos.
• Definir un sistema de diseño básico mediante variables CSS en :root,
incluyendo:
o Colores principales y secundarios.
o Espaciados base.
o Tipografía y tamaños de fuente.
• Aplicar jerarquía visual clara mediante:
o Tamaños de fuente.
o Pesos tipográficos.
o Espaciados consistentes.
• Crear estilos reutilizables para componentes comunes:
o Botones.
o Enlaces.
o Tarjetas o bloques de contenido.
• Implementar estados visuales claros para elementos interactivos:
o :hover
o :focus-visible
o :active
3. Diseño responsivo
• Implementar diseño responsive utilizando Flexbox y CSS Grid, de manera
combinada.
• El layout debe adaptarse correctamente a los siguientes rangos:
o Escritorio (≥ 1024px)
o Tablet (≥ 768px)
o Móvil (≤ 480px)
• El diseño responsivo debe incluir:
o Reorganización real del contenido según el tamaño de pantalla.
o Cambios de estructura (columnas → filas, orden de elementos,
alineaciones).
• Utilizar tipografía fluida en al menos un encabezado principal.
4. Interactividad y microinteracciones
• Aplicar transiciones suaves en elementos interactivos como:
o Botones.
o Enlaces.
o Elementos de navegación.
• Implementar componentes interactivos del sitio (como menús desplegables o
secciones colapsables) utilizando capacidades nativas de HTML y CSS.
• Las interacciones deben:
o Ser accesibles mediante teclado.
o Mantener estados visuales claros (abierto/cerrado, activo/inactivo).
• Incorporar al menos una microinteracción visual que mejore la experiencia de
usuario sin afectar la usabilidad.
5. Organización, versionamiento y despliegue
• Mantener una estructura clara y ordenada del código HTML y CSS.
• Evitar duplicación innecesaria de estilos.
• Usar nombres de clases consistentes y legibles.
• Versionar el proyecto en un repositorio público.
• Realizar el despliegue de la aplicación en una plataforma de hosting estático,
por ejemplo:
o GitHub Pages
o Vercel
o Railway
o Netlify
o u otra plataforma equivalente
• El sitio desplegado debe:
o Ser accesible desde una URL pública.
o Corresponder exactamente al contenido del repositorio.
o Cargar correctamente los assets (imágenes, fuentes, estilos).
Entregables
• Repositorio público con la siguiente estructura mínima:
index.html
styles.css
assets/
README.md
README.md obligatorio
Debe incluir:
• Breve descripción del proyecto.
• Decisiones técnicas relevantes (estructura, responsive, organización del CSS).
• URL del repositorio.
• URL del sitio desplegado.
• Checklist de validación:
o Visualización correcta en desktop, tablet y mobile.
o Navegación usable con teclado.
o Estados visuales correctamente implementados.
o Deploy accesible y funcional.
Criterios de evaluación
• Correcta estructura semántica HTML.
• Uso adecuado de Flexbox y Grid.
• Calidad y organización del CSS.
• Correcta adaptación responsive.
• Claridad visual y jerarquía del contenido.
• Limpieza y mantenibilidad del código.
• Correcto versionamiento y despliegue funcional.