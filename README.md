<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitación icónica</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <h1>💅 Invitación de amistad icónica 💅</h1>

    <img src="diablo.jpg" alt="El Diablo Viste a la Moda">

    <p>
        Oye, tengo una propuesta demasiado buena para dejarla pasar…  
        <br><br>
        ¿Te animas a ver <strong>El Diablo Viste a la Moda</strong> conmigo? 🎬✨  
        <br><br>
        Prometo drama, moda, risas y comentarios innecesariamente críticos sobre outfits.
    </p>

    <button onclick="aceptarInvitacion()">Sí, vamos 💖</button>
</div>

<script>
function aceptarInvitacion() {
    document.body.innerHTML = `
        <div class="container">
            <h1>Sabía que tenías buen gusto 😌</h1>
            <img src="amigos.jpg" alt="Amistad icónica">
            <p>
                Prepárate para una tarde de amistad, estilo y energía fashionista 💅✨
            </p>
        </div>
    `;
}
</script>

</body>
</html>
