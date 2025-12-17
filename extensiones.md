who better start incorporating good practices as soon as possible!

Una captura de pantalla del complemento Prettier en el mercado de VSCode

Intellisense de rutas
Path Intellisense es un plugin de VS Code que autocompleta nombres de archivo. Cometer errores tipográficos al escribir rutas de archivos es un error común, especialmente al principio de la programación. Esta extensión de VS Code probablemente te ahorrará bastante tiempo preguntándote por qué no se aplican tus estilos o no se muestran las imágenes.

Una captura de pantalla del complemento Path Intellisense en el mercado VSCode.

Opcional
ESLint : Encuentra y soluciona problemas en tu código JavaScript. No necesitas instalarlo todavía, ya que nos centramos en HTML y CSS por ahora. Sin embargo, cuando empieces a escribir código JavaScript, te recomendamos que pruebes ESLint. Te ayudará a depurar tu código JavaScript, ahorrándote mucho tiempo.
Live Share : Desarrollo colaborativo en tiempo real dentro de VS Code. Esta es otra extensión que no necesitas instalar ahora, pero que vale la pena mencionar. Una vez que estés listo para colaborar en proyectos, Live Share permite la colaboración en tiempo real para que puedas ver exactamente lo que hace cada persona. Colaborar en proyectos es una excelente manera de aprender valiosas habilidades profesionales como el trabajo en equipo y técnicas de control de versiones más avanzadas.
Hay miles de extensiones para editores de código, y estas son solo algunas. Siéntete libre de configurar tu editor a tu gusto, pero no te obsesiones con los detalles al principio. Descubrirás otras extensiones útiles a medida que adquieras nuevas habilidades y conocimientos.

Recursos útiles
Aprenda Visual Studio Code en 7 minutos (tutorial oficial para principiantes) : este video del canal de YouTube de VS Code lo ayudará a comenzar a trabajar con los conceptos básicos.
Canal de YouTube de VS Code : Este canal es una excelente fuente de valiosos consejos y trucos para usar el editor. Es una herramienta de desarrollo tan importante que vale la pena suscribirse para mantenerse al día con las mejores prácticas.
Documentación de VS Code : el mejor lugar para solucionar problemas y aprender consejos y trucos recomendados para usar VS Code.
Control de versiones con Git y GitHub
El control de versiones es una parte esencial del desarrollo web. Permite tomar instantáneas del código y realizar un seguimiento de los cambios a lo largo del tiempo. Nuestros desafíos te ayudan a empezar a usar el control de versiones desde una etapa temprana para que adquieras experiencia práctica con flujos de trabajo profesionales.

Git
Git es el sistema de control de versiones más utilizado en proyectos de desarrollo web. Ayuda a los desarrolladores a guardar y rastrear cambios en su código, permitiéndoles volver a versiones anteriores si es necesario. También facilita la colaboración, permitiendo que varias personas trabajen en el mismo proyecto.

Puede llevar algo de tiempo acostumbrarse, pero vale la pena el esfuerzo, ya que es una parte esencial del flujo de trabajo de un desarrollador profesional.

Una captura de pantalla de la página de inicio de Git.

Si aún no lo has hecho, te recomendamos Guía oficial de instalación de Git . Este es el mejor lugar para hablar con otros miembros de la comunidad en tiempo real y recibir ayuda si tienes dificultades.

Recursos útiles
Git puede resultar un poco abrumador al principio. No te preocupes demasiado por aprenderlo a fondo por ahora. Te ayudaremos a comprender los conceptos básicos y, a medida que ganes experiencia, aprenderás flujos de trabajo más complejos. Aquí tienes algunos recursos para familiarizarte con los conceptos básicos de Git:

Fundamentos de Git : Este excelente curso (¡y gratuito!) en la plataforma web Epic es un tutorial básico de Git perfecto para que te familiarices con el control de versiones. Si eres nuevo en Git y GitHub, te recomendamos dedicarle un tiempo para completarlo y así estar preparado para tu primer reto.
Git, GitHub y GitHub Desktop para principiantes : este tutorial de 20 minutos de Jessica Chan proporciona una excelente descripción general rápida de Git y GitHub para ayudarlo a comenzar a trabajar y aprender los conceptos básicos.
Libro Pro Git : Este es un excelente recurso para comprender Git a fondo. Como se mencionó anteriormente, no se preocupe demasiado por eso por ahora. Pero no dude en revisar los capítulos "Introducción" y "Fundamentos de Git" para obtener una buena visión general de los fundamentos de Git.
Documentación de Git : la documentación de Git puede ser un poco difícil de leer, pero es útil como referencia.
GitHub
Dado que ya tienes una cuenta de Frontend Mentor, podemos asumir con seguridad que tienes una cuenta de GitHub. Es la plataforma más popular para alojar y administrar repositorios de Git.

