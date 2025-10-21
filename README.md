🕵️‍♂️ El Impostor — Juego Web Multijugador Local

El Impostor es un juego web inspirado en dinámicas de deducción social, donde un grupo de jugadores recibe nombres de futbolistas y uno de ellos es designado como el impostor.
El objetivo es descubrir quién miente antes de que sea demasiado tarde ⚽.

🎮 Cómo se juega

Cada jugador recibe el nombre de un futbolista profesional.

Uno de los jugadores recibe el rol de impostor, sin saber el nombre del jugador real.

En cada ronda, los participantes deben decir algo relacionado con su futbolista (características, clubes, nacionalidad, posición, etc.).

Después de las pistas, el grupo vota quién creen que es el impostor.

Si aciertan, ganan los jugadores; si no, gana el impostor.

🧩 Características

Juego totalmente web (no requiere instalación).

Compatible con celular y PC.

Sistema de selección aleatoria de jugadores de fútbol.

Puede usarse en modo local (pasando el dispositivo) o publicarse online.

Código simple en HTML, CSS y JavaScript — ideal para extender o personalizar.

⚙️ Cómo ejecutar el proyecto
🔹 Opción 1 — Local (VS Code)

Cloná este repositorio:

git clone https://github.com/tuUsuario/el-impostor.git
cd el-impostor


Abrí la carpeta en Visual Studio Code.

Instala la extensión Live Server (de Ritwick Dey).

Abrí index.html → clic derecho → Open with Live Server.

Juega desde tu navegador:

http://localhost:5500

🔹 Opción 2 — Online (Vercel o GitHub Pages)

Subí la carpeta del proyecto a Vercel
 o activá GitHub Pages desde la configuración del repositorio.

Compartí la URL pública con tus amigos.

¡Listo para jugar desde cualquier dispositivo!

🧠 Personalización

Podés modificar o agregar tus propias listas de futbolistas en el archivo principal:

const jugadores = "Lionel Messi, Cristiano Ronaldo, Kylian Mbappé, ...";


Si dejás el campo vacío, se usa la lista predeterminada del juego.

📱 Sugerencias

Agregá el juego a la pantalla principal del celular desde el navegador para jugarlo como si fuera una app.

Se puede ampliar con:

Sistema de nombres personalizados

Pistas automáticas

Roles adicionales

Modo en línea con Socket.io

🧑‍💻 Tecnologías usadas

HTML5

CSS3

JavaScript Vanilla

(Opcional) Vercel / GitHub Pages para despliegue

📄 Licencia

Este proyecto es de uso libre para fines educativos y recreativos.
Podés clonarlo, modificarlo o compartirlo con tus amigos libremente.
