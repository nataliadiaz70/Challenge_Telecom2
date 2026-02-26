# Predicción de Churn en Telecomunicaciones

## 📌 Descripción
Este proyecto desarrolla modelos de Machine Learning para predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones. El objetivo es identificar patrones de abandono y proponer estrategias de retención basadas en datos.

## 🎯 Objetivos
- Preparar y limpiar los datos para modelado
- Codificar variables categóricas y normalizar variables numéricas
- Entrenar modelos de clasificación
- Evaluar el rendimiento predictivo
- Identificar factores que influyen en la cancelación

## 🧹 Preparación de datos
Se realizó:
- Eliminación de valores faltantes en variables clave
- Conversión de variables numéricas
- Codificación One-Hot de variables categóricas
- Escalado de variables numéricas

## 🤖 Modelos entrenados
- Regresión Logística
- Random Forest

## 📊 Evaluación de modelos
Métricas utilizadas:
- Accuracy
- Precision
- Recall
- F1-score
- ROC AUC
- Matriz de confusión

El modelo de Regresión Logística presentó mejor capacidad para detectar clientes que cancelan el servicio.

## 🧠 Hallazgos principales
Factores que reducen la cancelación:
- Mayor antigüedad del cliente
- Contratos de largo plazo
- Servicios adicionales (soporte técnico, seguridad)
- Mayor vinculación con el servicio

Perfil de mayor riesgo:
- Clientes nuevos
- Contratos mensuales
- Menor nivel de servicios contratados

## 💡 Conclusión
El modelo permite identificar clientes con alto riesgo de cancelación y proporciona información útil para diseñar estrategias de retención focalizadas.

## 🛠 Tecnologías utilizadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 👩‍💻 Autor
Natalia Diaz
