# Informe completo del Dashboard

En este proyecto, se me encomendó la realización de un análisis que permita reconocer las principales características del comportamiento de los servicios de telecomunicaciones. Considerando que la actividad principal de la empresa es brindar acceso a internet, se tomó como referencia principal la evolución en los últimos años de los diferentes tipos de conexiones.

Se tomaron datos del Ente Nacional de Comunicaciones (ENACOM), y luego de un proceso de extracción, transformación y carga en el que se direccionó la selección de datos hacia aquellos puntos prometedores, se realiza un análisis exploratorio de los mismos con el objetivo de alcanzar conclusiones y recomendaciones.

La importancia de un análisis de esta naturaleza descansa en que el principal medio de intercambio de datos, en orden interno o internacional, es a través de internet. Conocer el comportamiento y evolución de este servicio permitirá encontrar puntos de mejora y mayor rentabilidad, lo que directa o indirectamente afecta la calidad de vida de los ciudadanos en un país que se encuentra a la vanguardia en la región en materia de conectividad.

## Ejes Principales del Análisis

Para realizar el análisis, se hizo foco en dos ejes principales: el primero de ellos, se encuentra relacionado a la velocidad de las conexiones. Podemos observar rápidamente que, de acuerdo a su evolución histórica, hay una estrecha relación entre la velocidad y la tecnología disponible. El segundo consiste en el análisis de la penetración de la conectividad en la población.

### Velocidad y Tecnología

En los últimos diez (10) años, han prevalecido por sobre las otras ciertos tipos de tecnologías:

- **ADSL** (línea de suscriptor digital asimétrica por sus siglas en inglés - Asymmetric Digital Subscriber Line): consiste en conexiones de banda ancha a través de líneas telefónicas de cobre tradicionales.
- **Cablemódem**: consiste en conexiones de cable coaxial a través del cual se lleva la televisión por cable.
- **Fibra óptica**: consiste en una guía de onda en forma de hilo, con filamentos de óxido de silicio y zinc (que tienen una alta refracción), para transmitir información utilizando señales ópticas.

Puede observarse que las conexiones a través de líneas telefónicas (ADSL) eran la conexión predominante hasta el año 2017, cuando empezó a ser desplazada por las conexiones a través de cable coaxial (cablemódem).

Debemos considerar que, en ese entonces, la velocidad de conexión promedio de descarga era de 9 Mbps. El cablemódem ofrece mayor estabilidad en las conexiones, y permite transmitir información a niveles considerablemente más rápidos, sin el desgaste que suponen las conexiones telefónicas de cobre.

A medida que se afianzaba el crecimiento de este tipo de conexiones, aumentaba la velocidad promedio de las mismas. Hacia 2021 este tipo de conexiones ya era absolutamente predominante en Argentina, y apenas empezaban a tomar importancia las conexiones de fibra óptica. El escenario de conectividad ya era otro: existía una velocidad promedio de 47 Mbps.

Hacia 2023, las conexiones ADSL continuaron en su tendencia a la baja, llegando a abarcar apenas el 8% de las conexiones. Por su parte, se observa un notorio avance de la tecnología de Fibra Óptica, que incluso ha comenzado a desplazar las conexiones de cable coaxial (Cablemódem). Esta prevalencia de cablemódem y fibra óptica, han llevado a que el promedio de velocidad de bajada llegue a 126 Mbps.

De esta forma, vemos una relación directa entre el tipo de tecnología utilizado y la velocidad de descarga. El reemplazo de ADSL por cablemódem ha mejorado considerablemente las conexiones, y se ha aumentado la tendencia aún más con el reemplazo de ambas tecnologías por fibra óptica. Esta evolución tecnológica no sólo impacta en la mejora de las conexiones, sino que permite una mejora en la calidad de vida de las personas, impactando en comunicaciones con un fuerte peso en los sectores de educación, en el mercado laboral, entre otros.

### Penetración en la Población

Analizada la relación entre los diferentes tipos de tecnologías y la velocidad, corresponde ahora adentrarse en el nivel de acceso existente en la población. En Argentina, el promedio de conexiones por cada 100 hogares es de 102. Es decir: existen más conexiones que hogares. Se ve una relación de 1 a 3 con el promedio de conexiones por cada 100 habitantes (33). Esto tiene mucho sentido si se considera que el hogar promedia 3,34 habitantes.

Pero estos valores actuales estaban bastante por debajo de esos valores hacia el año 2017, cuando comenzó el crecimiento de conexiones de Cablemódem y Fibra óptica (ésta última, en menor medida). Este análisis es más apropiado hacerlo por provincias, por eso podemos visualizar que las 3 provincias con mayor acceso por cada 100 habitantes son:

- Buenos Aires
- Capital Federal
- Córdoba

Por su parte, aquellas que más acceso por cada 100 hogares tienen, son:

- Capital Federal
- Córdoba
- La Pampa

Aquí podemos considerar dos variables que dan cuenta de los motivos de tal penetración: las principales provincias se encuentran en la zona central del país, donde han existido grandes proyectos para mejorar las conexiones de red. Lo que potencia tal nivel de accesos, por su parte, es la densidad poblacional de cada provincia. Por ejemplo, la Provincia de Buenos Aires, que es la segunda provincia territorialmente más extensa, tiene 17,57 millones de habitantes. Mientras que la Ciudad Autónoma de Buenos Aires, sin considerar el conurbano bonaerense, cuenta con 3,12 millones de habitantes.