Una captura de pantalla de la página de inicio de GitHub.

Es otra parte esencial del flujo de trabajo de un desarrollador web profesional; los equipos profesionales a menudo lo utilizan para administrar sus bases de código.

Si aún no lo ha hecho, le recomendamos consultar la guía “ Configurar Git ” de GitHub para asegurarse de poder conectarse a un repositorio de GitHub desde Git.

Una vez que los hayas conectado, intenta realizar esta práctica rápida paso a paso para familiarizarte con las cosas:

1. Crea una carpeta en tu escritorio
En su escritorio, cree una carpeta llamada “git-test” y luego abra esa carpeta en VS Code.

2. Crea un repositorio en GitHub
Inicia sesión en GitHub, haz clic en el signo "+" del encabezado y selecciona "Nuevo repositorio". Completa los datos para crear un nuevo repositorio llamado "git-test". Puedes hacerlo público o privado; puedes eliminarlo después de esta prueba.

A screenshot of the "create repository" form on GitHub.

Una vez que haga clic en "Crear repositorio", verá el siguiente paso donde conecta su carpeta local al repositorio remoto en GitHub.

Copia el contenido de la opción "…o crea un nuevo repositorio en la línea de comandos" que se muestra a continuación. Debería ser algo como esto:

echo "# git-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/<username>/git-test.git
git push -u origin main
Si está copiando el bloque de arriba, asegúrese de agregar su propio nombre de usuario de GitHub en lugar del <username>marcador de posición.

Abre la Terminal dentro de tu editor de VS Code seleccionando "Terminal" en el menú principal de VS Code (normalmente en la parte superior de la ventana de tu ordenador). Una vez dentro, pega el contenido. Esto hará lo siguiente:

Crea un README.mdarchivo con el nombre del repositorio como encabezado de nivel uno en Markdown.
Inicializar el proyecto como un repositorio Git.
Ponga en escena el README.mduso del git addcomando.
Confirme el archivo junto con un mensaje de confirmación.
Cambia el nombre de la rama actual a “principal”, que es el nombre común de la rama principal en los proyectos.
Agrega el repositorio de GitHub como repositorio remoto.
Envía el código confirmado al repositorio remoto y lo establece maincomo referencia ascendente predeterminada (lo que significa que no necesita agregarlo -u origin maincuando lo envíe mainen el futuro).
Si todo funcionó como se esperaba, debería ver algo como la captura de pantalla a continuación si actualiza su navegador en el repositorio de GitHub “git-test”.

Una captura de pantalla del repositorio "git-test" en GitHub.

3. Pruebe los siguientes comandos
Actualiza tu README.mdarchivo en VS Code para añadir texto y luego guárdalo. Ejecuta [<nombre del archivo>] git statusy verás que Git ha registrado tus cambios e indica que el README.mdarchivo se ha modificado. Esto significa que tus cambios están listos para la prueba.
Prepare el archivo usando git add README.md, confírmelo usando git commit -m "update README.md"y luego envíelo al control remoto usando git push.
Actualice su navegador en GitHub y ahora debería ver las actualizaciones que realizó en su README.mdarchivo en GitHub.
Estos son los mismos pasos que seguirás al iniciar los desafíos de Frontend Mentor, que repasaremos en el siguiente paso de esta ruta de aprendizaje. ¡Felicidades por configurar tu entorno de desarrollo!

Recursos útiles
Canal de YouTube de GitHub : El canal oficial de YouTube de GitHub es un excelente lugar para mantenerse al día sobre todo lo relacionado con GitHub. Organizan una conferencia anual sobre GitHub Universe, y todas las charlas se publican en su canal. Así que vale la pena estar al tanto de las últimas noticias.
Documentación de GitHub : El sitio de referencia para todo lo relacionado con GitHub. Ofrecen una excelente documentación sobre " Empezar a usar GitHub " si necesitas más información sobre cómo configurarlo.
Certificaciones de GitHub : No necesitas hacer nada de esto ahora, pero es útil saberlo. Puedes obtener certificaciones de GitHub para validar tus habilidades. Esto podría aumentar tus posibilidades de conseguir un trabajo en el futuro al demostrar que te sientes seguro trabajando con Git y GitHub.