# Coordenadas UTM (10 de 36)

Las **coordenadas UTM** llevan una numeración que está **en relación a un imaginario sistema de ejes cartesianos compuesto por el meridiano medio del Huso y la línea del ecuador**.

Como este sistema de ejes cartesianos se repite en cada Huso, **es muy importante que cada coordenada UTM esté en relación a su Huso**, pues de otra manera es una coordenada que se repite 60 veces sobre la superficie de la tierra.

![Coordenadas UTM](./gps_files/Coordenadas UTM.jpg)

En la imagen podéis ver cómo se estructuran estas coordenadas.

**Por encima de 84º N o por debajo de 80º S no se aplican este tipo de coordenadas** ni de proyección por las grandes deformaciones antes comentadas. Entre 84ºN y 80ºS sí se utilizan.

Las **coordenadas UTM se expresan en metros** (m).

La **coordenada X es siempre positiva** y va de un valor 166.021 m. a un valor 833.979 m. en el ecuador, menos a medida que nos desplazamos hacia los polos.

La **coordenada Y es también siempre positiva**, pero debe ir vinculada a un valor N o S pues se repiten valores a ambos lado del ecuador. En el hemisferio norte, que es el que nos interesa, va de un valor 0 a un valor 9.329.005 m.

Como puedes ver, **este tipo de coordenadas nada tienen que ver con las geográficas**, que son en grados y son únicas para cada punto del planeta, mientras que éstas se repiten en cada Huso y si se desvinculan del mismo (si se da la coordenada sin el Huso) es muy difícil saber de qué lugar se trata pues esa misma localización se repite 60 veces sobre la tierra.

Los mapas excursionistas de España, que provienen todos de las bases digitales topográficas del Instituto Geográfico Nacional, están basados en este tipo de coordenadas proyectadas UTM, y en los márgenes de los mapas aparecen este tipo de valores.

#### A la hora de entender las coordenadas UTM debéis tener en cuenta que...