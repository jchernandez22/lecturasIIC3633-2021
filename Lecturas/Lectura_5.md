# Crítica: Combining Predictions for Accurate Recommender Systems

En el paper se presentan combinaciones de algoritmos de recomendación con el objetivo de alcanzar mayores niveles de precisión en las predicciones que podrían conseguir los modelos por sí solos.

Comienza presentándonos el método de entrenamiento y una pequeña review de los modelos que se utilizaran para realizar los *blendings* o combinaciones, aclarándonos que estos fueron elegidos a partir del *Netflix Prize*. Luego nos presenta métodos de blending, tales como *Binned linear regression* y *KNN blending*, para poseteriormente presentarnos los resultados que se obtuvieron sobre el dataset de *Netflix Prize*. Finalmente, concluye que la combinación de modelos es un método que permite superar en precisión el rendimiento que podrían conseguir los modelos por sí solos.

Me gustó la estructura del paper ya que el overview de los modelos permite contextualizarse dentro del de los algoritmos. Luego, la presentacion de los blending models me pareció bastante precisa y no se desvió en detalles que podrían distraer y sumas poco valor. 

En el momento en que presenta el blending *Neural Network* dice que el output de la red es transformado desde $[-1,1]$ a $[1,5]$ multiplicando por $3.6$ y luego sumando $3$ pero no argumenta por qué se eligieron estos estos valores. Si consideramos un output igual a $-1$, la transformación nos da $-0.6$ que no se mapea detro de un raiting válido entre 1 y 5.

Algo que me hubiese gustado es que mostraran alguna comparación entre la elección de parámetros y los rendimientos asociado, al menos para los blendings. Esto porque muchas veces se decía: "X modelo funciona mejor con Y parámetros" pero en ningún momento vi una justificación explícita del por qué. Un ejemplo de donde se realiza esto es al final de *Neural Network* donde dice "This works better compared to an exponential learnrate decay" y nada más.

Otro punto que me hubiese gustado que tocara sería la capacidad actualizar de los blendings de actualizarse cuando se cuenta con nueva data. Esto ya que tal vez no es tan conveniente como a mi parecer el trade-off entre aumento de precisión con el aumento de complejidad del modelo.

En la conclusión o resultados me hubiese gustado que se criticara más la complejidad de los modelos y el aumento en memoria de los blendings vs el uso de 1 modelo en particular. A mi parecer, el aumento de precisión fue bastante pequeño y no compensa los recursos de pasar de usar 1 modelo a 17 más.

Juan C. Hernández S. | N° Alumno: 17642744