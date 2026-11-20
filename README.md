# DLY0100 - EP3 RNN y Transformer

Proyecto desarrollado para la asignatura **Deep Learning (DLY0100)**.

El objetivo es implementar y comparar modelos de traducción automática entre **Español e Inglés** utilizando arquitecturas de Deep Learning construidas con **TensorFlow/Keras**.

## Modelos implementados

El repositorio contiene dos cuadernos principales:

- **RNN / LSTM:** implementación de una arquitectura recurrente Encoder-Decoder, comparación entre RNN y LSTM y ajuste de hiperparámetros.
- **Transformer:** implementación de una arquitectura Encoder-Decoder con Multi-Head Attention y mecanismos de autoatención.

## Dataset

Se utiliza el dataset Español-Inglés de **Tatoeba**, distribuido por **ManyThings**.

Las oraciones utilizadas cumplen las siguientes condiciones:

- Entre 3 y 20 palabras.
- Máximo 100 caracteres.
- Eliminación de registros nulos y duplicados.
- Selección aleatoria de 10.000 pares para mantener tiempos de entrenamiento manejables.

Los datos se dividen en:

- 70% entrenamiento.
- 15% validación.
- 15% prueba.

## Evaluación

Los modelos son evaluados utilizando:

- Accuracy
- Precision
- Recall
- F1-Score
- Loss

También se realizan pruebas con oraciones del conjunto de prueba para analizar la calidad de las traducciones generadas.

## Estructura

```text
dly0100-ep3-rnn-transformer/
│
├── Evaluacion_3_RNN.ipynb
├── Evaluacion_3_Transformer.ipynb
├── README.md
└── dataset/
    └── spa.txt
```

## Tecnologías

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Integrantes

- Vicente Alonso Fuentes Lagos
- Marlon Gabriel Abreu Galviz
