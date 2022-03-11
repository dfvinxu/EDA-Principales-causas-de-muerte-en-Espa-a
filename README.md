 <!-- IMAGEN DEL PROYECTO -->
 <br />
 <p align="center">
   <a href="https://i.pinimg.com/originals/55/7c/ce/557cce2513704946429db193352ba95e.jpg">
     <img src="dp.png" alt="Logo" width="80" height="80">
   </a>

   <h3 align="center">EDA - Principales causas de muerte en España</h3>


 <!-- TABLA DE CONTENIDOS -->
 <details open="open">
   <summary>Tabla de contenidos</summary>
   <ol>
     <li>
       <a href="#sobre-el-proyecto">Sobre el proyecto</a>
       <ul>
         <li><a href="#librerias-utilizadas">Librerias utilizadas</a></li>
       </ul>
     </li>
     <li>
       <a href="#resumen-del-proceso-de-trabajo-con-datos">Resumen del proceso de trabajo con datos</a>
       <ul>
         <li><a href="#obtención-y-limpieza-de-datos">Obtención y limpieza de datos</a></li>
         <li><a href="#elbaoración-de-los-grágicos">Elaboración de los gráficos</a></li>
       </ul>
     </li>
     <li><a href="#license">License</a></li>
   </ol>
 </details>



 <!-- SOBRE EL PROYECTO -->
### Sobre el proyecto

Este proyecto se centra en el análisis de los datos sobre las diferentes causas de muerte en España durante un periodo de 40 años. La finalidad del proyecto es realizar una comparativa de las principales causas. Todos los datos utilizados para la realización del mismo han sido obtenidos directamente de la página oficial del <a href="https://www.ine.es/index.htm">Instituto Nacional de Estadística</a> (INE).

 Evolución de las muertes totales en España durante el periodo 1980-2020.

 [![Product1][product-screenshot1]](https://github.com/simranjeet97/SriLanka-Car-Price_EDA-and-DASHboard)

 ### Librerias utilizadas

 Para el tratamiento de los datos y obtención de los gráficos, he utilizado las siguientes librerías: - 
 * [Pandas](https://pandas.pydata.org/)
 * [Numpy](https://numpy.org/)
 * [Seaborn](https://seaborn.pydata.org/)
 * [Matplotlib](https://matplotlib.org/)

### Resumen del proceso de trabajo con datos

#### Obtención y limpieza de datos

Para la realización de este proyecto he utilizado cuatro datasets diferentes que me he descargado de la base de datos del INE. En los cuatro datasets los datos estan clasificados por causas globales, sexo, edad y año.Una breve descripción de los archivos .csv obtenidos sería la siguiente:

- Primer dataset: muestra de todas las muertes en España para el periodo 1980-2020. 
- Segundo dataset: muestra los datos de las muertes causadas por enfermedades del sistema circulatorio.
- Tercer dataset: muestra los datos de las muertes causadas por tumores malignos.
- Cuarto dataset: muestra los datos de las muertes causadas por enfermedades infecciosas y parasitarias.

Una vez leído el fichero .csv en Python, el proceso ha sido similar en los cuatro casos:

- Eliminar aquellas columnas que no iban a resultar útiles (como la de sexo y la de edad, ya que en este proyecto me he basado en datos totales de la población, sin distinción por sexo ni edad).
- 
