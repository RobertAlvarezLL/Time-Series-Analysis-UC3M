# Time-Series-Analysis-Project-
# Análisis de Series Temporales

## Descripción del Proyecto
Este proyecto consiste en el análisis exhaustivo de una serie temporal, concretamente sobre datos de vuelos, particularmente en el contexto del tráfico en el aeropuerto y las operaciones de las aerolineas de la U.S. Airline Traffic Data, estos datos exhiben características de estacionalidad. Con el fin de comprender mejor el comportamiento de la serie y predecir futuros valores, se aplicaron técnicas de suavizado, análisis armónico, y redes neuronales en la primera parte del proyecto, seguido de un análisis completo de ARIMA, métodos de bootstrap, y modelos VAR en la segunda parte.

## Objetivos
- Analizar una serie temporal con al menos 120 observaciones, preferentemente con estacionalidad.
- Aplicar y comparar diferentes modelos y técnicas para estimar y predecir la serie temporal.
- Evaluar los modelos basándose en el error cuadrático medio (MSE) y otros criterios como el criterio de información de Akaike (AIC).

## Metodología
1. **Selección de Datos**: Los datos fueron seleccionados de [Kaggle](https://www.kaggle.com/datasets/yyxian/u-s-airline-traffic-data) por su relevancia y la presencia de estacionalidad.
2. **División de Datos**: La serie fue dividida en dos segmentos, 80% para entrenamiento y 20% para pruebas, para facilitar la validación de los modelos.
3. **Modelización**:
   - **Parte I**: Se exploraron técnicas de suavizado como los modelos de Holt-Winter, análisis armónico, y redes neuronales.
   - **Parte II**: Se realizó un análisis ARIMA completo, se aplicaron métodos de bootstrap para evaluar estimaciones e intervalos de confianza, y se exploraron los modelos VAR.

## Resultados
- Se evaluaron diversos modelos en términos de precisión predictiva y MSE. Los detalles específicos de cada modelo, incluyendo los parámetros estimados y la precisión de las predicciones, se discuten en detalle en los documentos correspondientes.
- La aplicación de técnicas avanzadas permitió una mejor comprensión de la serie temporal, destacando la importancia del análisis detallado en la predicción de futuras observaciones.

## Herramientas y Tecnologías Utilizadas
- Python
- Bibliotecas específicas para el análisis de series temporales como pandas, numpy, statsmodels, y matplotlib entre otras.
## Cómo Usar
Este repositorio contiene todos los scripts utilizados para el análisis, divididos por partes según se detalla en las tareas. Para replicar el análisis o aplicarlo a otros conjuntos de datos de series temporales, siga los comentarios detallados en cada script.

## Contribución
Este proyecto está abierto a contribuciones. Si tienes ideas para mejorar los modelos o aplicar diferentes técnicas de análisis, no dudes en crear un `pull request` o abrir un `issue`.

## Licencia
[MIT](LICENSE) - para más detalles ver el archivo LICENSE.

## Contacto
Para más información, preguntas o colaboraciones, por favor, contacta a robertoalvarezllordachs@gmail.com

---


