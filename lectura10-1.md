**Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. *ACM Computing Surveys* (CSUR), 52(1), 1-38**

*Parte 1*

Zhang et al., describe un artículo sobre aprendizaje profundo en sistemas de recomendación cuyo objetivo es presentar una evaluación de investigaciones de la misma temática. Ante esto, el artículo presenta un análisis del estado del arte, una clasificación de modelos de recomendación basados en aprendizaje profundo, y finalmente análisis de tendencias actuales y futuro trabajo en esta área. En específico, en esta primera parte analizaremos la introducción, una revisión conceptual de sistemas de recomendación y aprendizaje profundo y un análisis del estado del arte.  Las contribuciones de este estudio son realizar un examen sistemático de los modelos de recomendación basados en técnicas de aprendizaje profundo y proponer un esquema de clasificación para posicionar y organizar el trabajo actual; proporcionar una visión general y un resumen del estado del arte; y  discutir los desafíos e identificar las nuevas tendencias y direcciones futuras en este campo de investigación.

El artículo describe diferentes características del aprendizaje profundo en los sistemas de recomendación. En primer lugar, la omnipresencia y ubicuidad, lo cual es un aspecto relevante ya que está directamente relacionado con la vida diaria de las personas, por ejemplo, en este tópico los autores explican muy bien las aplicaciones prácticas que tiene aprendizaje profundo para sistemas de recomendación, y resaltan la ventaja de estos modelos con ejemplos cotidianos y de la academia con los que muchos lectores se sentirían identificados. Se destaca también la necesidad de mayor análisis de las investigaciones al respecto, para comprender mejor los puntos fuertes y débiles, y los escenarios de aplicación de estos modelos, lo cual es importante para los investigadores que desean buscar dónde existen espacios de profundización y problematización en esta área. 

La innovación de esta propuesta radica en su metodología, una revisión sistemática, lo cual otorgaría mayor calidad de evidencia a este artículo frente a otros análisis menos profundos en términos metodológicos. Esto, con el objetivo de identificar los problemas abiertos que actualmente limitan las aplicaciones en el mundo real y señalar las direcciones futuras en esta dimensión. Sin embargo, un aspecto contradictorio de este segmento, es que se critican investigaciones previas por ser extemporáneas en relación a los avances de este tópico, y en ese sentido, a pesar de que el presente artículo realiza un análisis de mayor profundidad, debe considerar también la naturaleza iterativa y de rápido cambio de la temática, dada su potencialidad y popularidad creciente. Ante esto, no se describe en el artículo como los autores abordan este problema. Se describe que para la recolección de información se utilizó el buscador Google Scholar, la base de datos de Web of Science (WoS) y otros sitios de conferencias de alto perfil y las palabras clave las cuales son bastante amplias y variadas respecto a tipos de algoritmos y tópico general, sin embargo, no se describe en esta parte el resto de la metodología,  como criterios de inclusión-exclusión de los artículos, y el proceso de análisis y filtro de los mismos. 

En el siguiente apartado, el artículo realiza una revisión general de los sistemas recomendadores y aprendizaje profundo, donde se definen los conceptos involucrados. Este apartado es de gran aporte al lector ya que sienta las bases de qué definición conceptual y criterios concibieron los autores para cada tópico dentro de las técnicas de aprendizaje profundo y sistemas de recomendación para realizar el análisis crítico de la literatura, también es importante destacar que cada definición se referencia adecuadamente. Luego, los autores sintetizan las fortalezas de los recomendadores basados en aprendizaje profundo, con el objetivo de que los lectores tengan claro que es lo más importante a tener en consideración en esta temática. Ante esto, se destaca la transformación no-lineal (lo que acota las opciones de análisis de predicción, ya que las comúnmente utilizadas utilizan supuestos lineales y multivariados), aprendizaje de representación (la cual hace referencia al aprendizaje de los factores explicativos subyacentes y representaciones útiles de la base utilizada), modelado de secuencias (donde tienen buenos resultados sobretodo en el área del lenguaje),  y flexibilidad (la cual se ve reflejada en los marcos de aprendizaje profundo donde se van adaptando las técnicas). Por otro lado, la interpretabilidad de las predicciones, la necesidad de información para que funcione bien y la amplia sintonización de hiperparámetros destacan como las principales limitaciones lo cual es relevante de considerar al momento de realizar pruebas de análisis con estas técnicas y se analizan en forma posterior en el artículo. 

La última sección de la primera parte, introduce las categorías de los modelos de  recomendaciones basadas en aprendizaje profundo y analiza el estado del arte respecto a prototipos de investigación y técnicas de investigación. Respecto a los modelos, se mencionan las categorías de recomendaciones con neural building blocks y las recomendaciones con modelos híbridos profundos. La primera categoría comprende ocho subcategorías cada una representando a un modelo de aprendizaje profundo, las cuales difieren respecto a su técnica, linealidad de interacción, extracción de representaciones, bases de datos con las que pueden trabajar, etc.  En cuanto a la segunda categoría, hace referencia a modelos que utilizan más de una técnica de aprendizaje profundo, destacando que puede ser una buena solución para hacer frente a la naturaleza iterativa de las necesidades en recomendación. Al respecto, se describen algunas técnicas que tienen mayor evidencia que otras en cuanto a frecuencia de publicación, pero no se profundizan en estas diferencia específicas. 

Los autores describen muy bien las aplicaciones de las recomendaciones basadas en Multilayer Perceptron (MLP) y también los modelos de recomendación basados en las redes neuronales convolucionales (CNN). Para el primero, es importante destacar que la técnica utiliza una mezcla de modelos lineales y no lineales y que también la descripción indica que se puede trabajar con retroalimentación explícita o retroalimentación implícita dependiendo del método de entrenamiento, lo cual es importante para lograr adaptabilidad en estos sistemas. La ventaja de este método es que puede resolver problemas de regresión y de clasificación y ha ido iterando en su uso, por lo que el aprendizaje es amplio y profundo y logra mejorar la precisión y la diversidad de la recomendación. Un término que me pareció interesante es el aprendizaje métrico en colaboración, el cual  utiliza como insumo el gusto de los usuarios para maximizar o disminuir la distancia entre los usuarios y sus artículos preferidos, el cual es generalmente usado en representaciones de características de los artículos, como texto, imágenes y etiquetas. Finalmente, en cuanto a CNN, se destaca que son importantes en el campo de  procesamiento de datos multimedia. Se describen ejemplos en imágenes, donde se utiliza BPR para optimizar la red y maximizar las diferencias entre etiquetas relevantes e irrelevantes. En extracción de texto, donde CNN se hace cargo del problema de data sparsity y mejora la interpretabilidad del modelo explotando las representaciones con contenido semántico en la revisión de textos, esto es muy importante ya que previamente se destacó la interpretabilidad como una limitación de los sistemas de recomendación basada en aprendizaje profundo. Para audios y videos, se ha demostrado que este puede aliviar el problema de cold start. Otro aspecto positivo, es que  se describe que CNN también se puede aplicar en filtrado colaborativo y recomendación gráfica, donde ésta última destaca por tener resultados positivos en redes sociales como pinterest para abordar tareas de recomendación a gran escala. 

Destaco que, en esta primera parte, pudimos revisar de manera muy completa los aspectos introduce los preliminares para los sistemas de recomendación y las redes neuronales profundas, las ventajas y desventajas de los modelos de recomendación basados en redes neuronales profundas y un marco  de clasificación de las técnicas y ejemplos de sus aplicaciones, ventajas y desventajas. 