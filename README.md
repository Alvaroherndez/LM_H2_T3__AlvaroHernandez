**Encuesta de Datos sobre el Uso de Redes Sociales**

Este proyecto consiste en una encuesta sobre el uso de redes sociales entre estudiantes de CampusFP, junto con visualizaciones de datos en forma de gráficos de barras. El objetivo es comprender mejor los hábitos y percepciones de los estudiantes en relación con las redes sociales.

### Contenido del Repositorio

El repositorio incluye los siguientes archivos:

1. **index.html**: Este archivo contiene la estructura HTML de la encuesta, una tabla para mostrar los datos de la encuesta y los gráficos de barras generados dinámicamente a partir de los datos recopilados.

2. **styles.css**: Este archivo contiene los estilos CSS que dan formato y diseño a la página HTML, incluyendo la apariencia de la tabla y los gráficos.

3. **script.js**: Este archivo contiene el código JavaScript necesario para cargar dinámicamente los datos de la encuesta en la tabla HTML, calcular los promedios para cada pregunta y generar los gráficos de barras utilizando la biblioteca Chart.js.

### Uso del Proyecto

Para utilizar este proyecto, simplemente abre el archivo `index.html` en un navegador web compatible. La página mostrará la encuesta junto con una tabla que resume los datos recopilados y los gráficos de barras que representan diferentes análisis de los datos de la encuesta.

### Características

- **Tabla de Datos**: Se ha implementado una tabla HTML para mostrar los datos recopilados de la encuesta. Esta tabla proporciona una visualización clara y detallada de las respuestas de los encuestados.

- **Gráficos de Barras**: Se han creado gráficos de barras dinámicos utilizando la biblioteca Chart.js. Estos gráficos representan diferentes análisis de los datos, como el promedio de respuestas para cada pregunta, el promedio por centro, por grado y por género.

- **Cálculos de Datos**: El código JavaScript incluye funciones para calcular los promedios de las respuestas a cada pregunta, así como los promedios por centro, por grado y por género. Estos cálculos se utilizan para generar los datos necesarios para los gráficos de barras.

- Por supuesto, aquí tienes una explicación detallada sobre la función implementada para calcular el promedio de los datos de la encuesta:

**Función para Calcular el Promedio de Respuestas**

En el código JavaScript, se ha implementado una función denominada `calculateQuestionAverages(data)`, la cual recibe como parámetro un arreglo de objetos que representan los datos de la encuesta. Esta función tiene como objetivo calcular el promedio de las respuestas para cada una de las preguntas realizadas en la encuesta.

El proceso de cálculo se realiza de la siguiente manera:

1. **Iteración por Preguntas:**
   Se itera sobre un conjunto de preguntas, representadas por los números del 1 al 5.

2. **Cálculo del Promedio:**
   Para cada pregunta, se recorre el arreglo de datos de la encuesta y se suman las respuestas correspondientes a esa pregunta para todos los estudiantes. Luego, se divide la suma total por la cantidad de estudiantes para obtener el promedio de respuestas para esa pregunta.

3. **Retorno de Resultados:**
   La función retorna un arreglo que contiene los promedios calculados para cada una de las preguntas de la encuesta.

Esta función es fundamental para el análisis de los datos de la encuesta, ya que permite obtener información relevante sobre la tendencia general de las respuestas para cada pregunta. Los promedios calculados son utilizados posteriormente para generar gráficos que visualizan de manera clara y concisa los resultados de la encuesta.

En el README del proyecto se explicará de forma detallada la implementación y el propósito de esta función, proporcionando así una comprensión completa de cómo se han analizado los datos de la encuesta.

### Requerimientos

- Un navegador web compatible con HTML5, CSS3 y JavaScript.
- Conexión a Internet (para cargar las bibliotecas Chart.js y jQuery desde CDNs).


Si deseas contribuir, simplemente realiza un fork del repositorio, implementa tus cambios en una nueva rama y envía una solicitud de extracción.

