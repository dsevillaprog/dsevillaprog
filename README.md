## Hi there 👋

<!--
**dsevillaprog/dsevillaprog** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es-ES">
<head>
    <meta charset="UTF-8">
    <title>𝔻𝕊𝕖𝕧𝕚𝕝𝕝𝕒ℙ𝕣𝕠𝕘 | Página de Presentación</title>
    <meta name="author" content="𝓓𝓢𝓮𝓿𝓲𝓵𝓵𝓪𝓟𝓻𝓸𝓰 © ">
    <meta name="artist" content="ᗪᔕᵉᵛⁱˡˡᵃᑭʳᵒᵍ">
    <meta name="url" content="https://github.com/dsevillaprog">
    <meta name="instrument" content="🄱 🄰 🅂 🄷 + 🄷 🆃 🄼 🅻  & 🄲 🆂 🅂 ">
    <meta name="copyright" content="𝓓𝓢𝓮𝓿𝓲𝓵𝓵𝓪𝓟𝓻𝓸𝓰 © 2025 Todos los Derechos Reservados">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="icon" type="image/x-icon" href="img/cmd.gif">
    <style>
        /* Variables personalizadas */
        :root {
            --color-bg-pri: rgb(82, 65, 100);
            --color-bg-sec: rgb(187, 187, 187);
            --color-bg-sec-hov: rgb(206, 205, 205);
            --color-head: #2c1f32;
            --color-head-txt: rgba(179, 165, 192, 0.936);
            --color-foot: #6a6770;
            --color-link: aliceblue;
            --color-link-hov: rgb(180, 216, 247);
            --color-txt-pri: rgb(218, 209, 226);
            --color-txt-sec: rgb(253, 251, 255);
            --font-1:1rem;
            --font-2:1.2rem;
            --font-3:0.8rem;
            --font-4:0.6rem;
            --border-10:10px;
        }
        /* Reset general */
        * {
            margin: 0;
            padding: 0;
            color: inherit;
            text-decoration: none;
            box-sizing: border-box;
        }
        /* Estilos generales de la web */
        html {
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            font-size: var(--font-1);
        }
        body {
            width: 100vw;
            display: flex;
            flex-direction: column;
            position: absolute;
            align-items: center;
            justify-content: space-around;
            margin: auto;
            color: var(--color-txt-sec);
            background-color: var(--color-bg-pri);
        }
        h1 {
            text-align: center;
            padding: 2%;
            text-shadow: 0 0 60px #e2bcf6b8;
        }
        h2 {
            font-size: 2rem;
            text-align: center;
            color: rgb(195, 182, 203);
        }
        h3 {
            text-align: center;
            margin: 0 auto;
            color: rgb(36, 17, 46);
        }
        h4 {
            font-size: var(--font-2);
            text-align: left;
            margin: 0 0 20px 50px;
            color: rgb(229, 215, 238);
        }
        p {
            text-align: left;
            margin: 0px 0px 20px 70px;
            color: var(--color-txt-pri);
            text-shadow: rgba(72, 42, 102, 0.744);
        }
        a {
            color: var(--color-link);
        }
        a:hover {
            color: var(--color-link-hov);
        }
        /* Estilo de: Cabecera */
        header {
            width: 100%;
            text-align: center;
            align-items: center;
            justify-content: center;
            padding: 3%;
            color: var(--color-head-txt);
            background-color: var(--color-head);
            text-shadow: #9a7cbdb3;
        }
        #nombre {
            color: #aeacaf;
            text-shadow: 0 0 60px #dd98ffcc;
        }
        /* Estilo de: Sobre mi */
        .contenido {
            width: 80vw;
            text-align: center;
            margin: 5% auto;
            padding: 4%;
            background-color: var(--color-bg-sec);
            box-shadow: 0 0 50px rgba(0, 0, 0.1);
            border-radius: var(--border-10);
            transition: transform .6s ease-in-out, border-radius .6s, background-color .6s, box-shadow .6s;
        }
        .contenido:hover {
            background-color: var(--color-bg-sec-hov);
            box-shadow: 0 0 90px rgb(39, 39, 39);
            border-radius: 30px;
        }
        .sobremi {
            font-size: 1.1rem;
            line-height: 2rem;
            margin: auto;
            text-align: center;
            color: #1d1753;
        }
        /* Estilo de: Proyectos */
        .bg-proyectos {
            width: 90%;
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            margin: 3% 0;
            padding: 0 5%;
            background-color: rgb(69, 51, 82);
            border-radius: var(--border-10);
            transition: transform .7s ease-in-out, border-radius .4s, background-color .5s, box-shadow .7s;
        }
        .bg-proyectos:hover {
            background-color: rgb(56, 41, 66);
            box-shadow: 0 0 50px rgba(54, 1, 78, 0.719);
            border-radius: 30px;
        }
        #mis_proyectos p h2 {
            width: 30%;
            font-family: 'Courier New', Courier, monospace;
            font-size: 25px;
            display: flex;
            padding: 5%;
            margin-right: 3%;
            color: #aeacaf;
            border-color: #252128;
            text-shadow: rgba(72, 42, 102, 0.744);
            border-radius: var(--border-10);
        }
        .proyectos {
            display: flex;
            flex-direction: column;
            padding: 5%;
            color: rgb(241, 233, 247);
            text-shadow: #aeacaf;
        }
        ol li {
            text-align: left;
            margin: 0px 0px 20px 70px;
            color: rgb(218, 209, 226);
            text-shadow: rgba(72, 42, 102, 0.744);
        }
        /* Estilo de: Aficiones */
        section {
            width: 15vw;
            min-width: 15vw;
            height: auto;
            line-height: 1.6rem;
            position: sticky;
            left: 5px;
            bottom: 3%;
            margin-left: 80%;
            margin-right: 3%;
            margin-bottom: 5%;
            margin-top: 8%;
            padding: 1%;
            color: #2b0d3f1a;
            background-color: #c9b0d310;
            box-shadow: 2px 2px 5px rgba(110, 96, 114, 0.144);
            border-radius: var(--border-10);
            transition: transform .4s ease-in, color .3s, background-color .3s, box-shadow .4s, border-radius .4s;
        }
        section:hover {
            color: #271d27de;
            background-color: #b385c5e1;
            box-shadow: 1px 1px 25px rgba(148, 129, 153, 0.706);
            border-radius: 15px;
        }
        section h3 {
            font-size: var(--font-1);
        }
        section p {
            font-size: var(--font-2);
            line-height: 1.6rem;
            margin: 1% 1% 1% 20%;
            color: #271d27de;
        }
        /* Estilo de: Imágenes */
        .img-logo {
            width: auto;
            max-height: 5vh;
            margin: 1%;
            border-radius: 6px;
        }
        .img-sed {
            height: 30vh;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: top;
            margin: 20px auto;
            border-radius: 6px;
        }
        .img-div {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: top;
        }
        .img-proyect {
            height: 30vh;
            width: auto;
            margin: 20px auto;
            border-radius: 6px;
        }
        .img-proyect-width {
            height: 50vh;
            width: auto;
            margin: 20px 40px 150px 150px;
            border-radius: 6px;
        }
        /* Estilo de: Margen y Transiciones */
        .margen {
            margin: 0 0 180px 0;
        }
        .scale {
            transition: transform .4s ease-in-out;
        }
        .scale:hover {
            transform: scale(1.8);
        }
        .scale-1 {
            transition: transform .4s ease-in-out;
        }
        .scale-1:hover {
            transform: scale(2);
        }
        .scale-1-L {
            transition: transform .4s ease-in-out;
        }
        .scale-1-L:hover {
            transform: scale(2) translateX(-100px);
        }
        .scale-L {
            transition: transform .4s ease-in-out;
        }
        .scale-L:hover {
            transform: scale(1.8) translateX(-100px);
        }
        .scale-R {
            transition: transform .4s ease-in-out;
        }
        .scale-R:hover {
            transform: scale(1.8) translateX(100px);
        }
        /* Estilo de: Pié de Página */
        footer {
            width: 100%;
            height: 12%;
            font-size: var(--font-2);
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 8px;
            color: rgb(69, 67, 76);
            background-color: var(--color-foot);
            box-shadow: 0 0 50px rgba(95, 60, 104, 0.706);
            transition: transform .5s ease-in-out, background-color .5s, box-shadow .3s;
        }
        footer:hover {
            transform: scale(1.1);
            background-color: rgba(67, 66, 72, 0.893);
            box-shadow: 0 0 70px rgba(114, 76, 123, 0.706);
        }
        footer .logos .social a img {
            width: 50px;
            height: 50px;
            margin-top: 10px;
            flex: 1;
        }
        footer p {
            color: #9fc4c4;
            flex: 1;
        }
        footer .social {
            width: 50px;
            height: 30px;
            flex: 1;
        }
        footer .social:hover {
            color: #b0d2d2;
            text-shadow: 2px 1px 4px rgba(23, 153, 214, 0.616);
        }
        footer .pie_pag a:hover {
            color: #b0d2d2;
            text-shadow: 2px 1px 4px rgba(23, 153, 214, 0.616);
        }
        .git {
            cursor: progress;
        }
        /* Estilo Responsive a: 1785px */
        @media(max-width:1785px) {
        .sobremi {
            font-size: var(--font-1);
        }
        .img-sed {
            height: 25vh;
            margin: 0 auto;
        }
        .img-proyect {
            height: 25vh;
        }
        .img-proyect-width {
            height: 40vh;
        }
        section h3 {
            font-size: var(--font-1);
        }
        section p {
            font-size: var(--font-1);
            margin: 1% 1% 1% 20%;
        }
        }
        /* Estilo Responsive a: 1200px */
        @media(max-width:1200px) {
        header {
            font-size: var(--font-2);
        }
        #nombre {
            font-size: 1.8rem;
        }
        .img-sed {
            height: 25vh;
            margin: 10px auto;
        }
        .img-proyect {
            height: 25vh;
            margin: 10px auto;
        }
        .img-proyect-width {
            height: 35vh;
            margin: 20px auto;
            border-radius: 6px;
        }
        .scale:hover {
            transform: scale(1.6);
        }
        .scale-L:hover {
            transform: scale(1.6);
        }
        .scale-R:hover {
            transform: scale(1.6);
        }
        section h3 {
            font-size: var(--font-2);
        }
        section p {
            font-size: var(--font-2);
            margin: 1% 1% 1% 15%;
        }
        section {
            margin-left: 92%;
        }
        footer {
            font-size: var(--font-2);
            display: flex;
            flex-direction: column;
            align-items: center;
            align-content: center;
            justify-content: space-around;
            padding: 2%;
        }
        footer .logos .social a img {
            width: 40px;
            height: 40px;
        }
        /* Estilo Responsive a: 768px */
        @media(max-width:768px) {
        .img-sed {
            height: 25vh;
        }
        .img-proyect {
            height: 25vh;
        }
        .img-proyect-width {
            height: 35vh;
        }
        .scale:hover {
            transform: scale(1.2);
        }
        .scale-L:hover {
            transform: scale(1.2);
        }
        .scale-R:hover {
            transform: scale(1.2);
        }
        section h3 {
            font-size: var(--font-3);
        }
        section p {
            font-size: var(--font-3);
        }
        section {
            min-width: 20vw;
            margin-left: 90%;
        }
        }
        </style>
