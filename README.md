# Laboratorio 3 Familias de Malware

El archivo `lab3.ipynb` es el cuaderno principal del laboratorio. Ahi esta todo el proceso, desde la extraccion de caracteristicas hasta el analisis final y las respuestas. Tambien se incluye `lab3.pdf`, que es la version en PDF del cuaderno para revisarlo mas facil para ver.

La carpeta `salidasLab3` guarda todos los resultados generados. En `graficas` estan las visualizaciones principales, como el metodo del codo, Silhouette, los clusters en 2D y la grafica 2D de los embeddings de Gemini. En `grafos` estan los grafos en formato `.png` , tanto del conjunto completo como de cada familia, usando strings y llamadas a funciones con distintos umbrales. En `tablas` se guardan el dataset final, los resultados de similitud, los resumenes y la comparacion de caracteristicas. En esa misma carpeta tambien quedaron los archivos de embeddings de Gemini. Se guardaron asi porque Gemini tiene limite de cuota y fue necesario ir guardando el progreso para poder continuar despues sin empezar desde cero.

El reporte escrito esta dentro de `lab3.ipynb` al final del cuaderno, donde se responden las preguntas y se realiza la comparacion de los modelos.
