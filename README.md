# PopUps
## Los pop ups son la primera característica interactiva que estaremos incluyendo a nuestro mapa, los popups son pequeñas ventanas que se despliegan al dar click sobre algún elemento, similar a como ocurre en cualquier sitio web.

### Para añadir esta opción, es necesario escribir la información que deseamos incluir. 
Esto es muy útil para añadir alguna breve descripción, o incluso, imágenes, u otro contenido multimedia compatible con html.

#### A continuación veremos los elementos del código necesarios para añadir esta interesante opción.

``` html
<script>	
var marker1 = L.marker([20.86114, -99.785305]).bindPopup('Esto es un PopUp').addTo(map);
</script>
```
### Al ejecutar en tu navegador deberías tener algo como esto.

![screenshot](https://raw.githubusercontent.com/sampach95/PopUps/master/img/popups.png )

Siguiente Tutorial https://github.com/sampach95/ConvertirFormatosAGeoJSON

Haz click en el siguiente enlace para volver a la pagina inicial
https://github.com/sampach95/ComoCrearMapasEnLaWebConLeaflet
