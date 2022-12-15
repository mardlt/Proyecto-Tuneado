# Proyecto-Tuneado
![image](https://user-images.githubusercontent.com/119828910/207739030-a7d1717d-d6cf-460d-a890-b7b14072d08b.png)
Lectura de datos GPS con Python 

Resumen: Se realiza un programa en la plataforma Colab con base a lo aprendido durante las clases de Programación ll, el cual es capaz de leer datos de coordenadas de puntos sobre la superficie terrestre y los representa mediante una grafica mostrando sus datos correspondientes.
Palabras clave: Python, proyecto, datos, colab, superficie terrestre, programación II.
Abstract: A program is made in the Colab platform based on what was learned during Programming II classes, which is capable of reading coordinate data of points on the earth's surface and represents them by means of a graph showing their corresponding data.
Keywords: Python, project, data, colab, te rrestrial surface, programming II.

Introducción 

En el presente reporte se redacta cada uno de los pasos que fueron necesarios para la elaboración del producto final, que parte de los conocimientos básicos adquiridos durante el transcurso de la materia de Programación de Computadoras ll, así como también de la rigurosa búsqueda necesaria de información individual. Se plasma el proceso de elaboración en conjunto del objetivo general que abarca ampliamente a lo que se busca llegar con el resultado final, así como de los objetivos específicos que fueron necesarios para la conformación del producto final. Una vez explicado todo el proceso mediante hipótesis, criterios basados en información existente y con base a los resultados obtenidos se recata un apartado de conclusiones en el que cada integrante redacta su experiencia tanto individual como de equipo durante el desarrollo del mismo.

Desarrollo 

Python es un lenguaje de programación ampliamente utilizado en las aplicaciones web, el desarrollo de software, la ciencia de datos y el machine learning (ML). Los desarrolladores utilizan Python porque es eficiente y fácil de aprender, además de que se puede ejecutar en muchas plataformas diferentes. Python permite que los desarrolladores sean más productivos, ya que pueden escribir un programa de Python con menos líneas de código en comparación con muchos otros lenguajes. La geolocalización consiste en obtener la ubicación geográfica de un objeto como puede ser un teléfono móvil, un coche o una calle. Para ello se puede utilizar diferentes métodos como por ejemplo comprobar el código postal de una carta, la dirección IP de un equipo o el sistema GPS de nuestro teléfono móvil. Los cual para el desarrollo de este programa que estamos creando se utilizan ciertotipos de librerías como lo son matplotlib, importar un archivo desde drive y pandas, además del módulo os. Pandas es una librería de Python especializada en la manipulación y el análisis de datos. Ofrece estructuras de datos y operaciones para manipular tablas numéricas y series temporales, es como el Excel de Python. Las principales características de esta librería son: 
• Define nuevas estructuras de datos basadas en los arrays de la librería NumPy pero con nuevas funcionalidades. 
• Permite leer y escribir fácilmente ficheros en formato CSV, Excel y bases de datos SQL. 
• Permite acceder a los datos mediante índices o nombres para filas y columnas. 
• Ofrece métodos para reordenar, dividir y combinar conjuntos de datos. 
Matplotlib es una librería de trazado utilizada para gráficos 2D en lenguaje de programación Python, es muy flexible y tiene muchos valores predeterminados incorporados que te ayudarán muchísimo en tú trabajo. Produce figuras de calidad de publicación en una variedad de formatos impresos y entornos interactivos. Como tal, no necesitas mucho para comenzar, solamente tienes que hacer las importaciones necesarias, preparar algunos datos y con pued
nuuuuhhuhhes comenzar a trazar tu función con la ayuda de la instrucción plot. () El módulo os nos permite acceder a funcionalidades dependiema Operativo. Sobre todo, aquellas que nos refieren información sobre el entorno del mismo y nos permiten manipular la estructura de directorios (para leer y escribir archivos Para la creación del programa el propósito que se tiene en mente es la realización del programa que mediante un archivo .csv lo puedo graficar, lo cual los datos que se utilizaron para crear el archivo fueron las coordenadas de puntos geo localizados por teléfonos móviles, los cuales se registraron las coordenadas de cada uno al igual que su altitud y se registraron en Excel en un archivo delimitado por comas.aquellas que nos refieren información sobre el entorno del mismo y nos permiten manipular la estructura de directorios (para leer y escribir archivos Para la creación del programa el propósito que se tiene en mente es la realización del programa que mediante un archivo .csv lo puedo graficar, lo cual los datos que se utilizaron para crear el archivo fueron las coordenadas de puntos geo localizados por teléfonos móviles, los cuales se registraron las coordenadas de cada uno al igual que su altitud y se registraron en Excel en un archivo delimitado por comas.aquellas que nos refieren información sobre el entorno del mismo y nos permiten manipular la estructura de directorios (para leer y escribir archivos Para la creación del programa el propósito que se tiene en mente es la realización del programa que mediante un archivo .csv lo puedo graficar, lo cual los datos que se utilizaron para crear el archivo fueron las coordenadas de puntos geo localizados por teléfonos móviles, los cuales se registraron las coordenadas de cada uno al igual que su altitud y se registraron en Excel en un archivo deli.

![image](https://user-images.githubusercontent.com/119828910/207763694-99cfc3b1-0874-4f63-8123-9cf59b066e64.png)

En cuanto a las herramientas utilizadas para el desarrollo de nuestro programa se encuentras las siguientes:
1.- Computadora
2.- Internet
3.- Google Colab
4.- Excel
5.- Base de datos (Coordenadas)
6.- La mayor información posible recabada

![image](https://user-images.githubusercontent.com/119828910/207763751-d6d6da62-0cd4-42fb-a97e-d515edcfc5cb.png)

Hablando de términos técnicos y del proceso que se llevó a cabo para la obtención de resultados finales, podemos encontrar una serie de pasos que nos llevaron a la conformación del desarrollo de este documento redactado. 
Como primer paso se requirió de una investigación exhaustiva para la recabación de información importante como el conocer las librerías que serían utilizadas partiendo de las hipótesis planteadas al comienzo. Una vez encontrada dicha información procedimos a importar las librerías como se muestra en la imagen posterior.

![image](https://user-images.githubusercontent.com/119828910/207763804-b4d5538b-f449-48fb-a963-a254e2f37e1b.png)

En ocasiones Colab necesita la instalación previa de los paquetes de dichas librerías y se tiene que llevar un proceso previo a lo descrito anteriormente, pero como en este caso la instalación de los paquetes no fue necesaria no entraremos a detalle en ese aspecto.
Después de importar todas librerías necesarias, ahora solo importamos o enlazamos a google drive desde colab, para que así nos dé acceso a drive dependiendo la cuenta, pero el problema es que debes de tener el archivo en un carpeta en drive para que se puede realizar la lectura del archivo, así ya importado desde drive, se copia la ruta de donde esta para que así pueda leerlo. 

![image](https://user-images.githubusercontent.com/119828910/207763902-a96c0930-db4a-4357-ae60-f20990647ae8.png)

Ya importado el archivo solo indicamos que debe de leerlo por sus columnas para así registra las y poder graficarlas, ya leído el archivo y que lo haya encontrado en drive, ahora lo indicamos que lo grafique desde un mapa y los ubique mediante unos puntos, junto con su descripción y ID, lo cual para ello también indicamos como un título representativo al mapa de lo cual esta asignado como coordenadas puntos locales.

![image](https://user-images.githubusercontent.com/119828910/207763961-ef229331-2b59-468d-9d3b-558eb8924192.png)

Una vez creado el programa lo hacemos correr y checamos correctamente que no haya falla a la hora de leer el archivo desde drive para poder seguirlo, y así finalmente grafica los puntos que están el archivo .csv generando un mapa con sus coordenadas que hayamos capturado.
Para fines del ordinario y con permiso del resto de los autores y colaboradores del proyecto, me di a la tarea de agregar una extensión al programa con la finalidad de que no solamente graficara los datos de un solo archivo csv, sino que cree una nueva carpeta con datos GPS recabados desde un teléfono móvil en el que se presentan una serie de datos en X, Y que son graficados al mismo tiempo que se procesa la información del programa previamente entregado por mis compañeros de equipo.

Manejo de datos 

Mi versión del programa presentado funciona con base a una serie de datos recopilados a partir de un censo y de un breve recorrido dentro de las instalaciones de la Facultad de Ingeniería Civil, para ser exactos comenzando en la parte norte del área de los comedores y recorriendo en dirección a servicios estudiantiles, generando 284 puntos a una velocidad media de 4.3 km/h, distancia de 340 metros, duración de 04:43 minutos y una diferencia de altura de 1 metro aproximadamente. Estos datos contienen características que nos permiten poder ubicarlos como datos geoespaciales con ayuda de un programa. Cuentan con un código de identificación y las coordenadas dadas en x, y, z para el caso de los datos del primer archivo, el el caso del segundo archivo generado con un teléfono móvil, cuenta con datos de identificación como lo son las coordenadas en X,Y. Para hacer la correcta función de estos datos se ha generado un archivo con características de .csv que posteriormente fue guardado en drive con la intención de que al ejecutar el programa este lo llame mediante un código y de esta manera nos permita conocer su componente geoespacial.


![image](https://user-images.githubusercontent.com/119828910/207764049-f86dbdc0-ea6f-42e5-b78c-ce9f614e674a.png)

Si observamos los datos a importar podemos darnos cuenta de que en la columna de norte todos los valores son negativos, esto porque de acuerdo a las características geoespaciales indica que cuando los valores con negativos son porque representan el Este desde el meridiano de Greenwich y los valores positivos representan el Oeste. Las líneas de latitud (coordenadas Y) van desde -90º hasta +90º. Siendo los valores negativos los que representan el Sur desde el ecuador y los valores positivos los representa el Norte. Cada uno de los datos registrados en el csv son leídos por el programa y ubicados en la coordenada que les corresponde con ayuda de un mapa que a su vez el programa se en carga de graficar.

![image](https://user-images.githubusercontent.com/119828910/207764103-15c860ab-70ff-4843-b623-da25c5f6c2c1.png)

Resultados 
Como resultado final presentamos un programa que dadas las características geográficas de ciertos puntos proporciona la ubicación de cada uno de ellos. En este caso y con referencia a los datos brindados para el desarrollo del programa se hace la localización de 18 puntos que se ubican sobre un gráfico proporcionado por el mismo programa en el que al poner el cursor sobre cada uno de los puntos se proporciona la información con la que este fue localizado, es decir: se presenta la descripción del punto y su característica geográfica.

![image](https://user-images.githubusercontent.com/119828910/207764160-d911524a-43f9-4b96-a2a7-1d5e5dfac118.png)

Entrando en posibles aplicaciones el programa proporcionado podría ser utilizado como una herramienta en distintas áreas en las que se requiera de la ubicación por áreas, regiones, etc., de algunos elementos, por ejemplo; mediante coordenadas se podría hacer una esquematización para poder hacer un análisis adecuado de la información sobre algún tema. De esta manera todo aquel que trabaje con la ubicación geográfica de las cosas podría utilizar el programa para darle mayor énfasis a sus proyectos futuros. En este caso con ayuda del programa realizado se hace la ubicación de los resultados obtenidos en un censo elaborado en el municipio de Colima, es por esta razón que los puntos ubicados se concentran en la región sureste del gráfico.

Conclusión 

Como conclusión final del proyecto queda claro que para la creación de códigos o programas que nos den resultados geoespaciales es demasiado importante saber cómo realizarlo y qué tipo de librerías o módulos tener que instalar para que así nos arroje resultados que esperamos, la parte geoespacial es muy amplia ya que se pueden crear diferentes tipos de programas o proyectos que demuestren resultados como mapas, puntos, gráficas, etc., es por eso que es muy importante conocer todo sobre eso ya que es indispensable para poder crear cual quiero tipo de trabajo que tenga que ver con la programación, así que como enseñanza de este proyecto se logró generar un programa lo cual nos arrojará resultados finales lo cual como objetivo que se tenía en mente era generar un mapa que creará los puntos y los identificará rápidamente importándolo desde un archivo .csv con coordenadas, descripción y su número de punto y al final se logró generar el programa que nos ayude a obtener esos resultados.
Y como ya se menciona anteriormente, concluyo personalmente con la extensión del código para facilitar la entrada de más de un archivo a la vez con características similares y posibles de integrar.


Referencias 

•	Alberca, A. S. (2020, 4 octubre). La librería Matplotlib. Aprende con Alf. https://aprendeconalf.es/docencia/python/m anual/matplotlib/ Maluenda, R. (2022, 17 agosto). 
•	Introducción a Pandas, la librería de Python para trabajar con datos. Profile Software Servi ces. https://profile.es/blog/pandas-python/ uniwebsidad. (s. f.). 10.1. 
•	Módulos de sistema (Python para principian tes). https://uniwebsidad.com/libros/python/capit ulo-10/modulos-de-sistema



