# DS_Interconnect_FinalProject

Tipo de proyecto: DS - Data Science

Sector: telecomunicaciones y tecnología

Tecnologías implementadas: Pandas | Sklearn <LogisticRegression> <DecisionTreeClassifier> <RandomForestClassifier> <xgboost> <catboost> | Matplotlib 

Introducción:

La empresa interconnect esta buscando implementar una solución que permita identificar de forma óptima la posible pérdida de clientes, a partir de una base de datos proporcionada por la compañía. El objetivo es maximizar la retención de usuarios ofreciendo promociones y opciones de planes alternativos a los clientes que estén considerando finalizar su contrato con la compañía.

Para lograr este objetivo se realizaron una serie de pruebas con diferentes modelos de machine learning para determinar cuál de ellos ofrece una mayor precisión a la hora de predecir la posible decisión de un usuario de finalizar su contrato.

Conclusiones:

El modelo que mejor se desempeñó fue XGB para tareas de clasificación binaria, logrando una puntuación F1 (Medida de precisión y sensibilidad a los datos) de 0,80 en los datos de prueba y sorprendentemente 0,84 en los datos de validación, lo que lo convierte en un modelo notablemente bueno.

Con este modelo se redujeron las instancias en las que el modelo predijo una rescisión del contrato cuando el cliente realmente iba a permanecer, lo que puede ayudar a evitar ofrecer códigos promocionales a usuarios que no tienen intención de cambiar de proveedor.
De manera similar, observamos que para el conjunto de pruebas, el número de verdaderos positivos disminuyó ligeramente, mientras que la detección de usuarios que cancelaron el contrato pero no fueron detectados por el modelo aumentó ligeramente.
