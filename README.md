# ymoto_motosono
Mi primer proyecto para el curso de Desarrollo web en Coderhouse

CAMBIOS HECHOS PARA EL SEPTIMO DESAFIO DE SASS II + SEO
*Agregué en el head de cada html:
<meta name="description" content="Blog about the artist, dj and music producer YMOTO">
<meta name="keywords" content="YMOTO, DJ, ARTIST, MUSIC, MUSIC PRODUCER">

*Utilicé la página de https://webspeedtest.cloudinary.com/ para optimizar las imágenes empleadas en la página web. 

*Dentro de la carpeta scss creé: 
-la carpeta generic con los archivos:  _box-sizing.scss y _normalize.scss

*Hice uso de mapa:
-declaré un mapa(está en _partials.scss) en el footer para los botones de redes sociales
-creé el bucle para usar los valores del mapa

*Hice uso del extend:
-Primero declaré un h1 modelo(está en _partials.scss), el h1 son los titulos de cada page. 
-Luego de llamar al @extend le agregué modificadores a los que tenía que modificar.

*Hice uso de mixin:
@mixin sizes($width, $height) {
    height: $height;
    max-width: $width;
}
