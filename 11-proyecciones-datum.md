# Proyecciones: DATUM (11 de 36)

![Datum](./gps_files/Datum.jpg)El **[datum](http://es.wikipedia.org/wiki/Datum "Datum en wikipedia")** es un conjunto de parámetros que **definen la posición del elipsoide de referencia con respecto a la superficie real de la tierra** (el geoide).

No es un único dato sino un conjunto de ellos. **Por un lado se establece el elipsoide de referencia y por otro el punto en el que dicho elipsoide es tangente al geoide**.

Para entenderlo de forma sencilla, es un conjunto de valores que **permiten un ajuste mejor del elipsoide de referencia a una parte de la realidad**, entendiendo que cuando se ajusta bien por un lado, este elipsoide se "desajusta" por otro. Por la imagen te podrás hacer una idea...

Las **coordenadas geográficas** habitualmente vienen referidas al **Datum WGS 84.**

Las **coordenadas UTM** **en España** se han venido refiriendo en los últimos años al **Datum ED50** (European Datum 1950), pero por normativa europea ([**normativa INSPIRE**](http://www.idee.es/europeo-inspire "Normativa INSPIRE")) antes del 2015 todos los países de la Unión Europea deben tener su cartografía en **coordenadas UTM Datum ETRS89. **En España se está en pleno proceso de migración y si bien el Instituto Geográfico Nacional ha migrado ya prácticamente todos sus datos, **no es así con las editoriales que se dedican a hacer cartografía excursionista**, que todavía tienen en el mercado un importante número de mapas en coordenadas UTM Datum ED50.

**La diferencia de valores entre estos dos sistemas es apreciable sobre todo cuando se usa GPS**, más que sobre el propio mapa, **y es del orden de 200 m de distancia** entre los valores de un punto descrito con un Datum y los valores del mismo punto descrito con el otro Datum.

**El Datum WGS84 se considera equivalente al ETRS89**.

No vamos a entrar en más detalles sobre el Datum. Sólo lo queríamos nombrar para que sepáis que existe y que en las coordenadas que habitualmente manejamos un error de interpretación de Datum puede llevar a errores del orden de 200 m sobre el terreno.

La idea que tienes sobre el datum es que...