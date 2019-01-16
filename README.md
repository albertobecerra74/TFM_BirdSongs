# TFM_BirdSongs
KSchool TFM (8 Master Data Science)

Identificando aves por el canto
=======

El objetivo de este trabajo es determinar si es posible generar un modelo lo bastante preciso, que permita la identificación de las aves a partir de sus cantos y que pueda ser utilizado con fines de investigación y/o comerciales. Para ello contamos con un dataset elaborado a partir de la web [Xeno-Canto](https://www.xeno-canto.org) con grabaciones de aves localizadas en el continente europeo.

Ver el documento con la propuesta inicial: TFM_Identificando_aves_por_el_canto.pdf

Memoria
-------------

La memoria contiene un resumen del trabajo realizado, las metodologías y herramientas utilizadas para su elaboración, así como los resultados y conclusiones obtenidas.

Ver documento **TFM_Memoria_Identificando_aves_por_el_canto.pdf**


Notebooks
-----------------------
Notebooks elaborados para la ejecución del trabajo

* Birdsongs_01_Obteniendo_Datos_Webscrapping_DataSet.ipynb
* Birdsongs_02_Obteniendo_Datos_Seleccionando_Especies.ipynb
* Birdsongs_03_Obteniendo_Datos_Descargando_Audios.ipynb
* Birdsongs_04_Obteniendo_Datos_Verificando_Integridad.ipynb
* Birdsongs_05_Preprocesando_Datos_Explorando_Audios.ipynb
* Birdsongs_06_Preprocesando_Datos_Convirtiendo_Audio_a_Datos.ipynb
* Birdsongs_07_Preprocesando_Datos_Cortando_Datos.ipynb
* Birdsongs_08_Preprocesando_Datos_Convirtiendo_Datos_a_Imagenes.ipynb
* Birdsongs_09_Modelando_Datos_Determinando_Sets_Train_Validation_Test.ipynb
* Birdsongs_10_Modelando_Datos_Deep_Learning_CNN.ipynb
* Birdsongs_11_Modelando_Datos_Deep_Learning_DNN.ipynb

Datasets
-----------------------
* Birdsongs_europe_C_20181220213936.csv: Dataset original scrapeado 
* **Birdsongs_My_Birdsongs_Europe_20181230103204.csv: Dataset de trabajo**
* Birdsongs_My_Especies_Europe_20181230103204.csv: Listado de especies


Repositorios
-----------------------

* **audio**: contiene las grabaciones en mp3 de 5 de las especies utilizadas. Por motivos de espacio no se han subido más.
* **data**: repositorio donde se generan los datos
* **image**: repositorio donde se generan las imágenes
* **model**: repositorio donde se generan los modelos con el conjunto de datos de train, validación y test
* **results**: repositorio donde se almacenan las ejecuciones en formato HTML
* **resources**: repositorio con imágenes y fotos para la elaboración del trabajo

Resultados
-----------------------

Ver https://public.tableau.com/profile/alberto.becerra#!/vizhome/TFM_Birdsongs/BirdSongs, que muestra un pequeño dashboard con los resultados obtenidos.

Agradecimientos
-----------------------

A la web [Xeno-Canto](https://www.xeno-canto.org) por permitir el uso de la grabaciones de audios.



