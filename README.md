<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Web</title>
    <style>
        body {
            margin: 0;
            font-family: sans-serif;
            background-image: url("descarga.jpeg"); /* Reemplaza con la URL de tu imagen de fondo */
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8); /* Fondo blanco semi-transparente */
            border-radius: 5px;
        }

        header {
            display: flex;
            align-items: center;
            padding: 20px 0;
        }

        img.logo {
            height: 50px;
        }

        button {
            padding: 10px 20px;
            background-color: #00cc00; /* Verde */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em; /* Tamaño de fuente por defecto */
            width: 100%; /* El botón ocupará el 100% del ancho disponible */
            box-sizing: border-box; /* Incluye el relleno y la frontera en el ancho */
        }

        main {
            margin-bottom: 20px;
        }

        section {
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="images.png" alt="Logo del sitio" class="logo">
        </header>
        <main>
            <h2>Bienvenido a mi sitio web</h2>
            <p>Aquí encontrarás información sobre mis proyectos y habilidades.</p>
            <p>Haz clic en el botón para ver un ejemplo de mi trabajo:</p>
            <button onclick="window.open('https:https://youtu.be/sLTNgxxSBR4?si=5BHfUdcNhzWXPSsf')">Reproducir Video</button>
        </main>
        <section>
            <h3>Sobre mí</h3>
            <p>Soy un desarrollador web con experiencia en [desarrollo de sistemas web]. Me apasiona crear sitios web y aplicaciones web que sean fáciles de usar y atractivos.</p>
        </section>
        <section>
            <h3>Mis proyectos</h3>
            <p>He trabajado en varios proyectos, incluyendo:</p>
            <ul>
                <li>Proyecto 1: [pagina web de materiales moreno]</li>
                <li>Proyecto 2: [pagina web de cementera cuatemoch]</li>
                <li>Proyecto 3: [pagina de bellas artes]</li>
            </ul>
        </section>
        <footer>
            <p>Nombre del curso: Desarrollo de sistemas Web</p> 
            <p>Nombre completo: Ruben Lomeli Alcaraz</p>
            <p>Código: 219858081</p>
            <p>Correo de contacto: rubenlomeli70@gmail.com</p>
        </footer>
    </div>
</body>
</html>
