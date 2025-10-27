# 📊 TALLER II SEGUNDO CORTE: ANÁLISIS DE DATOS CON PYTHON

## 🏛️ Información Académica
**Universidad:** Universidad del Pacífico.  
**Carrera o Programa:** Ingeniería en Sistemas.  
**Asignatura:** Inteligencia Artificial (IA)  

**Integrantes del Grupo:**
- ANDRES STEVEN RIVAS SALAS  
- KEVIN JOSEPH VALBUENA PÉREZ  
- RUBEN DARIO BARAHONA  

---

## 🎯 Objetivo del Trabajo
El objetivo principal de este taller es aplicar los fundamentos de la programación en **Python** para la manipulación y análisis de datos, utilizando las librerías especializadas **NumPy** y **Pandas**.  
Específicamente, se busca:

- Demostrar el manejo eficiente de arreglos numéricos y el cálculo de medidas estadísticas fundamentales (media, moda, varianza).  
- Realizar el análisis exploratorio de datos de un conjunto de estudiantes, incluyendo filtrado de información y agrupamiento.  
- Generar visualizaciones (gráficos de barras, dispersión e histogramas) para interpretar la distribución y relación de las variables.  

---

## 💡 Descripción del Proyecto o Taller
Este proyecto se desarrolla en un entorno **Google Colab** a través de un **Notebook (.ipynb)** que aborda ejercicios prácticos divididos en dos bloques:

1. **Manipulación de datos con NumPy.**  
2. **Análisis del dataset real de estudiantes (Dataset_Estudiantes.xlsx)** utilizando **Pandas**, **Matplotlib** y **SciPy**.  

---

## 🛠️ Tecnologías Utilizadas

| Librería / Tecnología | Versión (opcional) | Función Principal |
|------------------------|--------------------|-------------------|
| Python | 3.x | Lenguaje de programación principal. |
| NumPy (np) | - | Operaciones con vectores y matrices. |
| Pandas (pd) | - | Análisis y manipulación de datos. |
| Matplotlib (plt) | - | Visualización de datos. |
| SciPy (stats) | - | Funcionalidades científicas y estadísticas. |
| scikit-learn | - | Modelado estadístico y regresión lineal. |

---

## 💻 Desarrollo y Explicación

### 🧪 Metodología Aplicada
El desarrollo se basó en una metodología de **Análisis Exploratorio de Datos (EDA)**, siguiendo los pasos:

1. **Preparación de Entorno:** Importación de librerías y montaje de Google Drive.  
2. **Análisis con NumPy:** Cálculos matemáticos básicos y estadísticos.  
3. **Carga y Limpieza de Datos:** Lectura del archivo Excel (`Dataset_Estudiantes.xlsx`).  
4. **Estadísticas Descriptivas:** Cálculo de medidas de tendencia central y dispersión.  
5. **Transformación y Agrupación:** Agrupación por género y cálculo de promedios.  
6. **Visualización:** Gráficos para representar los resultados obtenidos.  

---

## 🔎 **Interpretación y Análisis de Resultados**

- **📊 Medidas de Dispersión:**  
  El rango de las notas es de **2.40** y la desviación estándar de **0.7115**, lo que refleja una **dispersión moderada**. Esto indica que la mayoría de las calificaciones se agrupan relativamente cerca de la **media (3.901)**, sin valores extremos que alteren significativamente la distribución.

- **📈 Normalidad de los Datos:**  
  Según el **test de Shapiro-Wilk**, el p-valor obtenido (**0.0003**) es menor a **0.05**, lo que implica que **las notas no provienen de una distribución normal**. En consecuencia, la curva observada en el histograma presenta una forma **platicúrtica y asimétrica hacia la izquierda**, reforzando el resultado estadístico.

- **🧮 Relación Edad–Nota:**  
  El coeficiente de correlación (**0.046**) y la covarianza (**0.099**) muestran una **relación positiva débil**, es decir, **no hay una relación lineal clara** entre la edad del estudiante y su nota final. La pendiente positiva de la regresión indica una leve tendencia al aumento de las notas con la edad, aunque estadísticamente poco significativa.

---

## ✍️ **Conclusión**

El desarrollo de este taller permitió **aplicar con éxito las herramientas esenciales de la ciencia de datos en Python**, integrando el uso de librerías como **NumPy**, **Pandas**, **Matplotlib**, **SciPy** y **Scikit-Learn** para realizar un análisis completo de un conjunto real de datos académicos.

Se demostró la capacidad de:
- **NumPy** para cálculos numéricos y medidas estadísticas,  
- **Pandas** para la manipulación y estructuración eficiente de datos,  
- **Matplotlib** para la creación de visualizaciones claras y analíticas, y  
- **SciPy / Scikit-Learn** para el análisis estadístico y modelado lineal.

Los resultados obtenidos proporcionan una **visión estadística integral del rendimiento académico** de los estudiantes, evidenciando que las calificaciones presentan una ligera asimetría negativa y no siguen una distribución normal.  
En conjunto, este trabajo cumple el objetivo planteado de **aplicar técnicas de análisis, interpretación y visualización de datos** dentro del contexto de la **Inteligencia Artificial aplicada al análisis educativo**.

