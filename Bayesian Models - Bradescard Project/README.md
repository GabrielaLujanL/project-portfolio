
# 💳 Segmentación y Predicción de Pagos para Clientes Bradescard

Este proyecto tiene como objetivo **comprender y modelar el comportamiento de pago de los clientes de Bradescard** a partir de variables clave que reflejan patrones de uso, riesgo crediticio y morosidad.

Utilizando **Redes Bayesianas**, se identifican relaciones de dependencia entre distintos factores para **estimar la probabilidad de pago** dada cierta evidencia histórica.

El enfoque del proyecto busca **brindar flexibilidad al usuario en la toma de decisiones**, facilitando la orientación de **acciones estratégicas** enfocadas en:
- Prevención de morosidad  
- Recuperación de cartera  
- Reactivación de cuentas  

---

## 📑 Implementación

El proyecto sigue un flujo de trabajo estructurado que incluye:

- 🧹 **Limpieza y separación de datos** en cinco tipos de clientes con características particulares  
- ⚒ **Feature Engineering** para el diseño de indicadores categóricos utilizados en el modelo  
- 🕹 **Creación del modelo** mediante una Red Bayesiana Multinomial  
- 📊 **Visualización y simulación** de predicciones de pago bajo diferentes escenarios de cliente  

---

## ⚙️ Estructura de Documentos

```text
📁 Proyecto Bradescard/
├── Preprocessing/
│   └── pipeline.py
│       # Limpieza de datos y segmentaciones iniciales
│
├── Models/
│   └── ModeloBradescard_RedBayesiana_Categoricass_mm.qmd
│       # Implementación de la Red Bayesiana Multinomial y queries iniciales
│ 
├── App/
│   ├── app.R
│   │   # Aplicación Shiny para simulación de probabilidades de pago
│   └── bayesian_network_models.rds
│       # Modelo entrenado para su uso en la app
│
└── README.md
```
---

## 💻 Tecnologías Empleadas

| Herramienta        | Uso principal                         |
| ------------------ | ------------------------------------- |
| **Python**         | Backend y preprocesamiento de datos   |
| **R / RStudio**    | Implementación de la Red Bayesiana    |
| **Shiny**          | Desarrollo de la interfaz interactiva |
| **Pandas & NumPy** | Manipulación y limpieza de datos      |

---

## 👥 Miembros del equipo

- Brenda Itzelt Gómez Catzín
- Gabriela Lujan
- Gabriel Reynoso Escamilla
- Valeria Aguilar Meza
- Ariel López García

🎓 Estudiantes de Ingeniería en Ciencia de Datos y Matemáticas
