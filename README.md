# 🚢 Predicción de Supervivencia en el Titanic (Árboles de Decisión)

Este repositorio contiene la implementación de un modelo de clasificación de Machine Learning diseñado para predecir la supervivencia de los pasajeros del Titanic. El proyecto se centra en la aplicación de un Árbol de Decisión (*Decision Tree Classifier*) utilizando variables demográficas y estructurales del viaje.

## 🧰 Stack Tecnológico

* **Lenguaje:** Python
* **Manipulación de Datos:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`
* **Visualización:** `matplotlib`, `seaborn`

## 🧠 Flujo de Trabajo del Modelo

El script sigue un flujo de trabajo estándar de ciencia de datos:

1. **Carga y Separación de Datos:** Extracción del dataset y división entre la variable objetivo `y` (Sobreviviente) y la matriz de características `X` (Clase, Género, Edad, Familiares a bordo).
2. **Entrenamiento (Training):** Configuración de un `DecisionTreeClassifier` limitando la profundidad máxima (`max_depth=3`) para evitar el sobreajuste (*overfitting*).
3. **Predicción y Evaluación:** Cálculo de la precisión del modelo frente a los datos reales.
4. **Análisis Visual:** Generación de la Matriz de Confusión y gráficas de importancia de atributos para lograr explicabilidad en el modelo (*Explainable AI*).

## 📊 Resultados y Rendimiento

* **Precisión Global (Accuracy):** **`81.51%`**
* **Evaluación de Errores:** La Matriz de Confusión demuestra una fuerte capacidad para predecir correctamente tanto los Verdaderos Positivos (supervivientes reales) como los Verdaderos Negativos (víctimas reales).
* **Importancia de Variables:** El análisis gráfico de `feature_importances_` revela cuáles son los atributos (ej. Género, Clase) que más peso tienen en la decisión algorítmica.

## ⚙️ Cómo ejecutar el proyecto

Este análisis fue desarrollado en el entorno interactivo de Google Colab, montando los datos directamente desde Google Drive. Para explorar el código, ver los árboles generados y comprobar las predicciones paso a paso, haz clic en el siguiente botón:

[[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/titanic-survival-prediction/blob/main/TU_ARCHIVO.ipynb)](https://github.com/ivanmm710x/machine-learning-titanic/blob/main/Machine_Learning_Titanic.ipynb)

