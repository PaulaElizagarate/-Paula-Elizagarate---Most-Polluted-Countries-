
# Most Polluted Countries


## Objetivo

Este proyecto tiene como objetivo el conocer y analizar los países más contaminados del mundo. Para entender bien el contexto, hemos complementado la información con datos acerca de la natalidad y el coste de vida.

Nuestras motivaciones para realizar este análisis son responder a ciertas preguntas como:

*¿Hay características comunes entre los países más contaminados?

Para entender el análisis de datos realizado primero hay que conocer los ratios con los que hemos trabajado:

- Indicador de contaminación: hace referencia a la contaminación del aire debido a la presencia de sustancias nocivas en la atmósfera que dañan la salud de los seres vivos, clima o materiales. A continuación, podemos ver las orquillas del indicador:

<img src=https://www.sparetheair.com/assets/aqi/PM2017.png>

- Coste de vida : indicador formado por consumo de productos básicos (IPC) incluyendo compra , suministros, transporte y restaurantes. Queda excluido el precio de la vivienda. 

- Indice de natalidad: número de nacimientos ocurridos en un año entre su población total.

## Preguntas planteadas tras nuestro análisis

- ¿Pagamos por vivir en países menos contaminados?
- ¿Externalizamos a terceros países aquellas actividades económicas que implican la polución de nuestro entorno?
- ¿El coste de vida en estos terceros países es menor en consecuencia de la contaminación de sus ecosistemas o es fruto de una dinámica de relaciones socio-económicas?
- ¿Se vende la contaminación de estos terceros países por parte de sus gobiernos?
- ¿Tiene sentido regularizar, por ejemplo desde el prisma europeo, que las industrias no contaminen nuestro entorno más inmediato, pero que esas mismas industrias estén contaminando de manera masiva aquellos países con menor coste de vida?
- ¿La natalidad es un vehículo en muchos países para mantener las economías familiares?


## Estructura Carpetas
---
- *data*  almacena todos los CSV de nuestra extracción de datos, así como los CSVs resultantes de nuestra limpieza. 
- *notebooks* almacena 2 tipos de notebooks: extractores de datos, es decir, el código de scrapeo y nuestra limpieza de datos divida por tema (natalidad, coste de vida y polución). 
-*sql* almacena nuestra creación de base de datos en MySQL, el código de nuestra base de datos, la inserción de nuestros datos y análisis de los mismos a través de queries con sus respectivas visualizaciones.
- *src* almacena nuestro documento de funciones aplicadas a la hora de limpiar nuestros datos
- *images* almacena imágenes de nuestras visualizaciones así como imágenes de utilidad. 


## Tecnología Utilizada
---
- *BeautifulSoup* scrapeo de datos web con método Beautiful Soup
- *requests* para la gestión de HTTP
- *webdriver* para acceder al navegador con el scrapeo con método Selenium 
- *tqdm* para saber el avance de nuestro proceso de scrapeo
- *warnings* para la interpretación de errores
- *sleep* para introducir pausas a la hora de scrapear
- *import sys* para introducir el path de nuestros pipeline 
- *support* para importar nuestras funciones
- *pandas* gestión de DataFrames
- *numpy*  gestión de DataFrames
- *sqlalchemy* gestión de SQL
- *getpass* gestión de nuestra contraseña en SQL
- *matplotlib.pyplot* para visualización
- *seaborn* para visualización
- *plotly.express* para visualización






