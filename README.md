# ID-DE-ESTADO-DE-SIEMBRA
Proyecto de ciencia de datos y percepción remota que utiliza imágenes satelitales para analizar el estatus de actividad agrícola y generar estadísticas agrícolas automatizadas.

# Introducción
La agricultura es uno de los pilares fundamentales de la economía y la sociedad, ya que provee de alimentos y materias primas para la industria. Sin embargo, la generación de estadísticas agrícolas precisas y actualizadas puede ser un desafío debido a la necesidad de recopilar datos en campo de manera regular, lo que resulta costoso en términos de tiempo y recursos.

Para abordar este problema, se desarrolló un proyecto de ciencia de datos y percepción remota que utiliza imágenes satelitales para analizar el estatus de actividad agrícola y generar estadísticas agrícolas automatizadas. Esto permite obtener información precisa y actualizada sin la necesidad de recopilar datos en campo de manera constante, lo que resulta en una reducción significativa de costos.

# Objetivo
El objetivo de este proyecto es ayudar a los gobiernos a mejorar el análisis de estatus de actividad agrícola a través del uso de la tecnología de ciencia de datos y percepción remota. Se proporcionarán estadísticas agrícolas precisas y detalladas que ayuden a tomar decisiones informadas y oportunas.

# Metodología
Se recopilaron imágenes satelitales mensuales de una zona agrícola de interés. Para procesar estas imágenes, se extrajeron los valores de diferentes bandas espectrales, como el rojo, el verde y el infrarrojo cercano. A partir de estas bandas, se generaron índices de vegetación como el NDVI y NDMI utilizando fórmulas estándar en el campo de la percepción remota.

Luego, se realizó una clasificación supervisada para identificar áreas de sembradas, preparadas para siembra y parcelas sin actividad agrícola. 

Se utilizó una muestra de entrenamiento para entrenar y validar un modelo de clasificación supervisada basado en árboles de decisión. Este modelo se ajustó y mejoró iterativamente hasta obtener una precisión satisfactoria en la clasificación de las áreas de cultivo y no cultivo.

Una vez completada la clasificación, se procedió a realizar un análisis exploratorio de los datos obtenidos en Google Colab. Se evaluaron los patrones y tendencias en el estatus de actividad agrícola en la zona de interés. Se llevaron a cabo diversos análisis estadísticos y se identificaron los indicadores clave que podrían utilizarse para modelar el estatus de actividad agrícola en la zona.

Para modelar el estatus de actividad agrícola, se exploraron diferentes modelos estadísticos, incluyendo regresiones lineales, modelos de regresión logística y modelos basados en árboles de decisión. Se evaluó la calidad de los modelos mediante validación cruzada y se seleccionó el modelo más adecuado.

Por último, se utilizó el modelo de árbol de decisión generado previamente para clasificar automáticamente las imágenes satelitales más recientes. Se implementó un flujo de trabajo automatizado utilizando la plataforma Google Earth Engine para clasificar las imágenes satelitales y generar estadísticas agrícolas actualizadas de forma periódica.

# Resultados
Durante el análisis exploratorio de los datos, se observó que las distintas clases de cultivos presentaban respuestas espectrales similares en ciertas bandas en determinadas épocas del año. Esto fue crucial para la selección y extracción de características relevantes de las imágenes satelitales y la generación del modelo de clasificación supervisada. La identificación de estas características específicas permitió la creación de un modelo de alta precisión, lo que llevó a una mejora significativa en la eficiencia y la productividad de la agricultura a través de la aplicación de ciencia de datos y percepción remota.

Los resultados obtenidos mostraron una precisión del 84.03% en la clasificación automatizada del estatus de actividad agrícola, lo que indica un alto nivel de confiabilidad en el modelo generado.

# Conclusiones
La generación de estadísticas agrícolas precisas y actualizadas permite una mejor planificación y toma de decisiones informada en la agricultura, lo que puede llevar a una mayor eficiencia y productividad en el sector.

La aplicación desarrollada en este proyecto ofrece una solución automatizada para el análisis del estado de actividad agrícola, lo que ahorra tiempo y recursos valiosos. 

La capacidad para actualizar regularmente los datos de la aplicación en tiempo real permite una toma de decisiones oportuna y efectiva por parte de los gobiernos locales.

En última instancia, la aplicación de la ciencia de datos y la percepción remota para el análisis del estado de actividad agrícola tiene el potencial de mejorar significativamente la productividad y eficiencia agrícola, lo que puede traducirse en beneficios económicos y sociales para las comunidades locales.
