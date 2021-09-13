# Crítica: Content-Based Recommendation Systems

El paper nos presenta las distintas variantes que existen de **sistemas recomendadores basados en contenido**. Comienza por explicarnos la representación de los items y los problemas asociados a las características de texto libre y soluciones a estas problemátcas como el *stemming*.
Luego nos exponen la importancia de los *User Profiles* y cómo estos permiten sugerir items a partir de los historiales de compra y reviews  de un usuario.
Posteriormente, nos expone algunos modelos basados en contenido que poseen distintas formas de enfrentar el problema, tales como: probabilística, de clasificación lineal o a través de decission trees, y otros que agregan implicit feedback al modelo. 
Por último, nos presenta las tendencias de los sistemas basados en contenido y algunas limitaciones de estos sistemas. 

Como crítica al paper, me gustó que dejaran un espacio para observar hacia dónde se dirige el estudio de esta tecnología ya que en estas áreas de estudio nuevas todo está en un progreso rápido. 

Sin embargo, no me gustó que no compararan el *Content-Based* con *Collaborative Filtering* u otros approaches de sistemas recomendadores.

Sentí que faltó un área comparativa entre métodos basados en contenidos con alguna métrica de rendimiento ya que sentí muy general las explicaciones de los algoritmos y no me quedó claro en cuáles áreas uno es superior a otro.

Finalmente, no comprendí como los algoritmos basados en decission trees se actualizaban ya que usualmente uno crea un árbol "fijo" y lo usa para clasificar, pero en estos casos se necesita actualizar constantemente el modelo a partir de la información nueva que se instaura en la base de datos. No me quedó claro si estos modelos debían rehacerse cada cierto tiempo o si existían métodos para actualizar uno ya existente.

Juan C. Hernández S. | N° Alumno: 17642744