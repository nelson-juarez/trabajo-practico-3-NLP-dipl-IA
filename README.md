Sentiment Analysis Project

Este proyecto realiza análisis de sentimiento sobre tweets utilizando diferentes modelos de Machine Learning. Tras evaluar múltiples enfoques, el modelo con mejor desempeño fue la Regresión Logística, con un 79% de accuracy en el conjunto de validación.

📌 Modelos Evaluados

Naive Bayes

Regresión Logística ✔ Mejor performance

XGBoost

TextBlob (baseline)

También se midió la similitud coseno entre centroides de cada clase, obteniendo un valor de 0.74, lo que indica que las clases son distinguibles pero cercanas semánticamente.

📊 Resultados del Modelo Final

Modelo elegido: Regresión Logística

Validation Report:

Accuracy: 0.79
Negativo → F1: 0.79
Positivo → F1: 0.80


El modelo final se guardó como:

Modelo_Sentiment.pkl
