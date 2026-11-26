
# Multimedial
Ejercicio N°1: semana 1
```<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```
 Unidad 1: Hipervinculo
```Mi primera pagina.html
<!DOCTYPE html>
<html lang="es"> 
<head> 
<meta charset="UTF-8">
<title></title>Multimedial</title>
</head>
<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>
```
```Mi segunda primera html
<!DOCTYPE html>
<html>
<head>
<title>Página 2</title>
</head>

<body>

<h1>Esta es la segunda página</h1>

<a href="pagina1.html" target="_blank"> Volver a la página principal</a>

<!--<a href="https://www.wikipedia.org" target="_blank">Ir a Wikipedia</a>-->

</body>
</html>
```
```Index.html
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: #FCF78B;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: courier, sans-serif;
  /* Define la tipografía del texto */

  font-size: 40px;
  /* Define el tamaño grande del texto */


}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

Hola!
<!-- Texto que aparece en el centro de la pantalla -->


<h1>pecolia</h1>

<img src="img/20260207_151818.jpg" alt=onigiris width="170">



</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```
```Obras.html
<!DOCTYPE html>
<html>
<head>
<title>Obra</title>
  <style>
        /* Estilo general del cuerpo */
        body {
            font-family: courier, sans-serif;
             background-color: #FCF78B;
           
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h1 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }

        .boton { /* Define una clase llamada "boton" */
  background-color: FFFF80; /* Color de fondo del botón */
  color: black; /* Color del texto */
  padding: 50px; /* Espacio interno (arriba, abajo, izquierda, derecha) */
  width: 150px; /* Ancho fijo del botón */
  text-align: center; /* Centra el texto horizontalmente */
  transition: 0.3s; /* Hace que los cambios (como color) sean suaves en 0.3 segundos */
}

.boton:hover { /* Se activa cuando el mouse pasa sobre el elemento */
  background-color: FFFFAD; /* Cambia el color de fondo al pasar el mouse */
}
    </style>
</head>

<body>

       <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/viejas.jpg" alt="Descripción de la imagen" width="30"> 
            <h1>Viejitas diacharacheras</h1>
            
               <p>Algrafia. Litógrafia en aluminio. 2025</p> 
               <p>Un par de señoras</p>

            
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/Papa, tengo frio.jpg" alt="Descripción de la imagen" width="300">
            <h2>Papá, tengo frio</h2>
            <p>
              <p> Algrafia. Litófrafia en aluminio. 2025 <p></p>
               <p></p>Le dije a mi papá que tenia frio, y sin dudarlo, me trajo una manta.<p></p>
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/utero.jpg" alt="Descripción de la imagen">
            <h2>S/T</h2>
            <p>
                <p>Lapiz mina y acrílico sobre papel recortado. 2025</p>
                <p>En el utero de mi madre.</p>
            </p>
        </div>

    </div>








<a href="index.html" class="boton">Inicio</a><br> <br>
<a href="contacto.html" class="boton">Contacto</a>

</body>
</html>
```
```Contacto.html
<!DOCTYPE html>
<html>
<head>
<title>Contacto</title>
</head>

<body>

<h1>Contacto</h1>

<img src="contacto.jpg" alt="Imagen de contacto" width="300">

<p>email@email.com</p>

<a href="index.html">Inicio</a><br>
<a href="obra.html">Obra</a>

</body>
</html>
```
