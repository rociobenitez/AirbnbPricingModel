# Índice de la Práctica

1. Preparación de los datos. División en train y test
    *  Filtrar el DataFrame para incluir solamente los registros de Madrid
    *  Limpiar Códigos Postales
    *  Dividir en train y test
2. Análisis Exploratorio
    *  Visualización de las primeras columnas del DataFrame (`.head()`)
    *  Descripción rápida de los datos (ver qué atributos son numéricos y cuáles no) (`.info()`)
    *  Ver un resumen de los atributos numéricos (`.describe()`)
    *  Número de valores faltantes por columna
    *  Histograma para analizar cada atributo numérico
    *  Análisis inicial de la correlación entre variables
    *  Análisis del dataset por grupos
        1. Datos relacionados con la información del anfitrión
        2. Datos relacionadas con la información geográfica
        3. Características directas del alojamiento
        4. Datos relacionados con la información de precios y costos adicionales
        5. Datos relacionados con las restricciones de reserva y la disponibilidad
        6. Datos relacionados con métricas de calidad y popularidad
    *  Outliers
    *  Correlación entre variables
3. Preprocesamiento
    *  Anadir nuevas variables
    *  Filtros aplicados en el análisis
    *  Primera Eliminación de Características
    *  Codificación de características de texto o categóricas
    *  Limpiar datos
        *  KNNImputer
        *  Eliminación de Características tras Modelado
    *  Escalado de características y transformación
4. Modelado
    *   Aplicar las mismas transformaciones que en train
    *   Definir una función para calcular múltiples métricas
    *   Selección de Características - Lasso
    *   Linear Regression
    *   Árbol de Decisión (DecisionTreeRegressor)
    *   Random Forest
    *   Bagging Regressor
    *   Gradient Boosting Regressor
    *   SVMs
    *   Kernel Ridge Regression
5. Conclusión

