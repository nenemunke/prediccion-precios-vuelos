Predicción de Precios de Boletos de Avión ✈️

Proyecto de Machine Learning end-to-end para estimar el precio de boletos de avión a partir de sus características, desarrollado como caso aplicado de ciencia de datos.

🎯 Problema de negocio

Una agencia de viajes busca desarrollar un modelo predictivo capaz de estimar el precio de un boleto de avión, con el fin de anticipar tarifas, optimizar recomendaciones a clientes y apoyar la toma de decisiones comerciales.

🔧 Metodología

El proyecto sigue un flujo completo de ciencia de datos:


Análisis de calidad de datos: diagnóstico inicial, unificación de datasets y detección de inconsistencias.
Preprocesamiento y tratamiento de outliers: comparación de métodos IQR y Z-Score para preservar información valiosa.
Análisis exploratorio (EDA): análisis univariado y bivariado de las variables clave.
Análisis de correlaciones y selección de variables: identificación de los predictores más relevantes.
Ingeniería de características: transformaciones (incluida la del precio a escala logarítmica) para adecuar los datos al modelamiento.
Pipeline encapsulado: función reproducible que entrega un dataset limpio a partir de los datos originales.
Modelamiento: entrenamiento de múltiples modelos candidatos, incluyendo modelos regularizados.
Optimización de hiperparámetros: búsqueda en grilla (GridSearch) para cada modelo.
Evaluación: comparación contra un baseline usando RMSE y métricas complementarias.
Conclusiones: interpretación de resultados y valor para el negocio.


🤖 Modelos evaluados


Regresión Lineal
Modelos regularizados: Ridge, Lasso y ElasticNet
Árbol de Decisión
Random Forest


📊 Métricas

Los modelos se evaluaron principalmente con RMSE (para penalizar errores grandes), comparando su desempeño contra un baseline para medir la mejora real aportada por el modelamiento.

🛠️ Tecnologías


Python
Pandas / NumPy
Scikit-Learn
Matplotlib / Seaborn
Jupyter Notebook


📁 Contenido del repositorio


prediccion_precios_vuelos.ipynb — Notebook con el desarrollo completo del proyecto.



Proyecto desarrollado en el marco del bootcamp Data Science con Python (Academia Desafío Latam).
