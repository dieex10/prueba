<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <section>
        <form action="">
            <label for="nombre">
                <span>Nombre: </span>
                <input type="text" id="nombre" autofocus >
            </label>
            <br>
            <br>
            <label for="micorreo">
                <span>Correo electrónico : </span>
                <input type="email" name="micorreo" id="micorreo">
            </label>
          <br>
          <br>
            <label for="url">
                <span>URL: </span>
                <input type="url" id="url" placeholder="Escribe la URL de tu página web personal">
            </label>
            <br>
            <br>
            <label for="fecha">
                <span>Fecha: </span>
                <input type="date" name="micorreo" id="fecha">
            </label>
            <br>
            <br>
            <label for="Tiempo">
                <span>Tiempo: </span>
                :<input type="time" name="Tiempo" id="Tiempo">
            </label>
            <br>
            <br>
            <label for="Fecha_Hora">
                <span>Fecha y hora: </span>
                :<input type="datetime" name="Fecha_Hora" id="Fecha_Hora">
            </label>
            <br>
            <br>
            <label for="mimes">
                <span>Mes: </span>
                <input type="month"  name="mimes" id="mimes">
            </label>
            <br>
            <br>
            <label for="misemana">
                <span>Semana: </span>
                <input type="week" name="misemana"id="misemana">
            </label>
            <br>
            <br>
            <label for="misnumeros">
                <span>Número(min-10,max 10): </span>
                <input type="range"name="misnumeros" id="misnumeros" min="-10"
                max="10" step="5"> 
            </label>
            <br>
            <br>
            <label for="minumber">
                <span>Teléfono: </span>
                <input type="tel" name="minumber"id="minumber" min="0" max="10" step="3">
            </label>
            <br>
            <br>
            <label for="mibusqueda">
                <span>Término de búsqueda: </span>
                <input type="search" name="mibusqueda" id="mibusqueda">
            </label>
            <br>
            <br>
            <label for="micolor">
                <span>Color favorito: </span>
                <input type="color" name="micolor" id="micolor">
            </label>
            <br>
            <br>
            </label>
            <br>
            <button>Enviar</button>
        </form>
    </section>
</body>
</html>
