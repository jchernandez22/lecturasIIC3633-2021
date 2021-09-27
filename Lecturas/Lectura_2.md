# Crítica: MATRIX FACTORIZATION TECHNIQUES FOR RECOMMENDER SYSTEMS

El paper se centra en introducirnos el método de factorización matricial y su uso en sistemas recomendadores. Comienzan presentandonos las estrategias existentes para los sistemas recomendadores: *content filtering* y *colaborative filtering*, y se sitúa la factorización matricial dentro de los métodos más populares de *colaborative filtering*. En particular, nos mencionan su capacidad de capturar *latent factors* de los datos, los cuales son invisibles muchas veces para el ser humano, y la ventaja del metodo al permitirnos evitar matrices *sparse*.

Además, el texto ahonda en distintos puntos importantes a conocer sobre el método: regularización para evitar *overfitting*, posiblos métodos de aprendizaje para su entrenamiento como *stochastic gradient*, adición del sesgo en el modelo, entre otros; y nos presenta sus problemas como los cambios en las preferencias de los usuarios a través del tiempo y las variaciones en la confiabilidad de los inputs, junto con formas de combatir estas problemáticas. Por último, nos muestra cómo en el *Netflix Prize Competition* la factorización matricial se situó como uno de los algoritmos más efectivos y de mayor precisión en el estado del arte.

El paper me parece una muy buena guía en la comprensión de la factorización matricial ya que nos expone su funcionamiento teórico de forma clara. El hecho de que se añadan  las problemáticas a las que se puede enfrentar en la implementación lo hace un buen manual a tener si deseamos usar este método.

Algo que se pudo haber añadido serían comparaciones con el *content filtering* para conocer cuándo este método es superior y porqué. 

También preguntas que funcionen como provocaciones o que se nos presenten las direcciones en las que la investigación está avanzando para mejorar el método.

Un punto que me parece erróneo es la interpretración de la figura 2, en donde se definen los *features* latentes como "serious v/s escapist" y "males v/s female", ya que estas son extraídas de forma implícita por el algoritmo y no respaldan estas interpretaciones en bibliografía. De hecho, es muy probable una interpretación errónea.

Algo que me gustó mucho fue la adición de la figura 4 en donde se nos muestra cómo se refleja la mejoría de robustez del modelo en el rendimiento, lo cual deja muy claro si vale la pena complejizar el modelo. 

Juan Cristóbal Hernández Sánchez - 17642744