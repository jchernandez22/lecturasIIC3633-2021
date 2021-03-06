# Crítica: Deep Learning based Recommender System: A Survey and New Perspectives

El paper comienza por situar los sistemas recomendadores dentro de la industria y cómo estos han ayudado al consumidor elegir items de interés dentro de la basta oferta existente. Luego, nos relata cómo el deep learning (DL) ha obtenido resultados al nivel del estado del arte en distintas áreas, lo que ha llevado a que se utilicen en los RecSystems.

Procede a presentarnos enfoques y alg. de sistemas recomendadores y de deep learning por separado, describiendolos brevemente, para luego argumentar por qué resulta atractivo utilizar deep learning para recomendación y desventajas/limitaciones de su uso. Dentro de los argumentos se destaca la integración de no-linearidad a los modelos recomendadores tradicionales y su capacidad de integración de imágenes y texto libre al modelo.

Finalmente (hasta 3.4), revisa el estado del arte de los **DL Based Recomendation** clasificandolos según: (1) tipo de modelo de DL usado y (2) según tarea realizada dentro de la recomendación; y ahonda en detalles y áreas de implementación de modelos, basados en Multilayer Perceptron (MLP), Autoencoders y Convolutional Neural Networks (CNN).

Algo que me gustó del paper fue que no sólo se limita a exponer sobre los **DL Based Recomendation Models**, sino que argumenta por qué es valiosa esta combinación y qué aporta a los modelos tradicionales de Recomendación. Además, expone las limitantes  de estos modelos y las áreas en que resulta provechoso usar una componente de DL, lo cual puede ser usado si buscamos decidirnos en implementar o no uno de estos algoritmos.

Además, expone desde un principio el objetivo del paper y argumenta el por qué de la estructura de este. Esta estructura me pareció muy bien planificada ya que nos permite avanzar progresivamente en la lectura, informandonos sobre los modelos de DL y de Recomendación tradicionales por separado, para luego explicar cómo estos se pueden complementar y qué aportan los modelos de DL a los de Recomendación.

Las tablas de clasificación me parecieron muy útiles ya que se presentan muchas combinaciones de modelos que pueden confundir a la hora de elegir uno para X tarea. Además, realiza 2 clasificaciones según puntos de vista distintos, lo que facilita la elección del modelo que buscamos y aporta un carácter de "recetario" al paper que puede ser provechoso si buscamos un *handbook* de DL Based Recommenders.

En estas tablas, se agregaron varias referencias en las que se aplicaron los modelos de cada categoría en un orden numérico de las citas. Una mejora a esto podría ser haberlos ordenado según alguna métrica como **accuracy** o el nivel informativo del paper para así poder rankear los modelos según su desempeño en cada área. Esto ya que algunas categorías contaban con hasta 26 referencias, lo que puede dificultar la elección de referencias que deseemos leer.

En definitiva, me pareció un paper altamente valioso para quienes buscamos adentrarnos en los sitemas recomendadores basados en deep learning, ya que ahonda en modelos del estado del arte y específica las áreas en que éstos pueden resultar útiles de implementar. Además, para facilitar la elección de un modelo a otro, presentan una clasificación de los modelos según tarea de aplicación y modelo de DL usado, lo cual ayuda a la hora de discernir qué modelo usar para la tarea que deseamos.



