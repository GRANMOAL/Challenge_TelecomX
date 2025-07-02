# Challenge_TelecomX
Telecom X enfrenta una alta tasa de cancelación de clientes (churn). El propósito de este análisis es identificar patrones que expliquen por qué los clientes abandonan el servicio y aportar insights para ayudar a retenerlos.

## 🧪 Etapas del Análisis

### 1. 📥 **Extracción**
- Los datos se cargan directamente desde un archivo `.json` estructurado con información de clientes y servicios.

### 2. 🔧 **Transformación**
- Limpieza de datos: normalización de texto, conversión de variables, tratamiento de nulos.
- Creación de nuevas columnas, como `Cuentas_Diarias`.

### 3. 📊 **Análisis Exploratorio (EDA)**
- Estadísticas descriptivas
- Visualización de churn por género, contrato, método de pago, servicios contratados, etc.
- Análisis de variables numéricas: cargos, duración del contrato.
- Exploración de correlaciones entre variables clave y evasión.

### 4. 📈 **Insights y Recomendaciones**
- Clientes nuevos con contratos mensuales y sin servicios adicionales presentan mayor churn.
- Los servicios de valor agregado están correlacionados con mayor retención.
- Se recomienda impulsar contratos a largo plazo y automatizar métodos de pago.

---

## 📌 Conclusiones

Este análisis permitió identificar patrones clave de evasión que pueden ser utilizados para:
- Priorizar intervenciones en segmentos críticos.
- Diseñar campañas de retención.
- Entrenar modelos predictivos con variables significativas.
