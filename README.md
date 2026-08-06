# Improving Deep Neural Networks

Colección de laboratorios prácticos sobre cómo entrenar redes neuronales de forma más estable, eficiente y reproducible. El repositorio recorre el camino desde una buena inicialización hasta optimizadores modernos y una primera implementación completa con TensorFlow.

> Parte de mi recorrido por la especialización **Deep Learning** de DeepLearning.AI. El foco está en entender cada técnica desde sus fundamentos y llevarla a código claro.

## Qué encontrarás

| Semana | Tema | Prácticas principales |
|---|---|---|
| `week1` | Inicialización y generalización | Inicialización con ceros, aleatoria y He; regularización L2; dropout; gradient checking |
| `week2` | Optimización | Mini-batches, Momentum, Adam y learning-rate decay |
| `week3` | TensorFlow | Tensores, one-hot encoding, redes con Keras y seguimiento del entrenamiento |

## Ideas clave trabajadas

- Diagnóstico de vanishing/exploding gradients.
- Reducción de overfitting con regularización y dropout.
- Validación numérica de backpropagation mediante gradient checking.
- Implementación explícita de Gradient Descent, Momentum y Adam.
- Construcción de un pipeline de entrenamiento con TensorFlow/Keras.
- Interpretación de curvas de costo y comportamiento de optimización.

## Estructura

```text
.
├── week1
│   ├── W1A1  Initialization
│   ├── W1A2  Regularization
│   └── W1A3  Gradient Checking
├── week2
│   └── W2A1  Optimization Methods
└── week3
    └── W3A1  Introduction to TensorFlow
```

Cada assignment incluye el notebook principal, utilidades, pruebas públicas y los recursos visuales necesarios para seguir el desarrollo.

## Stack

- Python y Jupyter Notebook
- NumPy, SciPy y Matplotlib
- TensorFlow / Keras
- Scikit-learn y h5py para utilidades y datasets

## Cómo explorarlo

```bash
git clone https://github.com/SantiagoPachon77/Building-Better-Deep-Neural-Networks.git
cd Building-Better-Deep-Neural-Networks

python3 -m venv .venv
source .venv/bin/activate
pip install numpy scipy matplotlib scikit-learn h5py tensorflow jupyter
jupyter lab
```

Abre los notebooks en orden semanal. Algunos ejercicios fueron diseñados para versiones específicas de TensorFlow, por lo que pequeñas adaptaciones de API pueden ser necesarias en entornos actuales.

## Enfoque del repositorio

Este es un repositorio educativo: conserva implementaciones detalladas y explícitas para hacer visible el razonamiento matemático detrás de cada técnica. Es especialmente útil como referencia para depurar entrenamiento inestable o repasar los componentes de un pipeline de deep learning.

## Autor

**Santiago Pachón** — Data Scientist interesado en sistemas de recomendación, machine learning aplicado y deep learning.

## Créditos

Material basado en los assignments de la especialización **Deep Learning** de DeepLearning.AI. Los enunciados y recursos originales pertenecen a sus respectivos autores.
