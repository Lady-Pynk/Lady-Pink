[index.html](https://github.com/user-attachments/files/22688755/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lady Pink</title>
    <style>
        body {
            background-color: #fce4ec; /* Color del logo */
            font-family: Arial, sans-serif;
            color: #333;
            text-align: center;
        }
        header {
            padding: 20px;
        }
        img {
            max-width: 150px;
        }
        h1 {
            color: #e91e63;
        }
        .form-section, .gallery-section {
            padding: 20px;
            margin: 20px auto;
            max-width: 600px;
            background: white;
            border-radius: 10px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #e91e63;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .gallery-section img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Logo de Lady Pink">
    <h1>Lady Pink Estética</h1>
</header>

<section class="form-section">
    <h2>Reserva tu Cita</h2>
    <form action="https://formspree.io/f/moqbkwgv" method="POST">
        <input type="text" name="name" placeholder="Tu Nombre" required>
        <input type="email" name="_replyto" placeholder="Tu Email" required>
        <input type="text" name="date" placeholder="Fecha Deseada (DD/MM/AAAA)" required>
        <textarea name="message" placeholder="Comentarios" required></textarea>
        <button type="submit">Enviar</button>
    </form>
</section><img width="500" height="500" alt="1" src="https://github.com/user-attachments/assets/526f401b-6dc5-4e76-af69-1828b5733131" />


<section class="gallery-section">
    <h2>Galería de Fotos</h2>
    <img src="foto1.jpg" alt="Trabajo realizado">
    <img src="foto2.jpg" alt="Trabajo realizado">
    <!-- Puedes añadir más imágenes aquí -->
</section>

</body>
</html>
