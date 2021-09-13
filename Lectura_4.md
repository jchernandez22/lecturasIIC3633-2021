# Crítica: Content-Based Recommendation Systems

El paper nos presenta las distintas variantes que existen de **sistemas recomendadores basados en contenido**. 
Comienza por explicarnos la representación de los items y los problemas asociados a las características de texto libre, como lo son las descripciones de los objetos, y soluciones a estas problemátcas como el *stemming*.

Luego nos exponen la importancia de los *User Profiles* y cómo estos permiten sugerir items a partir de los historiales de compra de un usuario y reviews a objetos con los que ha interactuado.

Posteriormente, nos expone algunos modelos basados en contenido:
1. **Decission Trees y Rule Induction**, que buscan segregar los items.
2. **Nearest Neighbor Methods**: que recomendan a partir de items relacionados a previos que al usuario le atraen.
3. **Relevance Feedback and Rocchio’s Algorithm**: que instaura *implicit feedback* al modelo basado en contenido
4. **Linear Classifiers**, que buscan separar espacios multidimensionales con uso de planos 
5. y **Probabilistic Methods and Naïve Bayes** que presentan un enfoque probabilistico al problema de recomendación.

Por último, nos presenta las tendencias de los sistemas basados en contenido y algunas limitaciones de estos sistemas. 


Stemming -> agrupar palabras por su raíz o significado.

User Profiles -> 2 tipos: (1) por cada item busco los n-más cercanos o basandose en la historia de               compras/reviews

History uses:
* Return the recently viewed 
* recommend previously purchased items
* train a model
  
333 rocco como que no habla nada al respecto, menciona con suerte

Aclarar las tendencias del algoritmo me parece super bueno para tener un panorama más claro de cómo está evolucionando el área de investigación. Me parece fundamental agregar este punto en papers que estudian áreas nuevas ya que están día a día cambiando.



Juan C. Hernández S. | N° Alumno: 17642744