# 📈 Análisis de Series de Tiempo: Pronóstico de Tasa de Desocupación

Este proyecto tiene como objetivo **analizar y pronosticar la tasa de desocupación en México** utilizando series de tiempo históricas del INEGI, con el fin de **entender tendencias y proyectar valores futuros**.

El enfoque del proyecto combina **modelos ARIMA y SARIMA** para capturar patrones estacionales y tendencias, generando pronósticos con intervalos de confianza que permiten evaluar la incertidumbre de las predicciones.

El proyecto busca **brindar herramientas analíticas para la toma de decisiones** en políticas laborales o análisis económico, destacando:

* Identificación de **patrones estacionales y tendencias** en la desocupación
* Pronósticos a **corto y mediano plazo** con intervalos de confianza
* Visualizaciones claras para **comparar datos históricos vs. predicciones**

---

## 📑 Implementación

El proyecto sigue un flujo de trabajo estructurado que incluye:

* 🧹 **Carga y limpieza de datos** del INEGI (`Tasa_de_Desocupacion_INEGI.csv`)
* ⚒ **Análisis exploratorio** y visualización de series temporales
* 🕹 **Modelado de series de tiempo** mediante ARIMA y SARIMA, incluyendo selección de parámetros y validación
* 📊 **Pronóstico con intervalos de confianza** y visualización de resultados
* 🗂 **Generación de reportes** con gráficos y tablas para documentar hallazgos

---

## ⚙️ Estructura de Documentos

```text
📁 Time Series Analysis/
├── code/
│   └── ProyectoFinal_SeriesdeTiempo.ipynb
│       # Código completo de análisis y pronósticos
│
├── data/
│   └── Tasa_de_Desocupacion_INEGI.csv
│       # Datos históricos de la tasa de desocupación
│
├── images/
│   └── (a futuro, imágenes de gráficos y visualizaciones)
│
├── Reporte_ProyectoSeriesdeTiempo.pdf
│   # Reporte detallado del proyecto con análisis y resultados
│
└── README.md
    # Documentación general del proyecto
```

---

## 💻 Tecnologías Empleadas

| Herramienta              | Uso principal                                   |
| ------------------------ | ----------------------------------------------- |
| **Python**               | Preprocesamiento y modelado de series de tiempo |
| **Pandas & NumPy**       | Manipulación de datos y cálculo de métricas     |
| **Statsmodels**          | Modelado ARIMA y SARIMA                         |
| **Matplotlib & Seaborn** | Visualización de datos históricos y pronósticos |
| **Google Colab**         | Entorno interactivo de desarrollo               |

---

## 👤 Autor

- Gabriela Lujan

🎓 Estudiante de Ingeniería en Ciencia de Datos y Matemáticas
