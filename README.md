Descripción del Proyecto

Este repositorio contiene el análisis de datos, modelado predictivo y estrategias de retención para TelecomX, enfocado en reducir la tasa de cancelación de clientes (Churn).

Se realizó:
✅ ETL y limpieza avanzada de datos.
✅ Análisis exploratorio (EDA) para identificar patrones.
✅ Modelado predictivo (Regresión Logística, Random Forest, XGBoost).
✅ Estrategias de retención basadas en datos.

Hallazgos Clave
📊 Factores que más influyen en el Churn

    Contratos mensuales → +40% probabilidad de cancelación.

    Clientes nuevos (<6 meses) → 3x más riesgo de churn.

    Facturas elevadas → +26% correlación con cancelaciones.

    Fibra óptica → Alta tasa de rotación (30% correlación).
Rendimiento de Modelos Predictivos
Modelo	Precisión	Recall (Churn)	F1-Score
Regresión Logística	82%	75%	78%
Random Forest	85%	80%	82%
XGBoost	87%	83%	85%

nstalación y Ejecución
1. Entorno Virtual (Recomendado)

   python -m venv venv  
source venv/bin/activate  # Linux/Mac  
venv\Scripts\activate     # Windows

