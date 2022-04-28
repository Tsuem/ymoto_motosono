# ymoto_motosono
Mi primer proyecto para el curso de Desarrollo web en Coderhouse

<h2> CAMBIOS HECHOS PARA EL SEPTIMO DESAFIO DE SASS II + SEO Y PARA LA TERCER ENTREGA</h2>
*Agregué en el head de cada html:
<meta name="description" content="Blog about the artist, dj and music producer YMOTO">
<meta name="keywords" content="YMOTO, DJ, ARTIST, MUSIC, MUSIC PRODUCER">

*Utilicé la página de https://webspeedtest.cloudinary.com/ para optimizar las imágenes empleadas en la página web. 

*Dentro de la carpeta scss creé: 
-las carpetas para cada elemento, organismo, herramientas y partials.

*Hice uso de mapa:
-declaré un mapa en el footer para los botones de redes sociales
-creé el bucle para usar los valores del mapa

*Hice uso del extend:
-Primero declaré un h1 modelo, el h1 son los titulos de cada page. 
-Luego de llamar al @extend le agregué modificadores a los que tenía que modificar.

*Hice uso de mixin:
@mixin sizes($width, $height) {
    height: $height;
    max-width: $width;
}
