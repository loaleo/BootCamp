# BootCamp


# 📊 Análisis y Predicción de Aspiraciones de Carrera de Gen Z

Este proyecto analiza datos sobre las aspiraciones de carrera de la generación Z, utilizando técnicas de limpieza, visualización y modelos de aprendizaje automático para la predicción.

## 🚀 Instalación

Antes de ejecutar el código, instala las bibliotecas necesarias:

```bash
pip install pandas numpy tensorflow matplotlib seaborn nltk scikit-learn wordcloud flask pyngrok

## 🚀 Descripción de proyecto

El código realiza las siguientes tareas:

-Carga de Datos: Obtiene el dataset desde Google Drive.

-Preprocesamiento:
Renombramiento de columnas.
Conversión de variables categóricas.
Eliminación de valores nulos.

-Análisis y Visualización:
Generación de histogramas con seaborn.
Identificación de distribuciones de datos.

-Entrenamiento de Modelos:
Uso de RandomForestClassifier para la predicción.
Evaluación con métricas de precisión y matriz de confusión.

-Afinación de Modelos:
Aplicación de GridSearchCV para mejorar hiperparámetros.

-Despliegue de API REST:
Implementación con Flask para recibir datos de entrada y devolver predicciones.
Uso de ngrok para crear un túnel y hacer la API accesible públicamente.


## 🛠 Ejecución
Para iniciar el análisis y la API, sigue estos pasos:

python UDD_Proyecto_M7.ipynb

Si quieres probar la API, envía una solicitud POST a:
curl -X POST "http://<URL_PUBLICA>/predict" -H "Content-Type: application/json" -d '{"features": [valor1, valor2, valor3] }'


## 📊 Visualización
El código incluye gráficos generados con seaborn y matplotlib para explorar la distribución de las respuestas.

## 🤝 Contribución
Si deseas mejorar el código, sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b mejora-visualizacion).
Realiza cambios y haz commit (git commit -m "Optimización del modelo").
Haz push (git push origin mejora-visualizacion).
Abre un pull request.


## 📜 Licencia
Este proyecto está bajo la licencia MIT.





