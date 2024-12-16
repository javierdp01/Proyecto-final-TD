# Proyecto-final-TD
## 1. Análisis de la variable rating y categories
En este apartado se realizará un análisis de ambas variables y se tratarán de averiguar problemas o deducir correlaciones entre determinadas categorías y la variable de salida rating. La variable rating representa la puntuación de la receta por lo que es un buen parámetro para determinar si es una buena o mala receta. Primero se realizará una representación de la distribución del rating.

![Gráfica de distribución del rating](imagenestdproyecto/distrating.PNG)  

De esta primera gráfica se puede observar que la mayoría de ratings son muy positivos (entre 4-5) y que la mayoría se encuentran entre 4 y 5 indicando que o la mayoría de recetas son de muy buena calidad o que los usuarios suelen dar muy buena puntuación al calificar las recetas. A continuación se procede a representar el rating promedio por cada categoría y las categorías que aparecen con mayor frecuencia.

![Gráfica del rating promedio por categoría](imagenestdproyecto/ratingpromediocategoria.PNG)  
![](imagenestdproyecto/top10mascomunes.PNG)

En la primera gráfica se confirma lo visto anteriormente ya que la mayoría de recetas se encuentran en torno al 4. La segunda gráfica puede proporcionar información de porque algunas categorías son más famosas que otras:
- Alergias o intolerancias: Se pueden observar que en la posición 2, 3, 4 y 9 aparecen categorías relacionadas con intolerancias (cacahuete, frutos secos , soja y gluten), esta popularidad se puede deber a que muchas personas necesitan recetas sin determinados alimentos por su salud.
- Religiosidad: También determinadas categorías son populares debido a las prácticas religiosas, en concreto 'kosher' significa que esos alimentos respetan la ley judía.
- Facilidad y rapidez: Hoy en día un aspecto muy importante es la rapidez a la hora de hacer la comida por ello la categoría 'quick & easy' está tan alta.
- Dietas especiales: Aparecen categorías como comida vegetariana o pescatariana (vegetariana con pescado), esto puede determinar una aumento en la popularidad de dichas dietas.
En resumen estas categorías destacan por tendencias como la salud, rapidez o culturales.


Para poder ver una relación más concreta o una correlación entre la variable de salida y la entrada se utilizarán las categorías con mejor y peor rating, para ello se utilizan una serie de gráficos que nos permiten visualizar la salida respecto de la entrada, primero se medirán cuales son las recetas con mejor y peor rating, en concreto las 10 mejores y las 10 peores recetas. 

![Imagen 1](imagenestdproyecto/top10sinfilt.PNG)  ![Imagen 2](imagenestdproyecto/peroes10sinfilt.PNG)

Al representar esto tampoco se obtiene mucha información ya que no se puede observar alguna correlación, esto se puede deber a que no es representativo su valor ya que puede ser que solo tenga una reseña y por ello destaque o sea tan insignificate dicha categoría. Para solucionar este problema se realizará un análisis de las mejores y peores categorías con al menos 30 reseñas, gracias a esto se puede realizar un análisis más completo.

![Imagen 1](imagenestdproyecto/top10confiltro.PNG)  

En este gráfico se puede observar una correlación directa entre el rating y las categorías más populares

![Imagen 2](imagenestdproyecto/top10peoresconfilt.PNG)

E

