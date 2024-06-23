# CLIPMetaphor

En este trabajo se propone la evaluación de la capacidad del modelo multimodal CLIP para interpretar metáforas en las tareas de recuperación de imágenes basada en texto e implicación de lenguaje visual sobre un conjunto de datos multimodal compuesto de metáforas textuales y visuales llamada [HAIVMet](https://arxiv.org/pdf/2305.14724).  Con estos enfoques propios del campo multimodal, se plantea la comprensión metafórica como una tarea de inferencia de relaciones semánticas y de emparejamiento para responder a la pregunta: ¿Es capaz CLIP de entender el lenguaje metafórico?

## Código

El código utilizado para toda la experimentación se encuentra en CLIPMetaphor.ipynb. Este archivo incluye la lectura y preprocesamiento de datos, el proceso de fine-tuning, y las pruebas para los modelos CLIP en las modalidades zero-shot y fine-tuned. Estos modelos se evalúan utilizando HAIVMEt en tareas de recuperación de imágenes basada en texto e implicación de lenguaje visual (VLE). El conjunto de datos utilizado para estas tareas fue creado por los autores de HAIVMet. Las particiones necesarias se pueden descargar [aquí](https://visual-metaphors-finetuned-model.s3.amazonaws.com/metviz-ve.zip) y deben ser colocadas en la carpeta "Datos".

## Datos

Esta carpeta contiene los archivos tsv, csv y las particiones de los datos necesarios para la experimentación. También se incluyen los resultados obtenidos y el análisis manual sobre las paráfrasis generadas para las metáforas del conjunto de prueba y sobre el conjunto Diferencia.
