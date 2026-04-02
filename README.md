# Portafolio de Machine Learning y Data Science - SIAFI UNAM

Este repositorio contiene los proyectos desarrollados durante el curso propedéutico de la **Sociedad de Inteligencia Artificial de la Facultad de Ingeniería (SIAFI)** de la UNAM. 

El objetivo de este portafolio es demostrar la aplicación práctica del flujo de trabajo completo de Data Science: desde la exploración y limpieza de datos (EDA), hasta la construcción, optimización y evaluación de modelos de Machine Learning (Supervisado y No Supervisado) y Deep Learning.

## Contenido del Repositorio

El repositorio está dividido en cuatro módulos principales, ordenados por complejidad y paradigma de aprendizaje:

### 1. Regresión: Predicción de Precios de Vehículos
* **Directorio:** `01_Regresion_Precios_Vehiculos`
* **Descripción:** Desarrollo de un modelo predictivo para estimar el precio de venta de automóviles usados basado en características como kilometraje, año y tipo de combustible.
* **Técnicas aplicadas:** * Limpieza de datos y escalado con `StandardScaler`.
  * Entrenamiento y comparación de modelos de regresión.
  * Optimización de hiperparámetros.
  * Serialización del modelo final con `joblib` para futuros despliegues.

### 2. Clasificación: Reconocimiento Óptico y Análisis de Supervivencia
* **Directorio:** `02_Clasificacion_MNIST_Titanic`
* **Descripción:** Resolución de dos problemas clásicos de clasificación. El primero enfocado en visión computacional tabular (MNIST) y el segundo en datos demográficos (Titanic).
* **Técnicas aplicadas:**
  * Implementación de K-Nearest Neighbors (KNN) con búsqueda en cuadrícula (GridSearch) logrando una exactitud (accuracy) superior al 97% en el dataset MNIST.
  * Uso de Random Forest Classifier para predecir la supervivencia en el dataset Titanic, superando modelos basados en distancias debido a la naturaleza heterogénea y categórica de los datos.

### 3. Aprendizaje No Supervisado: Agrupamiento y Detección de Anomalías
* **Directorio:** `03_Aprendizaje_No_Supervisado`
* **Descripción:** Análisis de imágenes faciales (Olivetti Faces dataset) sin el uso de etiquetas, permitiendo que los algoritmos descubran la estructura subyacente de los pixeles.
* **Técnicas aplicadas:**
  * Reducción de dimensionalidad con Análisis de Componentes Principales (PCA) preservando el 99% de la varianza.
  * Agrupamiento de rostros utilizando K-Means.
  * Modelado de densidad mediante Gaussian Mixture Models (GMM) para generar nuevos rostros sintéticos y construir un sistema de detección de anomalías (imágenes rotadas o alteradas).

### 4. Deep Learning: Clasificación de Cubierta Forestal con PyTorch
* **Directorio:** `04_Redes_Neuronales_PyTorch`
* **Descripción:** Construcción de una Red Neuronal Artificial (Perceptrón Multicapa - MLP) desde cero para procesar mas de 580,000 registros cartográficos y predecir 7 tipos distintos de cubierta forestal.
* **Técnicas aplicadas:**
  * Creación de clases `Dataset` y `DataLoader` personalizadas en PyTorch.
  * Arquitectura de red neuronal profunda, funciones de activación y propagación hacia atrás (Backpropagation).
  * Entrenamiento en hardware acelerado (GPU/CUDA).
  * Análisis de estrategias de mejora (ej. propuesta de transicionar de One-Hot Encoding a capas de Embeddings para variables categóricas complejas).

## Stack Tecnológico

Los proyectos de este repositorio fueron construidos utilizando el siguiente conjunto de tecnologías:
* **Lenguaje:** Python 3
* **Análisis y Manipulación de Datos:** Pandas, NumPy
* **Machine Learning Clásico:** Scikit-Learn
* **Deep Learning:** PyTorch
* **Visualización:** Matplotlib, Seaborn
* **Entorno:** Jupyter Notebooks

## Instrucciones de Ejecución

Para replicar los resultados o explorar el código en tu entorno local:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/TuUsuario/Portafolio-Machine-Learning-SIAFI.git](https://github.com/TuUsuario/Portafolio-Machine-Learning-SIAFI.git)

## Autor

**Francisco José Coutiño Morales**
Estudiante de la Facultad de Ingeniería, UNAM. 
Miembro de la Sociedad de Inteligencia Artificial de la Facultad de Ingeniería (SIAFI).
