# 📊 Análisis de Ventas con Cadenas de Markov

Este proyecto tiene como objetivo **analizar y modelar la evolución de ventas de productos** utilizando **cadenas de Markov**, con el fin de **predecir comportamientos futuros y optimizar estrategias comerciales**.

A partir de los datos proporcionados por **Laboratorios PiSA**, se desarrollaron **matrices de transición que representan las probabilidades de que un producto pase de un estado activo a inactivo** y viceversa. Además, se identificaron **cadenas ergódicas y no ergódicas**, lo que permite evaluar la estabilidad de ventas a largo plazo.

El enfoque del proyecto busca **brindar herramientas para la toma de decisiones estratégicas**, incluyendo:

* Optimización de la **activación y desactivación de productos**
* Predicción de ventas futuras
* Evaluación de la **retención y lealtad del cliente**
* Cálculo de **Customer Lifetime Value (CLV)** para estrategias de retención

---

## 📑 Implementación

El proyecto sigue un flujo de trabajo estructurado que incluye:

* 🧹 **Limpieza y preprocesamiento de datos**, incluyendo filtrado por fechas y agrupación de ventas mensuales por producto
* ⚒ **Cálculo de estados y transiciones**, donde cada producto se clasifica como activo o inactivo según sus ventas
* 🕹 **Construcción de matrices de transición y normalización**, para modelar probabilidades de cambio de estado
* 📊 **Identificación de cadenas ergódicas y análisis de convergencia**, evaluando estabilidad a largo plazo
* 📈 **Visualización de resultados**, distribuciones de probabilidades y evolución de estados
* 🖥 **Desarrollo de una interfaz Shiny**, para explorar matrices de transición y distribuciones por producto

---

## ⚙️ Estructura de Documentos

```text
📁 Markov Chains Sales Analysis/
├── code/
│   └── Entregable final.qmd
│       # Código completo de análisis y cálculos de cadenas de Markov
│
├── Entregable Final.pdf
│   # Reporte final del proyecto con análisis detallado y resultados
│
└── README.md
    # Documentación general del proyecto
```

> Nota: Los datos utilizados en este proyecto son confidenciales y no se incluyen en el repositorio.

---

## 💻 Tecnologías Empleadas

| Herramienta       | Uso principal                                  |
| ----------------- | ---------------------------------------------- |
| **R / RStudio**   | Preprocesamiento de datos y modelado de Markov |
| **Shiny**         | Desarrollo de interfaz interactiva             |
| **dplyr & tidyr** | Limpieza y manipulación de datos               |
| **ggplot2**       | Visualización de distribuciones y tendencias   |
| **expm**          | Cálculo de matrices de transición a n pasos    |

---

## 👥 Miembros del equipo

* Rebeca Koch Torres
* Brenda Itzelt Gómez Catzín
* Gabriela Lujan
* María F. Gamboa Martínez
* Andrea Ruía Álvarez

🎓 Estudiantes de Ingeniería en Ciencia de Datos y Matemáticas

