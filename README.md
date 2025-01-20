# Análisis de Sentimientos con Técnicas de NLP y Machine Learning 🧠💬

Este repositorio contiene mi proyecto final del curso **Data Science 3: Deep Learning y Redes Neuronales** de @Coderhouse. El objetivo fue analizar y clasificar comentarios como **positivos** o **negativos** utilizando técnicas de procesamiento de lenguaje natural (NLP) y modelos de Machine Learning.

## 🎯 Objetivos del Proyecto

- Procesar y limpiar un conjunto de datos textuales para prepararlos para el análisis.
- Implementar modelos de **Machine Learning** para la clasificación binaria de sentimientos.
- Evaluar el impacto de distintas técnicas de preprocesamiento en el rendimiento de los modelos.
- Explorar el uso de **redes neuronales** simples como alternativa a los modelos tradicionales.

## 🗂 Estructura del Proyecto

### 1️⃣ **Exploración y Limpieza de Datos**  
- Eliminación de ruido (stopwords, caracteres especiales, números).  
- Aplicación de técnicas de **lemmatización** y **stemming** para normalizar el texto.  
- **Tokenización** de palabras y creación de representaciones vectoriales (TF-IDF).

### 2️⃣ **Modelos Implementados**

#### 🔹 **Machine Learning Tradicional:**
- **Regresión Logística**  
- **Random Forest**  
- **XGBoost**  
- **Naive Bayes**

#### 🔹 **Deep Learning:**
- Implementación de un **Perceptrón Multicapa (MLP)** para clasificación binaria.

### 3️⃣ **Optimización del Preprocesamiento**
- Comparación entre distintas combinaciones de técnicas de limpieza y representaciones textuales.
- Ajuste de **hiperparámetros** para maximizar el **accuracy** de los modelos.

### 4️⃣ **Evaluación y Resultados**

**Métricas utilizadas:**
- **Accuracy**  
- **Precision**, **Recall**, y **F1-Score**  
- Visualización de los resultados para cada modelo.

**Resultados Principales:**
- **Regresión Logística** obtuvo el mejor rendimiento general en términos de accuracy.
- Aunque la red neuronal **MLP** alcanzó un rendimiento ligeramente inferior, demostró ser una alternativa viable con datos bien procesados.
- Las técnicas de preprocesamiento (lemmatización y stemming) impactaron significativamente en el desempeño de los modelos.

## 🛠 Tecnologías y Herramientas Utilizadas

- **Lenguaje de programación**: Python 🐍
- **Librerías principales**:
  - `scikit-learn` para modelos de Machine Learning.
  - `nltk` y `spaCy` para procesamiento de texto.
  - `matplotlib` y `seaborn` para visualización.
  - `tensorflow` y `keras` para la implementación del MLP.

🔮 Próximos Pasos
Implementar técnicas más avanzadas como Word Embeddings (GloVe, Word2Vec).
Probar modelos más complejos como Transformers (BERT, GPT).
Optimizar la red neuronal MLP con arquitecturas más profundas.


¡Espero que encuentres este proyecto interesante y útil! 😊
No olvides dar ⭐ si te gusta este repositorio.
