# Transformación de texto en embeddings con TensorFlow

Laboratorio académico de Procesamiento de Lenguaje Natural orientado a transformar información textual en representaciones vectoriales mediante **TF-IDF** y **embeddings entrenables con TensorFlow**.

La solución compara ambos métodos mediante similitud coseno, mapas de calor y una proyección bidimensional con análisis de componentes principales, PCA.

## Información académica

- **Estudiante:** Dairo Enrique Contreras Quintana
- **Programa:** Especialización en Inteligencia Artificial
- **CADI:** Procesamiento de Lenguaje Natural
- **Gestor de conocimiento:** Paul Alexander Díaz Montaña
- **Institución:** Universidad de Cundinamarca
- **Fecha:** Septiembre de 2026

## Objetivo

Implementar y analizar un sistema capaz de convertir textos en vectores numéricos utilizando TensorFlow, comparando los embeddings entrenados con una representación TF-IDF para reconocer sus diferencias, alcances y utilidad en tareas de similitud semántica.

## Descripción del laboratorio

El laboratorio emplea un corpus controlado de **18 textos**, distribuidos en cuatro categorías temáticas:

- Inteligencia artificial
- Procesamiento de Lenguaje Natural
- Agro
- Deporte

El procedimiento implementado comprende las siguientes etapas:

1. Definición del corpus y sus categorías.
2. Normalización, tokenización y vectorización del texto.
3. Construcción de una representación TF-IDF con unigramas y bigramas.
4. Creación de una capa `Embedding` con TensorFlow.
5. Entrenamiento mediante una tarea de clasificación temática.
6. Obtención de un embedding para cada documento.
7. Cálculo de la similitud coseno.
8. Identificación de los textos más y menos similares.
9. Generación de mapas de calor.
10. Visualización de los embeddings mediante PCA.
11. Exportación de los resultados en formatos PNG, CSV y JSON.

## Tecnologías utilizadas

- Python
- TensorFlow
- Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub
