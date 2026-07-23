# Pipeline Base - Deep Learning

## Autor

Eliana Reina

## Objetivo

Este proyecto implementa un pipeline de Deep Learning utilizando PyTorch para resolver un problema de clasificación multiclase con el dataset Iris.

## Dataset

Se utilizó el dataset Iris disponible en Scikit-Learn.

El dataset contiene 150 muestras pertenecientes a tres especies:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

Las variables predictoras corresponden a medidas del sépalo y pétalo.

## Arquitectura

Red neuronal multicapa (MLP).

## Función de pérdida

CrossEntropyLoss

## Optimizador

Adam

## Learning Rate

0.001

## Métrica

Accuracy

## Resultados

La pérdida disminuye durante las épocas, indicando que el modelo aprende correctamente.

## Tecnologías utilizadas

- **Python:** lenguaje utilizado para el desarrollo del proyecto.
- **PyTorch:** framework utilizado para la construcción y entrenamiento de la red neuronal.
- **Scikit-Learn:** utilizado para la carga del dataset Iris, división de datos y normalización.
- **Pandas y NumPy:** utilizados para manipulación y procesamiento de datos.
- **Matplotlib:** utilizado para visualizar la evolución de la función de pérdida durante el entrenamiento.

## Estructura

```
pipeline-deep-learning
│
├── data
├── notebooks
├── README.md
└── requirements.txt
```

## Documentación del modelo

### Versión de PyTorch utilizada

Se utilizó PyTorch versión 2.11.0+cpu.

### Hiperparámetro learning_rate

El modelo fue entrenado utilizando un learning_rate de 0.001.

### Interpretación de la curva de pérdida

La curva de pérdida muestra una disminución progresiva durante las épocas de entrenamiento, indicando que con el modelo se logró aprender los patrones de los datos y mejorar su desempeño.

## Conclusiones

El modelo permitió clasificar las especies de flores del dataset Iris a partir de sus características físicas, aplicando un pipeline de Deep Learning con PyTorch que incluyó preparación de datos, división en conjuntos de entrenamiento y validación, normalización, conversión a tensores y entrenamiento del modelo.

Durante el entrenamiento se observó una disminución progresiva de la función de pérdida a medida que avanzaron las épocas, lo que indica que la red neuronal logró aprender patrones presentes en los datos y mejorar su capacidad de clasificación.
