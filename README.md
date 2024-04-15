# Análisis de Datos ECOBICI

Este proyecto analiza datos históricos de viajes del sistema ECOBICI de la Ciudad de México. Se utilizan técnicas de exploración de datos, reducción de dimensionalidad y clustering para entender las tendencias y patrones de uso de bicicletas.

## Estructura del Proyecto

El proyecto se divide en dos partes principales:

- `Proyecto_parte1.ipynb`: Contiene la exploración inicial de datos y las técnicas de Reducción de Dimensionalidad y Proyecciones.
- `Proyecto_parte2.ipynb`: Se enfoca en la creación del dataset y la clusterización de los datos.

## Proyecto_parte1.ipynb

Este notebook incluye:

- Visualización inicial de los datos para comprender las características y distribuciones clave.
- Aplicación de técnicas de Reducción de Dimensionalidad, como PCA, para simplificar los datos y facilitar su visualización.
- Proyecciones de los datos para identificar posibles agrupaciones y patrones.

## Proyecto_parte2.ipynb

Este notebook abarca:

- La creación del conjunto de datos final para el análisis, incluyendo la limpieza y transformación de datos.
- Clustering de los datos utilizando varios algoritmos, incluyendo K-Means y Clustering Jerárquico.
- Evaluación de los clusters utilizando métricas como la Silueta y el Índice de Davies-Bouldin.

## Requisitos

Para ejecutar los notebooks, necesitarás las siguientes bibliotecas de Python:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Scipy

Asegúrate de instalar todas las dependencias ejecutando el siguiente comando:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
