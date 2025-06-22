# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

---

## 🎯 Propósito del Análisis Realizado

Este proyecto tiene como objetivo identificar los factores que influyen en la **evasión de clientes (churn)** en Telecom X, una empresa del sector telecomunicaciones. A través del proceso ETL y análisis exploratorio, se busca:

- Comprender el perfil de clientes propensos a cancelar el servicio.
- Identificar variables relevantes para la predicción del churn.
- Sentar las bases para estrategias de retención efectivas y futuros modelos de machine learning.

---

## 📊 Ejemplos de Gráficos e Insights Obtenidos

### 📦 Distribución de Variables Numéricas

Se utilizaron gráficos tipo **boxplot** para evaluar la distribución y detectar valores atípicos:

- `Charges.Monthly`: Clientes que abandonan tienen cargos mensuales más altos.
- `Charges.Total`: Amplia dispersión, pero sin correlación directa con el churn.
- `Cuentas_Diarias`: Útil para evaluar gasto diario promedio.

### 📉 Distribución General de Evasión

Gráfico de barras horizontal que muestra claramente la proporción de clientes que evaden (`Churn = 1`) frente a los que no (`Churn = 0`).

### 🧩 Análisis por Variables Categóricas

Se exploraron variables clave usando gráficos de barras por categoría:

- `Gender`: No se observan diferencias significativas.
- `Contract`: Clientes con contratos **mes a mes** evaden más.
- `PaymentMethod`: Los métodos de pago automáticos están asociados con más evasión.
- `InternetService`: Quienes no usan protección como `TechSupport` o `OnlineSecurity` evaden más.

### 🧮 Comparación Numérica por Churn

- **Cargos mensuales (`Charges.Monthly`)**: Más altos entre quienes evaden.
- **Antigüedad (`tenure`)**: Los clientes con mayor permanencia tienden a quedarse.

✅ Conclusión
El análisis revela que los clientes con contratos a corto plazo, sin servicios adicionales de soporte o seguridad, y con cargos mensuales elevados presentan una mayor probabilidad de abandonar el servicio. Estos hallazgos permiten enfocar políticas de retención más efectivas y priorizar futuras estrategias basadas en datos. Además, el proceso de limpieza y transformación de datos deja preparado el conjunto para una posterior modelización predictiva del churn.


