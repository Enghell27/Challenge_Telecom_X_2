# Challenge_Telecom_X_2
# Análisis de Churn – TelecomX

## Descripción
Este proyecto realiza un análisis de cancelación de clientes (churn) para la compañía TelecomX. 

## Preprocesamiento
- Conversión de columnas categóricas a tipo `category`.
- Reemplazo de valores vacíos y normalización de variables numéricas.

## Modelos utilizados
- **Árbol de Decisión**: Identifica relaciones no lineales y calcula importancia de variables.  
- **K-Nearest Neighbors (KNN)**: Clasificación basada en similitud de clientes.

## Análisis de variables
- Se identificaron las variables más relevantes para la cancelación de clientes:
  1. Contrato Month-to-month
  2. Antigüedad del cliente (`tenure`)
  3. Internet de fibra óptica
  4. Falta de seguridad en línea (`OnlineSecurity_No`)
  5. Gasto diario bajo (`Cuentas.diarias`)

## Resultados de modelos
- **Árbol de Decisión**:  
  - Exactitud: 0.8041  
  - F1-score: 0.6317
- **KNN**:  
  - Exactitud: 0.7629  
  - F1-score: 0.5365

