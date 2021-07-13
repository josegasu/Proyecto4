# Proyecto4
Archivos de proyecto 4 de Modelos

En este caso, la solución a lo solicitado en el proyecto es basado en la modulación 16-QAM la cual tiene como base el análisis en 4 bits en el que a través del proceso realizado se obtiene:

![image](https://user-images.githubusercontent.com/85901426/125529202-a4eb0fd7-7c32-4dd3-aedc-0a904296245d.png)

A partir de aquí se puede observar el trabajo en una escala de bits proveniente de una imagen en formato .jpg, es claro notar que la imagen original y la que está trabajada difieren en algunos puntos que como tales, son esperables debido a la pérdida de información que puede pasar cuando se procede a la modulación. Para este caso es importante hacer notar que se crearon 3019 errores, que parecen ser altos pero a la hora de observar la imagen se queda en claro que esto es mínimo, el procesamiento de estos bits se puede hacer notar a través de estacionariedad y ergonicidad.

![image](https://user-images.githubusercontent.com/85901426/125530757-47b76691-8770-403c-852c-06f0c27353c5.png)

A la hora de ver como se comporta la modulación se tienen las realizaciones de proceso aleatorio, donde se puede observar su variación respecto al tiempo y como tal aunque se pueden ver sus proximidades de amplitud a los valores de 3 y -3 en los altos y de 1 y -1 en los bajos, lo cual hace sentido a lo que se espera en estos casos con la distribución y donde se hae notar una varianza general en el promedio de lo visto pero de esta se puede concluir que la señal contiene estacionaridad y esto es más observable con la gráfica de correlación:

![image](https://user-images.githubusercontent.com/85901426/125534104-4a1fdbf8-c616-4426-a1f3-3e2ad49dbab5.png)

Aquí se puede observar claramente la coincidencia de los períodos es muy alta, lo que indica que su valor medio de iguala, esto es característico de la estacionariedad que hay y el concepto a través de la comparación en su correlación teórica es mostrada, por lo cual se puede asegurar dicha dicha característica además de su comparativa para la ergodicidad donde se nota la relación de su promedio estadístico y temporal. 

Finalmente se observa densidad espectral de potencia.

![image](https://user-images.githubusercontent.com/85901426/125535770-11a4abb0-000d-468b-bc5f-07ad27a41277.png)

Aquí se contempla el valor máximo de potencia con respecto a la frecuencia, la cual a nivel de procesamiento es óptimo para la observación de la imagen con el aporte de cada bit por energía, en este caso se trabaja en dicha frecuencia, la cual aporta a la modulación y se puede notar que es importante considerar la frecuencia para estos casos.
