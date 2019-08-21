# AI_Agricultura
Inteligencia artificial para el uso agricola

<img src='/images/BannerAI.png' width='1000px'>

Nuestros agricultores Colombianos por medio de su experiencia han logrado grandes resultados en la producción agrícola, sin embargo con ayuda de la inteligencia artificial y la recopilación de datos obtenidos de la experiencia de varios agricultores en diferentes regiones del país, se le otorga mas confiabilidad al proceso de predicción  y control de la producción agrícola.

**Objetivos del proyecto**

- Solucionar problemáticas referentes al tipo de cultivo o área a escoger,ayudar o predecir que cultivos plantar dependiendo la zona geográfica, y la viabilidad del cultivo entre otros datos recopilados en los datasets (Disponibles [aquí](https://www.datos.gov.co/) , [aquí](https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Cadena-Productiva-Ma-z-Area-Producci-n-Y-Rendimien/d968-yfb5)).
- Predecir que tipo de zona es acta para los cultivos, a partir de ciertas características, saber que tan productivo podría resultar el cultivo o que cultivo se podría obtener.

**Material Disponible**

- Se encuentran disponibles las dos versiones del proyecto(El analisis inicial 'Pv1.ipynb'; El analisis completo, predicción de la producción de los cultivos, comparación de metodos usados 'Pv2.ipynb').

- Se encuentra tambien el material utilizado para exponer, datos importantes, interesantes y relevantes en sus dos versiones(Sin compilar 'Pv2Slides.ipynb' y Compilado 'Pv2Slides.slides.html').

- Están disponibles las imagenes utilizadas para desarrollar el material expositorio como resultado de los notebooks trabajados.

- Se encuentra el link del breve video explicativo del proyecto.

**Desarrollo del proyecto**

- Inicialmente, los datos a trabajar fueron clasificados, proceso en el cual se descartaron conjuntos de datos que no eran de interes para el desarrollo del proyecto, que no servian para su analisis y no podian tratarse.

- Se determinaron como utiles un conjunto de datos de 8 columnas por dataset de un total de 16, seguidamente se convirtieron todos los datos alfanumericos a datos numericos siendo estos relacionados por medio de diccionarios de python con un unico ID en cada caso.

- Se visualizaron los datos de multiples maneras con el fin de encontrar las relaciones adecuadas para cumplir con los objetivos del proyecto, se encontró y marcó como importante la relación entre el municipio, departamento, area sembrada, area cosechada, producción y rendimiento.

- Se determina la relación entre el lugar donde se siembra y el área sembrada con la producción y el rendimiento del cultivo, se usan varios metodos de regresión documentados en la libreria SKLEARN.

- Se encuentra la convergencia entre algunos de los metodos utilizados hacia la solucion real del problema, obteniendo así un estimado de producción a partir de un lugar de siembra y un área sembrada que solventa los objetivos del proyecto. Se desestiman los metodos que no convergieron ya que no tenian un buen comportamiento de predicción.

**Conclusiones**

- Con los resultados obtenidos se determina que el lugar donde se siembra, es un factor importante ya que por propiedades de cada cultivo su producción es mejor en ciertas zonas del país, es decir, por propiedades como la necesidad de acidez en el suelo, buena vegetación, clima templado o caliente, presencia de animales entre otras cosas, la producción en cada cultivo resulta diferente dependiendo del sitio en donde se sembró.

- Se concluye que si las condiciones del terreo o ecosistema en el cual se siembra el cultivo son las adecuadas, la producción del mismo es proporcional al área sembrada y se obtiene un margen de perdida muy pequeño.


Puedes consultar el video del proyecto [aquí](https://www.youtube.com/embed/rraRTj8XcPE)
