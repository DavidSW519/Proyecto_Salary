# Proyecto_Salary
Este proyecto fue desarrollado como trabajo final para el Diplomado de Ciencia de Datos de la UNAM


## Resumen Ejecutivo
Este proyecto utilizó un conjunto de datos de un censo realizado en 1994 para determinar si una
persona ganaba más de 50,000 dólares al año. Se aplicaron 2 modelos para analizar los datos y dar dos
enfoques de interés para este proyecto, el primero enfocado en seleccionar adecuadamente a las
personas para la situación hipotética de la distribución de apoyos económicos y el segundo en
segmentar a las personas según sus características para la creación de mejores apoyos. \
En el primer modelo llamado “Wealth Detective”, se utilizó un modelo de clasificación basado
en árboles de decisión para predecir si una persona tendría un salario mayor a 50,000 dólares. El
modelo logró una precisión del 94% en sus predicciones lo que significo una buena exclusión de
falsos positivos o lo que significa dar el apoyo a personas que no cumplían con este requerimiento.\
El segundo modelo llamado “Income Cluster Profile”, un modelo que busca segmentos en la
población, se identificaron 5 grupos diferentes en la población. Se realizaron análisis detallados de
cada grupo, considerando tanto variables continuas como discretas, para comprender sus características
distintivas. Estos insights ayudan a comprender mejor la diversidad de la población y a tomar
decisiones más informadas en la asignación de recursos y apoyos económicos.


## Justificación para el uso del aprendizaje supervisado.
El enfoque que se le dio a este trabajo, sobretodo por el perfilamiento del modelo resultante es
en el caso hipotético donde el gobierno le otorgara “Apoyos Económicos” a las personas que ganen
menos de 50k dólares al año, estos apoyos son limitados y deben otorgarse con cautela ya que el punto
es apoyar a las personas que en realidad lo necesiten. Con esto en mente lo mejor para poder predecir
de forma acertada si alguien es merecedor de dicho apoyo es un modelo de clasificación binaria.
## Justificación para el uso del aprendizaje no supervisado.
Después del tratamiento de los datos nosotros podemos observar nuestra población y
segmentarla por clusters para ver los distintos tipos de población que tenemos y complementar lo
obtenido de aprendizaje supervisado aun más enfocado a un subgrupo de la población.