</head>

<body>
    <header id="arriba">
        <h1>Página de Presentación</h1>
        <h2 id="nombre"><a href="#contacto">𝔻𝕊𝕖𝕧𝕚𝕝𝕝𝕒ℙ𝕣𝕠𝕘</a></h2>
    </header>
    <div class="contenido ">
        <h2 id="SobreMi" class="sobremi">Sobre mi:</h2>
        <br>
        <p class="sobremi">Programador autodidacta; comencé a programar con scripts en Batch y Visual Basic muy simples
            para Windows, de ahí pasé a proyectos para Arduino, y desde hace unos años realizo programas y scripts en
            Bash para Linux, actualmente estoy aprendiendo Python.<br>Decidí instalar Linux porque siempre tuve
            curiosidad por probar un sistema operativo de
            código abierto, y, ahora que sabía algo de programación, podía crear y personalizar herramientas a mi gusto.
            Seguí varios libros de programación en Bash, realicé muchos de los ejercicios, pero siempre me atascaba en
            algún punto que no comprendía bien y acababa por buscar la información por otros medios. Fué así como
            descubrí y me
            empezó a interesar el campo de la Ciberseguridad, ya que el mejor contenido que encontré para programar en
            Bash y aprender sobre Linux estaba enfocado al Hacking Ético y a la Ciberseguridad.</p>
        <p class="sobremi">Encontré una web en la que superando retos cada vez más complejos, aprendí rápidamente a usar
            muchos comandos de terminal y técnicas de
            Ciberseguridad. Conforme mejoraba mis habilidades, iba descubriendo las infinitas posibilidades y la
            potencia de unas pocas líneas de código.</p>
        <!-- <p class="sobremi">Me gustaría formarme en Ciberseguridad ya que es un campo que me fascina y me parece el mejor
            lugar para desarrollar mis conocimientos de Linux y programación.</p> -->
    </div>
    <div class="bg-proyectos">
        <div id="mis_proyectos">
            <h2 class="proyectos">Aprendizaje Online</h2>
            <!-- OverTheWire - Bandit -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Linux">
                <h4><a href="https://overthewire.org/wargames/bandit/" target="_blank"><img class="img-logo"
                            src="../../../CURSO-CSS/blob/main/Ejercicio2/img/otw.png" alt="OverTheWire">Bandit</a></h4>
                <p> - CTF escalable en el que se aprenden el uso de comandos básicos de Linux como:</p>
                <p> ls, cd, cat, file, man, du, find, grep, sort, uniq, base64, tr, tar, gzip, bzip2, etc.</p>
                <p> - A medida que avanzamos por los niveles, comienzan a verse comandos más complejos de redes y
                    Ciberseguridad como:</p>
                <p> ssh, telnet, nc, ncat, socat, openssl, nmap, netstat, ss, cron, chmod, git, etc.</p>
                <br>
                <p> - La primera vez que lo completé, en la mayoría de niveles necesité seguir Writeups para conseguir
                    las Flag,</p>
                <p> un par de años más tarde, y tras hacer varios laboratorios de <a
                        href="https://www.hackthebox.com/">HackTheBox</a>, conseguí llegar al nivel 22 sin ayuda.</p>
                <div class="img-div">
                    <img class="scale-1 img-proyect-width" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/bandit.png" alt="overthewire-bandit">
                </div>
            </div>
            <br>
            <!-- OverTheWire - Natas -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Linux">
                <h4><a href="https://overthewire.org/wargames/natas/" target="_blank"><img class="img-logo"
                            src="../../../CURSO-CSS/blob/main/Ejercicio2/img/otw.png" alt="OverTheWire">Natas</a></h4>
                <p> - CTF escalable en el que se aprenden técnicas de Hacking Web:</p>
                <p> - Lo intenté sin ayuda y conseguí llegar al nivel 4, finalmente tuve que buscar un Writeup y
                    descubrí Burpsuite.</p>
                <p> - Estuve un tiempo viendo tutoriales de Burpsuite y Caido, y lo aparqué para comenzar este curso de
                    Elaboración de Páginas Web.</p>
                <br>
                <div class="img-div">
                    <img class="scale-1 img-proyect-width" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/natas.png" alt="overthewire-natas">
                </div>
            </div>
            <br>
            <!-- HackTheBox -->
            <div class="margen">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Linux">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/win2.png" alt="Windows">
                <h4><a href="https://www.hackthebox.com/" target="_blank"><img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/htb.png"
                            alt="htb"></a></h4>
                <p> - Plataforma online de Ciberseguridad y Hacking Ético</p>
                <p> - Laboratorios de pruebas y retos simulando entornos reales.</p>
                <p> - He realizado todas las máquinas gratuitas de nivel fácil, y varios retos Sherlock, estoy empezando
                    el nivel medio.</p>
                <br>
                <div class="img-div">
                    <img class="img-sed scale-1" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/htb_machines.png" alt="htb machines">
                    <img class="img-sed scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/htb_streak.png" alt="htb streak">
                </div>
            </div>
            <hr>
            <h2 class="proyectos">Proyectos Personales</h2>
            <!-- castDrop.py -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/castDrop" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/python.png" alt="Python" title="castDrop.py"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/castDrop" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Termux" title="Termux"></a>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/under_construction.png" alt="under_construction">
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/castDrop" target="_blank">castDrop.py</a>
                </h4>
                <p> - Aplicación de control para dispositivos ChromeCast (Linux/Termux).</p>
                <p> - Descubrimiento de dispositivos en red.</p>
                <p> - Detecta múltiples protocolos: Google Cast, AirPlay, Spotify, Sonos, DLNA, ...</p>
                <p> - Obtiene información multimedia: Aplicación, Estado, Volumen, Título, Canal, Duración, URL, ...</p>
                <p> - Opciones de control multimedia: Pausar/Reanudar, Forzar Cierre, Subir/Bajar Volumen,
                    Mutear/Desmutear, Inyectar Contenido, ...</p>
                <p> - Opciones de control Bluetooth (*en pruebas)</p>
                <br>
                <div class="img-div">
                    <img class="img-proyect scale-1" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/castDrop.png" alt="castDrop.py">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/castDrop-1.png" alt="castDrop.py">
                </div>
            </div>
            <br>
            <!-- cve_monitor.py -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/cve_monitor" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/python.png" alt="Python" title="cve_monitor.py"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/cve_monitor" target="_blank">cve_monitor.py /
                        cve_monitor_LIST.py</a></h4>
                <p> - Aplicación/bot de consulta y filtrado de alertas de seguridad (CVE).</p>
                <p> - Puede funcionar integrando un bot de Telegram o por consola.</p>
                <p>⠀⠀ ・Busca *linux en los últimos CVE modificados en nist.gov (cve_monitor_LIST.py: busca iterando
                    sobre listas definidas)</p>
                <p>⠀⠀ ・Busca si disponen de parche y/o exploit</p>
                <p>⠀⠀ ・Comprueba que no estén ya registrados en la base de datos local</p>
                <p>⠀⠀ ・Muestra métricas del CVE y envía la alerta al ID de Telegram si está configurado</p>
                <p>⠀⠀ ・Guarda el CVE en la base de datos local</p>
                <br>
                <div class="img-div">
                    <img class="img-proyect scale-1" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cve_monitor.png" alt="cve_monitor.py">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cve_monitor-t.png" alt="cve_monitor_bot">
                </div>
            </div>
            <br>
            <!-- Name_cleaner.sh / .py -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Name_cleaner.sh" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Name_cleaner.sh" title="Name_cleaner.sh"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Name_cleaner.py" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/python.png" alt="Python" title="Name_cleaner.py"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/Name_cleaner.sh"
                        target="_blank">Name_cleaner.sh</a><a
                        href="https://github.com/dsevillaprog/Shell-Scripts/Name_cleaner.py" target="_blank"> / .py</a>
                </h4>
                <p> - Borra / Renombra / numera por tipos los archivos de una carpeta.</p>
                <p> - Edita los metadatos si son compatibles con Exiftool.</p>
                <p> - Renombra todos los archivos de una carpeta:
                <p>⠀⠀ ・Borrando o cambiando una parte en común (www.descargas.com, Album-Hits 2025)</p>
                <p>⠀⠀ ・Agregando un término al final (--Estilo --Tipo)</p>
                <p>⠀⠀ ・Numerando al principio del nombre, eliminando o no el nombre</p>
                <p>⠀⠀ ・Eliminando la numeración del principio</p>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Name_cleaner.png" alt="Name_cleaner help">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Name_cleaner.gif" alt="Name_cleaner">
                </div>
            </div>
            <br>
            <!-- logFilter.sh -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/logFilter" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="logFilter.sh" title="logFilter.sh"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/logFilter" target="_blank">logFilter.sh</a>
                </h4>
                <p> - Extrae y procesa direcciones IPv4 del archivo Apache/access.log o de archivo de IPv4 únicas.</p>
                <p>⠀⠀ ・Filtra las que contienen peticiones maliciosas y por país</p>
                <p>⠀⠀ ・Las consulta con herramientas online: curl, dig, host, nslookup, ip-api, rdap, VirusTotal,
                    ...</p>
                <p>⠀⠀ ・Las consulta en listas de reputación de amenazas (DNSBL): Abuse, Spamhaus, Barracuda, DroneBL,
                    Sorbs</p>
                <p>⠀⠀ ・Las añade a listas de baneo en función de los resultados</p>
                <div class="img-div">
                    <img class="img-proyect scale-1" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/logFilter.png" alt="logFilter.sh">
                    <img class="img-proyect scale-1-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/logFilter-1.png" alt="logFilter.sh">
                </div>
            </div>
            <br>
            <!-- curl_dump.sh -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/curl_dump" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="curl_dump.sh" title="curl_dump.sh"></a>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/under_construction.png" alt="under_construction">
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/curl_dump" target="_blank">curl_dump.sh</a>
                </h4>
                <p> - Descarga y extrae direcciones URL del código de una URL o de una lista.</p>
                <p>⠀⠀ ・Descarga con curl las URL's</p>
                <p>⠀⠀ ・Extrae las URL's del código de cada URL</p>
                <p>⠀⠀ ・Vuelve a realizar el proceso</p>
                <br>
                <!-- <div class="img-div"> -->
                <!--     <img class="img-proyect scale-1" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/curl_dump.png" alt="curl_dump.sh"> -->
                <!--     <img class="img-proyect scale-1-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/curl_dump-1.png" alt="curl_dump.sh"> -->
                <!-- </div> -->
            </div>
            <br>
            <!-- Media_converter.sh / .py -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Media_converter.sh" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Media_converter.sh" title="Media_converter.sh"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Media_converter.py" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/python.png" alt="Python" title="Media_converter.py"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/Media_converter.sh"
                        target="_blank">Media_converter.sh</a><a
                        href="https://github.com/dsevillaprog/Shell-Scripts/Media_converter.py" target="_blank"> /
                        .py</a></h4>
                <p> - Cambia el formato de archivos multimedia con ffmpeg.</p>
                <p> - Convierte uno o todos los formatos de los archivos de la ruta de trabajo al formato elegido en una
                    nueva carpeta.</p>
                <p> - Convierte a formatos de codecs soportados por ffmpeg (aac, ac3, dts, flac, mp3, mpeg4, webp, ...).
                </p>
                <br>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Media_converter00.png" alt="Media_converter1">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Media_converter04.png" alt="Media_converter2">
                </div>
            </div>
            <br>
            <!-- DShtb.sh -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/DShtb" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="DShtb.sh" title="DShtb.sh"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/DShtb" target="_blank">DShtb.sh</a></h4>
                <p> - Aplicación con múltiples herramientas de análisis y auditoría.</p>
                <p> - Agiliza el reconocimiento y explotación de máquinas en HackTheBox, VulnHub, etc.</p>
                <p> - Crea un objetivo, filtra y guarda los datos obtenidos, ejecuta herramientas y genera reportes.</p>
                <p> - Integra: nmap, dirb, ffuf, gobuster, nikto, nuclei, wpscan, sqlmap, smbclient, cewl, crunch,
                    msfconsole, ...</p>
                <div class="img-div">
                    <img class="img-proyect scale-1" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/DShtb.png" alt="DShtb.sh">
                    <img class="img-proyect scale-1-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/DShtb_mx.png" alt="DShtb.sh mx">
                </div>
            </div>
            <br>
            <!-- img_convert.sh -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="img_convert.sh">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/under_construction.png" alt="under_construction">
                <h4>img_convert.sh</h4>
                <p> - Recorta, redimensiona, cambia de formato, y aplica múltiples filtros y efectos a las imágenes de
                    una carpeta.</p>
                <p> - Convierte Imágenes con ImageMagick.</p>
                <p> - Modifica metadatos con Exiftool.</p>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/img_convert.png" alt="img_convert1">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/img_convert2.png" alt="img_convert2">
                </div>
            </div>
            <br>
            <!-- Sed_loop-R.sh -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Sed_loop-R" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Sed_lopp-R.sh" title="Sed_loop-R.sh"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/Sed_loop-R" target="_blank">Sed_loop-R.sh</a>
                </h4>
                <p> - Función de "Buscar y Reemplazar" recursiva para todos los archivos de una o varias extensiones
                    dentro de la ruta de trabajo.</p>
                <p> - Elije una extensión o modifica recursivamente todo un proyecto web (.html, .css y .js).</p>
                <p>⠀⠀ ・Ejemplo, añadir la clase "mi-clase" a todas las etiquetas ul sin atributos:</p>
                <p>⠀⠀ ⠀ Buscar: <strong>&#60;ul></strong></p>
                <p>⠀⠀ ⠀ Cambiar:<strong>&#60;ul class="mi-clase"></strong></p>
                <p>⠀⠀ ・Ejemplo:</p>
                <p>⠀⠀ ⠀ Cambiar lang="es-ES" por lang="en"</p>
                <p>⠀⠀ ⠀ Cambiar dsevillaprog por RandomUser</p>
                <div class="img-div">
                    <img class="img-sed scale-R" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Sed_loop-R1.png" alt="Sed_lopp-R1">
                    <img class="img-sed scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Sed_loop-R2.png" alt="Sed_lopp-R2">
                    <img class="img-sed scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Sed_loop-R3.png" alt="Sed_lopp-R3">
                </div>
                <br>
                <div class="img-div">
                    <img class="img-sed scale-R" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Sed_loop-R4.png" alt="Sed_lopp-R4">
                    <img class="img-sed scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Sed_loop-R5.png" alt="Sed_lopp-R5">
                    <img class="img-sed scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Sed_loop-R6.png" alt="Sed_lopp-R6">
                </div>
            </div>
            <br>
            <!-- Roli-Sounds .sh / .html -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Roli-Sounds" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Roli-Sounds.sh" title="Roli-Sounds.sh"></a>
                <a href="../../Curso-Formularios/Ejercicio6/index.html" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/logo-html.png" alt="Roli-Sounds.html" title="Roli-Sounds.html"></a>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/under_construction.png" alt="under_construction">
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/Roli-Sounds"
                        target="_blank">Roli-Sounds.sh</a><a href="../../Curso-Formularios/Ejercicio6/index.html"
                        target="_blank"> / .html</a></h4>
                <p> - Base de datos personalizada de sonidos del teclado Roland GO:Keys.</p>
                <p> - Clasifica y busca sonidos por: Tipo, Estilo, Cualidad, Efecto, Favorito, etc.</p>
                <p> - Busca sonidos por una o varias cualidades: EP, delay:h, sustain:l, phaser, bass-fx, Soul, Rock,
                    ...</p>
                <p> - Crea/busca/modifica listas de estilos/cualidades.</p>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Roli-Sounds.gif" alt="Roli-Sounds">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Roli-Sounds.png" alt="Roli-Sounds.html">
                </div>
            </div>
            <br>
            <!-- VR-D2Pro Circuit Bending -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/logo-circuit.png" alt="Circuit Bending">
                <h4>Eachine VR-D2Pro Circuit Bending</h4>
                <p> - Modificación de la electrónica de las gafas de FPV Eachine VR-D2Pro.</p>
                <p> - Se le añaden conectores de entrada de video RCA y salida de audio Jack 3.5.</p>
                <br>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/vrd2pro.png" alt="VR-D2Pro Circuit Bending">
                </div>
            </div>
            <br>
            <!-- Casio SA-1 Circuit Bending -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/logo-circuit.png" alt="Circuit Bending">
                <h4>Casio SA-1 Circuit Bending </h4>
                <p> - Modificación de la electrónica del teclado Casio SA-1.</p>
                <p> - Se le añaden switch de octavas y 3 niveles de reverb base con modulación mediante LDR.</p>
                <br>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/sa-1-in.jpg" alt="Casio SA-1">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/sa-1.jpg" alt="Casio SA-1 Circuit Bending">
                </div>
            </div>
            <!-- Alarma GSM - Arduino -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/arduino-logo.jpg" alt="Alarma_GSM.ino">
                <h4>Alarma_GSM.ino</h4>
                <p> - Alarma realizada en Arduino con comunicación por módulo GSM.</p>
                <p> - Permite conectar multitud de sensores y actuadores para su monitorización y control, accesos,
                    presencia, niveles, tensiones, GPS, relés, contactores, ...</p>
                <p> - Avisa mediante llamadas/sms a una lista números en el orden definido.</p>
                <p> - Monitoriza/Activa mediante sms y/o llamadas los sensores/actuadores conectados.</p>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/arduino-uno-top.jpg" alt="Arduino Uno">
                    <img class="img-proyect scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/arduino-gsm.jpg" alt="Módulo SIM900">
                </div>
            </div>
            <br>
            <!-- Autotube.sh -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/Autotube" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="Autotube.sh" title="Autotube.sh"></a>
                <h4><a href="https://github.com/dsevillaprog/Shell-Scripts/Autotube" target="_blank">Autotube.sh</a>
                </h4>
                <p> - Reproduce listas de Youtube y Spotify en bucle cambiando de IP.</p>
                <p> - Conecta con un servidor VPN e inicia un bucle de reproducción:</p>
                <p>⠀⠀ ・Reproduce con firefox los links de una o varias listas</p>
                <p>⠀⠀ ・Hace una pausa personalizada para registrar la visualización</p>
                <p>⠀⠀ ・Cambia de servidor VPN para renovar la IP</p>
                <br>
                <div class="img-div">
                    <img class="img-proyect scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/Autotube.png" alt="Autotube.sh">
                </div>
            </div>
            <br>
            <!-- USB PorCotilla -->
            <div>
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script">
                <img class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/win2.png" alt="porcotilla.cmd">
                <h4>USB PorCotilla</h4>
                <p> - Conjunto de scripts (.cmd, .bat y .vbs), camuflados en una memoria USB con una "Carpeta Cebo" que
                    los inicia al intentar abrirla.</p>
                <p>⠀ » Una vez iniciados:</p>
                <p>⠀⠀ ・Crea scripts y copia un archivo .mp3 en el sistema cotilla, estos serán ejecutados al reiniciar
                    el equipo</p>
                <p>⠀⠀ ・Crea claves de registro de Windows llamadas: Windows_Defender.cmd y Windows_System.cmd</p>
                <p>⠀⠀ ・Listan en un .log el contenido de las carpetas principales del sistema cotilla</p>
                <p>⠀⠀ ・Obtiene información del sistema cotilla mediante: SYSTEMINFO, GETMAC, IPCONFIG y NETSH</p>
                <p>⠀⠀ ・Copia al USB el contenido de las carpetas: Escritorio, Descargas, Mis Documentos y Música</p>
                <p>⠀* El usuario del USB Cotilla verá un error al intentar extraer el dispositivo ya que se encuentra
                    ocupado.</p>
                <br>
                <p>⠀ » Al reiniciar el sistema:</p>
                <p>⠀⠀ ・La pantalla se vuelve azul</p>
                <p>⠀⠀ ・Se ejecuta un script simulando un borrado de disco y la instalación de un sistema virtual</p>
                <p>⠀⠀ ・Se ejecuta otro script reproduciendo el archivo .mp3 y mostrando un mensaje de aviso</p>
                <p>⠀⠀ ・El usuario cotilla sólo podrá detener el proceso mediante el administrador de tareas</p>
                <p>⠀⠀ ・El proceso persistirá en cada reinicio hasta que el usuario cotilla elimine las claves de
                    registro creadas</p>
                <br>
                <div class="img-div margen">
                    <img class="img-sed scale-R" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/porcotilla-1.png" alt="porcotilla1">
                    <img class="img-sed scale" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/porcotilla-2.png" alt="porcotilla2">
                    <img class="img-sed scale-L" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/porcotilla-3.png" alt="porcotilla3">
                </div>
            </div>
            <br>
            <!-- BUSCADORES-WEB -->
            <div>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/" target="_blank"><img class="img-logo"
                        src="../../../CURSO-CSS/blob/main/Ejercicio2/img/cmd.png" alt="Script" title="Shell-Scripts"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/BUSCADORES-WEB.bat" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/win2.png" alt="BUSCADORES-WEB.bat" title="BUSCADORES-WEB.bat"></a>
                <a href="https://github.com/dsevillaprog/Shell-Scripts/BUSCADORES-WEB.sh" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/gnu.png" alt="BUSCADORES-WEB.sh" title="BUSCADORES-WEB.sh"></a>
                <a href="../../Curso-Formularios/buscadores-web/BUSCADORES-WEB.html" target="_blank"><img
                        class="img-logo" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/logo-html.png" alt="HTML" title="BUSCADORES-WEB.html"></a>
                <h4><a href="../../Curso-Formularios/buscadores-web/BUSCADORES-WEB.html"
                        target="_blank">Buscadores-web</a><a
                        href="https://github.com/dsevillaprog/Shell-Scripts/BUSCADORES-WEB.bat" target="_blank">
                        (.bat,</a><a href="https://github.com/dsevillaprog/Shell-Scripts/BUSCADORES-WEB.sh"
                        target="_blank"> .sh,</a><a href="../../Curso-Formularios/buscadores-web/BUSCADORES-WEB.html"
                        target="_blank"> .html)</a></h4>
                <p> - Herramienta con múltiples buscadores, páginas web y recursos.</p>
                <p> - Busca un término por categorías, en una o en todas las opciones.</p>
                <p> - Cambia de IP mediante VPN para evitar bloqueos (.sh).</p>
                <br>
                <div class="img-div">
                    <img class="scale img-proyect-width" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/BUSCADORES-WEB.png" alt="BUSCADORES-WEB.sh">
                    <img class="scale-L img-proyect-width" src="../../../CURSO-CSS/blob/main/Ejercicio2/img/BUSCADORES-WEB_html.png" alt="BUSCADORES-WEB.html">
                </div>
            </div>
            <br>
            <section>
                <h3>AFICIONES</h3><br>
                <p>Programación</p>
                <p>Ciberseguridad</p>
                <p>Electrónica</p>
                <p>Arduino</p>
                <p>Drones FPV</p>
                <p>Edición de música</p>
            </section>
        </div>
    </div>
    <footer>
        <div class="logos">
            <div class="social">
                <!-- Repositorios con ejercicios y ejemplos de los cursos de HTML, CSS, FORMULARIOS, ... -->
                <a class="git" target="_blank" href="https://github.com/dsevillaprog"><img src="../../../CURSO-CSS/blob/main/Ejercicio2/img/git-blk.png"
                        alt=""></a>
            </div>
            <p id="contacto" class="pie_pag"><a target="_blank"
                    href="https://github.com/dsevillaprog">𝔻𝕊𝕖𝕧𝕚𝕝𝕝𝕒ℙ𝕣𝕠𝕘
                    ©</a><strong>&MediumSpace;2025&MediumSpace;</strong> Todos los derechos reservados <a
                    class="icon-up" href="#arriba">⌂</a></p>
        </div>
    </footer>
</body>
</html>
