# Trabajo Final de Máster (Máster Universitario en Ciencia de Datos - UOC)

**"Mejoras al diagnóstico por imagen en cáncer de pecho mediante redes neuronales profundas"**
Junio de 2024

Este repositorio contiene los notebooks empleados para la fase de experimentación del Trabajo de Fin de Máster cuyo título está citado arriba. Los notebooks proceden del entorno de trabajo Google Colab. Cabe destacar que los modelos han requerido, en su mayoría, el uso de arquitecturas con GPU's, por lo que es necesario el servicio "PRO" de Colab para poder relanzarlos.

## Contenido del repositorio

- **CBIS-DDSM-CargaDatos.ipynb**: Análisis y carga de datos a tensores del dataset CBIS-DDSM.
- **CBIS-DDSM_CNN.ipynb**: Procesamiento, entrenamiento y validación de modelos CNN (Convolutional Neural Networks) para el dataset CBIS-DDSM.
- **CMMD_CNN.ipynb**: Procesamiento, entrenamiento y validación de modelos CNN (Convolutional Neural Networks) para el dataset CMMD.
- **CMMD_CargaDatos.ipynb**: Análisis y carga de datos a tensores del dataset CMMD.
- **DATASETS_UNIDOS.ipynb**: Fusión de los datasets CBIS-DDSM y CMMD para obtener un macrodataset heterogéneo que llamaremos "dataset fusión". Procesamiento, entrenamiento y validación de modelos CNN.
- **DenseArchitectures_TransferLearning.ipynb**: Entrenamiento y validación con modelos DCNN (Deep Convolutional Neural Networks) y Transfer Learning.
- **Keras_CNNs.ipynb**: Comparativa de rendimiento de las mismas arquitecturas CNN con Keras. Se compararán los tiempos con los obtenidos en el resto de notebooks.
- **Predicciones_InteligenciaColectiva.ipynb**: Pruebas y construcción de una inteligencia colectiva combinando modelos obtenidos en la experimentación.
- **Vision_Transformers.ipynb**: Pruebas con arquitecturas de Visión Transformers sobre el dataset fusión.

## Licencia

Esta obra está sujeta a una licencia de Reconocimiento-NoComercial 4.0 España de Creative Commons. Para más información visita [este enlace](https://creativecommons.org/licenses/by/4.0/).
Se publica para facilitar su acceso a otros investigadores.

