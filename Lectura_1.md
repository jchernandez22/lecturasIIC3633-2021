- Introduce CF y CBF.
- Describe tipos de CF: No Prob: Vecinos cercanos y Prob: 
- Describe cómo se realizan las predicciones para cada modelo.
- Incluye retos practicos en la implementacion de los modelos
- Presenta variaciones de enfoque de los modelos (item-based v/s user-based)
- Da juicios de valor a veces (considered the most important criteria to evaluate, p312)
- cambiar orden del paper y presentar metricas para los algoritmos propuestos
- mostrar cómo captan las cosas las metricas y compararlas con cómo se comportan los metodos en la realidad 

# Crítica: Collaborative Filtering Recommender Systems 

Este paper posee un enfoque totalmente informativo del estado del arte del Collaborative Filtering (CF) en el año 2007 que fue cuando se publicó. Los autores comienzan por presentarnos cómo funciona conceptualmente el CF, en qué campos se suele utilizar y en qué se diferencia del Content-Based Filtering. Luego, nos presenta las distintas implementaciones del CF junto con sus métodos predictivos, agrupadas en probabilísiticas y determinísitcas, los principales retos a los que se enfrentan estas implementaciones. También nos presentan los problemas que comparten todas ellas relacionadas a la recopilación de ratings como el "cold-start", y los métodos de evaluación de los CF existentes, aclarándonos que no existe ninguno predominante y que poseen distintos objetivos de evaluación. Ya para el final del paper, se nos presentan los retos a los que se enfrentaban en aquel tiempo los investigadores de esta área, las preguntas abiertas que se buscaban aclarar y también preguntas que debemos hacernos a la hora de implementar.

El paper me pareció un muy buen punto de partida para quienes nos estamos introduciendo en el Collaborative Filtering. Cumple muy bien su función de informar las distintas implementaciones y enfoques que existen y nos orienta en cuál implementación utilizar para una específica situación. 

Me hubiese gustado que las recomendaciones expuestas de una y otra implementación fuesen basadas en algunas evaluaciones experimentales ya que algunas no son fundamentadas ni en literatura ni experimentación.

Con este objetivo, un buen enfoque hubiese sido presentar primero las métricas existentes para medir la eficiencia de las implementaciones de CF, para poder utilizarlas en la evaluación de los métodos presentados. Así se hubiesen podido formalizar los juicios del tipo: "este enfoque suele dar mejores resultados para X situaciones" usando graficos en los que se presenten visualmente los distintos rendimientos de los algoritmos.

Además, se dan juicios de valor sin fundamentos como en la pagina 312 en que se expresa "(Accuracy) considered the most important criteria to evaluate" que siento que restan formalidad del documento.

Por último, la integración de preguntas abiertas me parece una valios agregación al paper ya que provocan al lector sumarse a la busqueda de respuestas a ellas. Además, las Temporal Questions nos sirven como recordatorios de qué debemos poner atención a la hora de que implementos un CF en un sistema.

Juan Cristóbal Hernández Sánchez - 17642744