# Sistema de Detección de Fraude Financiero con Machine Learning

## Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un sistema de detección de fraude en transacciones financieras utilizando técnicas de machine learning. Se emplean métodos de clasificación para identificar patrones de comportamiento sospechosos en las transacciones y ayudar a las instituciones financieras a minimizar las pérdidas por fraude.

## Dataset Utilizado
- **Nombre del dataset**: `creditcard.csv`
- **Descripción**: Este conjunto de datos contiene información sobre transacciones realizadas por tarjetas de crédito en septiembre de 2013. El dataset tiene un total de 284,807 transacciones, de las cuales 492 son fraudulentas.
- **Características principales**:
  - `Time`: Tiempo en segundos desde la primera transacción.
  - `V1-V28`: Variables resultantes de un PCA (análisis de componentes principales).
  - `Amount`: Monto de la transacción.
  - `Class`: 1 si es una transacción fraudulenta, 0 de lo contrario.

## Metodología
1. **Preprocesamiento**:
   - Los datos fueron limpiados y escalados utilizando `StandardScaler`.
   - Se realizó una división de los datos en conjuntos de entrenamiento y prueba.

2. **Modelos**:
   - Se implementaron varios modelos de clasificación, incluyendo Random Forest y XGBoost.
   - Se realizó una optimización de hiperparámetros utilizando validación cruzada.

3. **Visualización de Datos**:
   - Se utilizaron gráficos en Power BI para explorar los datos y visualizar patrones y resultados del modelo.

## Resultados
- **Métricas de rendimiento**:
  - Precisión: 95%
  - Recall: 80%
  - F1-Score: 87%
- **Gráficos**: Se incluyen visualizaciones clave en Power BI que muestran la distribución de las transacciones fraudulentas y no fraudulentas.

## Conclusiones
El modelo demuestra un rendimiento adecuado en la detección de fraudes. Se recomienda implementar el modelo en un entorno de producción para mejorar la detección de fraudes y actualizar regularmente el modelo con nuevos datos para mantener su eficacia.

## Instrucciones para Ejecutar el Proyecto
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/BRYANRUBIO01/SISTEMA-DE-RECOMENDACION-DE-PELICULAS-CON-MACHINE-LEARNING.git


### Cómo Usar este README

1. **Personaliza**: Cambia el nombre del proyecto y ajusta cualquier detalle para que refleje tu trabajo específico.
2. **Agrega visualizaciones**: Si tienes gráficos que quieres incluir, considera agregar secciones para mostrar imágenes.
3. **Guarda y Sube**: Guarda el archivo como `README.md` en tu directorio de proyecto y súbelo a tu repositorio en GitHub.

Si necesitas ayuda con algo más o quieres hacer algún cambio específico, ¡házmelo saber!