Si ponemos el foco en la densidad geográfica, CABA se encuentra muy por encima que Provincia de Buenos Aires. El área metropolitana de Buenos Aires (AMBA), que es una zona que comprende la Ciudad de Buenos Aires y otros 40 municipios conglomerados, tiene 14.8 millones de habitantes, prácticamente la tercera parte de la población del país.

En esta zona prevalece el acceso por población y por hogar, lo que puede explicarse a partir de la colocación de diferentes empresas, de la cantidad de oficinas públicas y gubernamentales, además de la cantidad de habitantes; lo que llevó a las principales empresas de telecomunicaciones a realizar grandes inversiones para prestar un mejor servicio en esta zona.

Observamos también una fuerte presencia de la Provincia de Tierra del Fuego. Se trata de una provincia pequeña (sólo supera en extensión a la Provincia de Tucumán), con sólo 185 mil habitantes. Pero lo que explica este nivel de conectividad es su importancia estratégica: además de tratarse de una zona ampliamente solicitada turísticamente, se encuentra geográficamente posicionada en una zona de gran explotación petrolera, y de gran relevancia en la investigación científica, por encontrarse a breve distancia de la Antártida continental.

Ello, sin mencionar el posicionamiento de ciertas grandes empresas de desarrollo de hardware y telefonía celular, lo que ha repercutido exitosamente en la consecución de inversiones que impactaron en el nivel de conexiones.

Ahora bien, analizados los niveles de acceso, podemos observar una correlación entre ese acceso y la velocidad de conexión. Ciertamente, esta correlación no llega a explicar el 100% del aumento de accesos por hogar y/o por habitantes. Pero sí nos da indicios de la existencia de otra variante que lo explica, como la tecnología disponible, que tiene a su vez una estrecha vinculación con la velocidad de conexión vista anteriormente.

Podemos señalar que el mayor acceso a internet, combinado con tecnologías más avanzadas, ha influido (y continúa haciéndolo) en el desarrollo social y económico de ciertas regiones (como el caso de Tierra del Fuego). Esto permite un mayor acceso a la información, educación y servicios.

Por su parte, el ofrecimiento de nuevas tecnologías más adecuadas al nivel y calidad que busca una población tan exigente como la argentina en esta materia, implica insertarse en un mercado que no estaba conforme con la relación precio-calidad de ciertas tecnologías como ADSL y Wireless.

Podemos concluir que la mayor disponibilidad de nuevas tecnologías ha sido un factor clave en la expansión del acceso a internet, llevando a una mayor penetración.

## El Caso de Starlink

Podemos observar que, geográficamente, quedan muchas zonas sin conexiones, o conexiones con tecnologías que ofrecen baja velocidad de descarga. Actualmente, esto se explica por las fuertes inversiones que requieren las tecnologías de Cablemódem y Fibra Óptica, para reemplazar las existentes. Deben cubrir grandes extensiones territoriales, sin mucha protección.

Las conexiones de fibra telefónica lideran en zonas alejadas, porque ya cuentan con una infraestructura muy antigua de cableado telefónico. Por su parte, las conexiones de internet satelital ofrecen una calidad del servicio defectuosa o insuficiente, que no permite mantener conexiones estables a una velocidad adecuada.

En ese sentido, la aparición y llegada de Starlink en la Argentina resuelve parte del problema planteado: es una conexión satelital (subtipo de Wireless) que ofrece una conexión estable con velocidades que pueden alcanzar hasta los 200 Mbps (por encima de la media de velocidad de descarga al año 2023).

## Conclusiones

A lo largo del análisis, se han identificado diversos patrones que arrojan luz sobre el desarrollo futuro de las telecomunicaciones por internet en Argentina. Este estudio nos ha permitido entender mejor los principales motores detrás de las mejoras en la calidad y expansión de la red, identificar áreas con potencial de progreso, y establecer objetivos claros para el crecimiento sostenido del sector.

- **Nivel de Acceso y Penetración**: Aunque Argentina muestra un nivel relativamente alto de accesos y penetración en la población, el análisis revela que todavía existe un margen significativo para la expansión. Es crucial continuar impulsando el crecimiento de nuevas tecnologías, como la fibra óptica y soluciones como Starlink, para cubrir las zonas aún no alcanzadas y mejorar la calidad del servicio.
  
- **Tecnología y Velocidad de Conexión**: La correlación entre la tecnología utilizada y la velocidad de la conexión es clara. El avance hacia tecnologías más rápidas y eficientes, como la fibra óptica, es esencial para seguir mejorando las velocidades de conexión en todo el país.

- **Inversiones Estratégicas**: Las inversiones deben dirigirse a las áreas que muestran un crecimiento significativo, como las zonas con alta densidad de población y las regiones estratégicamente importantes. Esto no solo mejorará la calidad de vida, sino que también incentivará el desarrollo económico y social.

En resumen, este análisis proporciona una visión detallada del estado actual de la conectividad en Argentina y ofrece un marco para las futuras estrategias de expansión y mejora de los servicios de internet.
