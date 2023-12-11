# Reto-Analisis-de-Trafico-en-Aeropuertos
Trabajo final de curso de Tableau de la certificación Citizen Data Scientist del Tec de Monterrey

Reto |
Análisis de Tráfico en Aeropuertos
Entregable final del reto
Documento editable por el participante
Objetivo:
El objetivo de este reto es poner en práctica los conocimientos adquiridos durante el módulo y
así realizar el proceso de construcción de una herramienta para el análisis de una situación
que apoyará en la toma de decisiones al generar descubrimientos, conocimiento y
conclusiones.
● Reconocimiento de los datos fuente.
● Definición de requerimientos de análisis.
● Acondicionamiento y configuración de los datos.
● Construcción e integración de visualizaciones.
● Análisis y toma de decisiones.
● Documentación final.
Introducción:
Actualmente es importante conocer que en todo proyecto de
ciencia de datos se tiene la necesidad de analizar datos. Es
conocido que la velocidad en que se generan datos es cada
vez más alta por un incremento masivo en la población, así
como las grandes capacidades tecnológicas que tenemos hoy
en día a nuestra disposición. Sin embargo, así como se
generan datos masivos a velocidades increíbles, también se
debe tener la capacidad de usarlos y analizarlos para llegar a
descubrir situaciones, oportunidades y problemas que nos
lleven a conclusiones que favorezcan a las organizaciones.
La creación de visualizaciones, dashboards e historias con los
datos nos dan la oportunidad de reducirlos en sencillas
pantallas para apoyar y agilizar el análisis de los interesados.
Para hacer que tengas una experiencia donde apliques el proceso para la generación de
información y conocimiento que apoye la toma de decisiones, llevarás a cabo el proceso que
te permitirá presentar la información relevante de una manera atractiva y conveniente usando
Dashboards e historias. Con el caso proporcionado del tráfico de pasajeros en los
aeropuertos, trabajaremos con un documento con 129889 renglones de viajeros y 23
columnas que describen el tráfico en un periodo de tres meses del año 2021 (enero, febrero y
marzo). El tráfico de pasajeros puede ser interesante para diferentes organizaciones,
inclusive para el público en general. Por tal razón tú deberás de elegir un rol para
direccionar la construcción de herramientas analíticas según los requerimientos y
necesidades del rol seleccionado.
Instrucciones:
Tomando el documento de Excel que contiene el tráfico de pasajeros que viajan por
vía aérea en algunas ciudades de los Estados Unidos, construirás herramientas de
visualización que permitan a los interesados realizar un análisis, para encontrar
información y conocimiento para llegar a conclusiones y propuestas que sean
favorables para el rol que ellos desempeñan.
Considera que los posibles analistas o usuarios a quien podrías dirigir las
visualizaciones a realizar pueden tomar los siguientes roles:
o Administradores de aeropuertos
o Administradores de alguna aerolínea
o Administradores de negocios dentro de los aeropuertos
o Público en general
Si al estar realizando la exploración de datos, antes de comenzar con la creación de
visualizaciones, encuentras otros posibles roles que puedan interesarse por un
determinado análisis puedes tomarlo.
El documento que usarás como fuente está formado por 129,890 renglones o
registros, donde cada renglón corresponde a un pasajero. Para cada pasajero se
tienen 23 columnas que describen algunas características personales y de su viaje
tales como: aerolínea por la que viaja, edad, género, horario, distancia de su vuelo,
minutos de retraso a la salida y a la llegada, si canceló.
Deberás de hacer una exploración detallada de la fuente de datos para que te
familiarices con ellos y puedas crear las visualizaciones que den más valor al usuario
dado el rol que hayas seleccionado (administrador de aerolínea, administrador de
aeropuerto, administrador de negocio que vende en el aeropuerto o público en
general).
A continuación, se describe paso a paso lo que deberás de realizar para mejores resultados:
Paso 1: Reconocimiento de la fuente de datos.
Explora cada una de las columnas que forman el documento fuente para asegurar la
comprensión de éste y de los datos que se te entregaron. Como resumen de este paso,
podrás crear una tabla (metadata) que describa cada una de las columnas (nombre, breve
descripción, tipo de dato, dominio que corresponde al número de valores diferentes y universo
o rango de valores).
Descarga el documento aquí
En este paso, también es conveniente que realices lo necesario para organizar el panel de
datos proveniente de la fuente. La creación de Folders o carpetas, la creación de jerarquías,
el orden en que aparecen los datos dentro del panel, entre otras acciones de organización
que pudieras aplicar.
Paso 2: Definición de requerimientos de análisis.
Ya que tienes una mayor familiarización con los datos dado el paso anterior, deberás de
recordar el perfil o rol a quien dirigirás el análisis para formular algunas preguntas que serán
de valor.
Si el rol elegido fue el público en general, ¿qué podrías aportar de valor para ellos? Haciendo
esta reflexión y teniendo esa familiaridad con datos, podrías formular preguntas como:
● ¿Cuáles son los meses donde hay más tráfico de viajeros?
● ¿Qué aerolíneas se caracterizan por tener más pasajeros?
Si el rol que elegiste fue un negocio que se encuentra en los aeropuertos de revistas o de
comida, podrías formular las siguientes preguntas:
● ¿Cuál es la tendencia de viajeros a través del tiempo?
● ¿Cuál es la tendencia de consumo en alimentos a través del tiempo?
En caso de haber elegido el rol de una aerolínea, te recomendamos plantearte estas
preguntas:
● ¿Qué características tienen los pasajeros que viajan en Business?
● ¿Qué destinos son los más solicitados?
Reflexiona qué preguntas le pueden interesar al usuario que hayas seleccionado. Deberás de
formular 5 preguntas para dicho rol. Puedes elegir las preguntas citadas como ejemplos, y
además deberás de plantear otras 4 preguntas adicionales.
Paso 3: Acondicionamiento y configuración de datos.
Verifica antes de iniciar el análisis si hay que hacer algún ajuste a los datos fuente, en caso de
haberlo, deberás documentarlo y realizarlo. Por ejemplo, un tipo de ajuste sería si el
contenido de una columna cambiarás algún valor por algún error o por que represente más
claramente la situación. Otro ajuste sería si deseas tener los horarios de vuelo por rango y no
por la hora exacta. También se podría requerir hacer y/o calcular un nuevo campo (métrica o
dimensión).
Normalmente los ajustes vienen como consecuencia de alguna pregunta que deseas
contestar de manera más directa y enfocada.
En este paso también debes de llevar a cabo el formato de los datos. Por ejemplo, poner el
dato como moneda, el tamaño o tipo de letra, entre otros. Esto con la finalidad de ir
preparándolos para que se vean presentables en las visualizaciones que más adelante
crearás.
Paso 4: Creación de las visualizaciones
Realiza las visualizaciones necesarias para presentar al usuario. Las visualizaciones deben
de enfocarse a contestar las preguntas que fueron planteadas en el Paso 2. Para realizar
esto, deberás de crear al menos 5 visualizaciones (gráficas y/o tablas) orientadas a dar
respuesta a los requerimientos de análisis. Utiliza el medio más conveniente para lo que
deseas transmitir y representar.
No te olvides de fortalecer tus visualizaciones utilizando filtros, colores, y un buen formato.
Utiliza marcas (marks) para hacer más profesionales las gráficas.
Paso 5: Creación de dashboard e historias
Realiza al menos dos dashboard que ayuden a resolver las preguntas de análisis. Utiliza
filtros para establecer conexiones entre las gráficas.
Realiza una Historia que dirija al analista a generar conclusiones, al menos de 4 páginas.
Paso 6: Salvando/Guardando el trabajo
Salva/guarda todo lo que has realizado en el sitio público de Tableau y toma la liga para que
más adelante la compartas. Al guardarlo hay que asegurar haber activado las opciones de
Settings para dar acceso a todo tu documento guardado.
Genera un documento PDF con todas las visualizaciones.
Genera un documento de PPT con todas tus visualizaciones.
Paso 7: Análisis, toma de decisiones y acciones
Asume tú el rol que elegiste en el inicio de este reto para responder las preguntas o
requerimientos de análisis. Cuando contestes cada pregunta es importante justificar cada
respuesta presentando la gráfica o tabla que la respalda.
Así también, listar los descubrimientos a los que llegaste al dar respuesta a cada pregunta
(conocimiento) para hacer una propuesta de negocio considerando el rol que se tomó.
Paso 8: Documentación
Documenta todo lo anterior en un Word con el siguiente contenido:
1. Introducción donde debes de mencionar el objetivo del análisis considerando el
rol que hayas seleccionado.
2. Tabla descriptiva de la Fuente de datos (desarrollada en el Paso 1)
3. Requerimientos de Análisis (desarrollado en el Paso 2)
4. Acondicionamiento y Configuración de Datos (documentar lo desarrollado en el
Paso 3)
5. Herramienta de Análisis desarrollada (en este apartado compartirás la liga del
sitio público de Tableau donde quedó guardado tu trabajo. Asegúrate que al
guardarlo actives las opciones para que se pueda apreciar todas las páginas,
dashboards e historias que creaste)
6. Resultados del Análisis y Conclusiones (desarrollado en el Paso 7)
Formato de entrega de actividad:
Para la entrega de tu solución al reto deberás subir en la plataforma 3 documentos:
● Un archivo Word (extensión .docx) que contiene lo que se describió en el PASO
8.
● Un documento PDF que se generó en el PASO 6.
● Un documento PPT que se generó en el PASO 6.
Cada documento generado que subirás a la plataforma dando clic en el botón
, lo deberás nombrar con la siguiente nomenclatura:
Reto_reporte_ APELLIDOS_NOMBRE.docx
Reto_formato1_APELLIDOS_NOMBRE.pdf
Reto_formato2_APELLIDOS_NOMBRE.pptx
Evaluación:
Tu reporte será evaluado con base al cumplimiento de los requerimientos y a su contenido, la
fecha límite de envío del archivo de tu reporte estará establecida en la plataforma.
Descarga la rúbrica de evaluación en PDF Descarga la rúbrica de evaluación en Word
Rúbrica PDF Rúbrica Word
Descarga el documento Excel Descarga las instrucciones en PDF
areolineas.xlsx Intrucciones
