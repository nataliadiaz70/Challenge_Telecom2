# Predicción de Churn en Telecomunicaciones

## 📌 Descripción
Este proyecto desarrolla modelos de Machine Learning para predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones. El objetivo es identificar patrones de abandono y proponer estrategias de retención basadas en datos.

## 🎯 Objetivos
- Preparar y limpiar los datos para modelado
- Codificar variables categóricas y normalizar variables numéricas
- Entrenar modelos de clasificación
- Evaluar el rendimiento predictivo
- Identificar factores que influyen en la cancelación
  
## 📘 Diccionario de datos

| Variable | Descripción |
|---|---|
| Churn | Indica si el cliente abandonó o no la empresa |
| gender | Género del cliente (masculino / femenino) |
| SeniorCitizen | Indica si el cliente tiene 65 años o más |
| Partner | Indica si el cliente tiene pareja |
| Dependents | Indica si el cliente tiene dependientes a cargo |
| tenure | Cantidad de meses que el cliente lleva con la empresa |
| PhoneService | Suscripción al servicio telefónico |
| MultipleLines | Suscripción a múltiples líneas telefónicas |
| InternetService | Tipo de servicio de internet contratado |
| OnlineSecurity | Servicio adicional de seguridad en línea |
| OnlineBackup | Servicio adicional de respaldo en línea |
| DeviceProtection | Servicio adicional de protección del dispositivo |
| TechSupport | Servicio adicional de soporte técnico |
| StreamingTV | Servicio de televisión por streaming |
| StreamingMovies | Servicio de streaming de películas |
| Contract | Tipo de contrato del cliente |
| PaperlessBilling | Indica si el cliente recibe la factura de forma digital |
| PaymentMethod | Método de pago utilizado |
| Charges.Monthly | Monto mensual facturado al cliente |
| Charges.Total | Monto total facturado desde el inicio del contrato |

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
