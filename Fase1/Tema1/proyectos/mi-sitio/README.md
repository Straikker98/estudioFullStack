## Versiones del entorno

Editor: VS Code 1.140.0
Git: 2.56.0.windows.2
Terminal: PowerSheel 5.1
Navegador: Google Chrome 155.0.8059.85


## Comandos base utilizados

Comando | Qué hace | Ejemplo real ejecutado |
------- | -------- | ---------------------- |
`pwd` | Muestra la carpeta actual | Lo usé para ver la carpeta donde estaba ubicado y asi poder irme guiando a medida que entraba entre carpetas hasta llegar a la raíz donde iba a crear la carpeta mi-sitio|
`ls` | Lista los archivos de la carpeta | Lo use para ir viendo como quedaban los archivos que iba creando y los archivos ya creados y poderme mover entre carpetas
`cd`| moverse entre carpetas | Lo use para moverme entre carpetas y asi llegar hasta la carpeta destino |
`mkdir`| Crear una carpeta | Cree todo el árbol de carpetas |
`New-Item`| Crear un archvio vacío | Lo usé para crear los archivos vacios como index.html, README.md|
`cp`| Crear copias de un archivo | cree una copia del index.html con el nombre imagen.html|
`mv`| mueve o renombra un archivo | moví el archivo imagen.html a la carpeta img |
`rm`| Elimina un archivo | lo usé para eliminar unas copias de prueba que había creado |
`cat`| Mostrar el contenido en la terminal | Lo usé para ver el contenido que iba escribiendo en el README por medio de VS Code |

Estos fueron los comandos que utilicé para dejar creado todo el arbol con estructuras e iba revisando que iba pasando


Para la revisión en vivo en el DevTools realice los pasos que aparecen en la guía, cambie el estilo del titulo desde elements, verifique que tanto el index como el css/estilo.css dieran el codigo 200, cambié la carpeta css a otro nombre y al recargar el navegador salio en el network (failed)net::ERR_FILE_NOT_FOUND en la columna status y en console salía un error GET que aun no entiendo, volvi a cambiar el nombre de la carpeta usando mv css2 css, recargué la página y ya todo funcionaba con normalidad sin errores en consola y en el network status 200 que indica que la ruta esta bién.

Tambien hice lo de Git, revise el estado y todo estaba bien, hice commit a todo en "Estructura datos", cambié el nombre del index, vi el estado y lo que habia sucedido con git status y luego restauré el index desde los comandos de git.

Todo esto me pareció muy práctico y util para todo mi proceso formativo, aprendi sobre esto y me diverti en el proceso. Gacias Straikker.