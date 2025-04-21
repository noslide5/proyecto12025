# NYC Taxi Fare Predictor 🚕📊

Este proyecto entrena un modelo simple de predicción de tarifas de taxi en Nueva York usando una muestra de datos reales del dataset de Kaggle: [New York City Taxi Fare Prediction](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction).

---

## 📁 Estructura del proyecto

```
nyc-taxi-fare-predictor/
├── train.csv        
├── fare.ipynb    
├── README.md               
```

---

## 📌 Objetivo

Predecir la tarifa (`fare_amount`) de un viaje en taxi a partir de datos como:

- Fecha y hora de recogida
- Coordenadas de origen y destino
- Número de pasajeros

---

## 🛠️ Tecnologías utilizadas

- Python 3.x
- Pandas
- Numpy

---

## 📈 Modelo utilizado

Se utiliza una **regresión lineal manual** para relacionar la tarifa con variables seleccionadas como la distancia del viaje y número de pasajeros.

---

## ▶️ Cómo usar el notebook

1. Asegúrate de tener instalado Python con pandas y numpy.
2. Abre el archivo `NYC_taxi_model.ipynb` con Jupyter Notebook.
3. Ejecuta las celdas paso a paso para:
   - Cargar y explorar los datos (`train.csv`)
   - Preparar las variables
   - Calcular la regresión
   - Evaluar y hacer predicciones

---

## 📚 Datos

Los datos provienen de la competencia de Kaggle:
🔗 [New York City Taxi Fare Prediction](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/data)

Solo se usó una **muestra reducida de 1.500 filas** para facilitar el procesamiento y permitir subirlo a GitHub.

---

## 📬 Contacto

Este proyecto es parte de una práctica de clase. Si tienes dudas o sugerencias, ¡no dudes en contribuir o abrir una issue!
