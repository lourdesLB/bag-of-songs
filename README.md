# Bag of songs

___
Desarrollado por María Lourdes Linares Barrera y Pablo Reina Jiménez.   
Proyecto para la asignatura Análisis de Información no Estructurada.  
Máster en Ingeniería del Software Cloud, Datos y Gestión TI.
___

El proyecto "Bag of Songs: Extracción de Características en Señales de Audio", tiene como objetivo principal aplicar técnicas avanzadas de procesamiento de señales e Inteligencia Artificial para la distinción de géneros musicales. Mediante la utilización de un enfoque estructurado, se analizan los dominios frecuencial y temporal de piezas musicales, para generar un conjunto de datos que permita entrenar "modelos verdes" que puedan diferenciar efectivamente entre diversos tipos de música sin un coste computacional alto. Presentándose como principal alternativa frente al análisis de audio basado en el uso de espectogramas y CNNs, este enfoque combinando *feature extraction* junto con MLP o modelos de ML clásicos (SVM o RF) muestra una eficiencia elevada sin incurrir en los altos costes computacionales derivados de la alternativa existente. 

## Estructura del proyecto

La estructura del proyecto es la siguiente:
```
/codigo_y_memoria
    /ccmusic
    /ccmusic2
    /img
    1-data-preparation.ipynb
    2-features-explanaition.ipynb
    3-models-prediction.ipynb
/presentacion
    presentacion_aine_PabloRJ_MLourdesLB.pptx
    presentacion_aine_PabloRJ_MLourdesLB.pdf
    ...
````

* Carpeta `codigo_y_memoria`
    * Contiene el código/memoria en los notebooks.
    * La carpeta `/img` almacena imágenes incrustadas en el notebook.
    * Las carpetas `/ccmusic` y `/ccmusic2` contienen los conjuntos de datos (se generan durante la ejecución del código en los pasos 1) Preparación de datos y 2) Generación de características). Si quiere proceder descargando directamente los datos generados, acceda al siguiente enlace y descargue y descomprima las carpetas en el directorio indicado: [Enlace de descarga de datasets](https://drive.google.com/drive/folders/14kvMM9TbNkxPXs69Q0pHO_4XoQ0J4eUx?usp=sharing).

* Carpeta `/presentación`: la carpeta `/presentacion` contiene la presentación en formato pdf y pptx.


____ 
