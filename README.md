# LayoutLMLX_DocTR_Spanish

## Descripción del Proyecto

Este proyecto busca probar algunas tecnologias de modelos multimodales para la tarea de clasificación. A través de la combinación de LayoutXLM, un modelo multimodal que procesa imágenes, texto y la posición del texto, junto con DocTR, una herramienta de OCR que proporciona no solo el texto sino también su ubicación exacta, este proyecto permite conocer una alternativa en la clasificación y análisis de documentos.

## Características Principales

- **DocTR**: Esta herramienta de OCR es fundamental para la extracción de texto y metadatos espaciales de los documentos, lo que permite un análisis detallado y una clasificación precisa.

- **LayoutXLM**: Un modelo de inteligencia artificial que integra datos visuales y textuales para comprender la estructura y el contenido de los documentos. Su capacidad para analizar la posición del texto lo hace ideal para documentos con diseños complejos.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

- `data/`: Contiene las imágenes de documentos utilizadas para entrenar el modelo, organizadas por categorías como Biología, Ciencias de la Salud, Ciencias Sociales, entre otras.
-models/ contiene los archivos del modelo y sus complementos
    - `complementos/`: Contiene archivos JSON con información adicional para el modelo.
- `notebooks/`: Cuadernos Jupyter que documentan el proceso de preprocesamiento, entrenamiento y demostración del modelo.
  - `1.DocTR_Preprosesing.ipynb`: Detalles sobre el preprocesamiento de los documentos (OCR).
  - `2.LayoutLMLX_classification_DocTR.ipynb`: Código y explicación del proceso de entrenamiento y clasificación.
  - `3.DemoLayoutMLX.ipynb`: Una demostración interactiva de cómo funciona el modelo.

**Nota**: El modelo no se pudo subir al repositorio 

## Uso del Proyecto

Este proyecto es ideal para aquellos interesados en la clasificación automatizada y el análisis de documentos. Puede ser utilizado para mejorar los flujos de trabajo de gestión documental, automatización de oficinas y sistemas de organización de información.

