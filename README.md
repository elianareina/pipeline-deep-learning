# Pipeline Base - Deep Learning

## Autor

Eliana Reina

## Objetivo

Construir un pipeline reproducible de entrenamiento y validación utilizando PyTorch.

## Dataset

Iris Dataset de Scikit-Learn.

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

## Tecnologías

- Python
- PyTorch
- Scikit-Learn
- Matplotlib

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

La curva de pérdida muestra una disminución progresiva durante las épocas de entrenamiento, indicando que el modelo logró aprender los patrones de los datos y mejorar su desempeño.

## Conclusiones

Se desarrolló un pipeline de Deep Learning utilizando el dataset Iris para realizar una clasificación multiclase.

El modelo permitió clasificar las especies de flores a partir de sus características físicas, aplicando etapas de preparación de datos, división entre entrenamiento y validación, normalización y entrenamiento mediante PyTorch.

Los resultados obtenidos muestran que el modelo logra identificar patrones entre las variables de entrada y las distintas categorías, demostrando la aplicación de redes neuronales en problemas de clasificación supervisada.
