# Otras bibliotecas para programación de SIG en la Web
Además de [Leaflet](https://leafletjs.com/), hay varias bibliotecas en el lenguaje [JavaScript](https://es.wikipedia.org/wiki/JavaScript) que facilitan la programación de mapas en la Web. Algunas listas y comparaciones pueden encontrarse en:

- [mappingGIS - Las 10 mejores librerías JavaScript para crear mapas web](https://mappinggis.com/2015/03/las-mejores-apis-javascript-para-webmapping/)  
- [Flatlogic - Top Mapping and Maps APIs](https://flatlogic.com/blog/top-mapping-and-maps-api/)  
- [GEOG 585: Open Web Mapping - What is a web mapping API?](https://www.e-education.psu.edu/geog585/node/763)  
- [RapidAPI - The Top 10 Mapping & Maps APIs](https://rapidapi.com/blog/top-map-apis/)  

Seguidamente, se brindan descripciones y ejemplos de dos de las bibliotecas más populares: Google Maps y OpenLayers.

## Google Maps
[Google Maps](https://developers.google.com/maps/documentation) ofrece un conjunto de API (*Application Programming Interface*) para la programación de mapas en la Web y en otras plataformas (ej. dispositivos móviles). Fue lanzado por Google en 2005. Además del API, ofrece un conjunto de capas geoespaciales que incluyen mapas de calles, imágenes satelitales, fotografías aéreas, vistas panorámicas y datos de tráfico en tiempo real, además de servicios como geocodificación y planeación de rutas, entre otras. En 2021, Google Maps es utilizado cada mes por mil millones de personas de todas partes del mundo ([https://sites.google.com/a/pressatgoogle.com/google-maps-for-iphone/google-maps-metrics](https://sites.google.com/a/pressatgoogle.com/google-maps-for-iphone/google-maps-metrics)).

A diferencia de Leaflet, y otras API libres, [Google Maps no es gratuito](https://cloud.google.com/maps-platform/pricing), pero puede user utilizado gratuitamente hasta un límite de solicitudes al API. Por otra parte, el API está enfocada en los mapas de Google y la integración de otras fuentes de datos es difícil.

Para desarrollar aplicaciones en Google Maps, es necesario obtener una [llave para acceder al API](https://developers.google.com/maps/gmp-get-started).

Puede ver un ejemplo de un mapa desarrollado con el API de Google Maps en:  
[https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-google/](https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-google/)

## OpenLayers
[OpenLayers](http://openlayers.org/) es otra biblioteca licenciada como software libre. Fue lanzada en el año 2005. Su API básica es muy extensa y no se apoya tanto en el uso de complementos, como sí lo hace Leaflet. Esto puede darle más consistencia al API pero, por otra parte, también puede hacer más grandes las aplicaciones.

Puede ver un ejemplo de un mapa desarrollado con OpenLayers en:  
[https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-openlayers/](https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-openlayers/)
