# 🧠 Clasificador de Correos Spam con Regresión Logística

Este proyecto es un ejercicio básico de *Machine Learning* donde se implementa un modelo de clasificación utilizando **Regresión Logística** para predecir si un correo es **spam** o **no spam**, basado en características numéricas simples.

## 📂 Contenido

- `Clasificacion_Logistica_Spam.ipynb`: cuaderno de Google Colab donde se desarrolla todo el código paso a paso.
- Entrenamiento del modelo con `scikit-learn`
- Predicción de nuevos casos
- Análisis de resultados

## 📌 Objetivo

El propósito de este ejercicio es entender el flujo básico de un algoritmo de clasificación supervisada, abarcando los siguientes pasos:

1. Preparación de datos
2. División en entrenamiento y prueba
3. Entrenamiento con regresión logística
4. Predicción sobre nuevos ejemplos
5. Interpretación del resultado

## 📊 Datos de entrada

Para efectos del ejemplo, se usaron datos sintéticos con dos características por correo:
- Número de palabras ofensivas
- Número de enlaces

Cada correo es etiquetado como:
- `1`: Spam
- `0`: No spam

```python
X = [[3, 1], [1, 1], [4, 1], [0, 2], [2, 1], [1, 0], [3, 0]]
Y = [1, 0, 1, 0, 1, 0, 1]
🤖 Librerías usadas
Python 3

scikit-learn

numpy

🚀 Cómo ejecutar
Puedes abrir y ejecutar el cuaderno en Google Colab sin necesidad de instalar nada en tu computador.
