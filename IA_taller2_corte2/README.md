# 📊 TALLER II SEGUNDO CORTE: ANÁLISIS DE DATOS CON PYTHON

## 🏛️ Información Académica
**Universidad:** Universidad del Pacífico  
**Carrera o Programa:** Ingeniería en Sistemas  
**Asignatura:** Inteligencia Artificial (IA)

### 👥 Integrantes del Grupo:
- ANDRES STEVEN RIVAS SALAS  
- KEVIN JOSEPH VALBUENA PÉREZ  
- RUBEN DARIO BARONA  

---

## 🎯 Objetivo del Trabajo
El objetivo principal de este taller es aplicar los fundamentos de la programación en **Python** para la manipulación y análisis de datos, utilizando las librerías especializadas **NumPy** y **Pandas**.  
Específicamente, se busca:

- Demostrar el manejo eficiente de arreglos numéricos y el cálculo de medidas estadísticas fundamentales (media, moda, varianza).  
- Realizar el análisis exploratorio de datos de un conjunto de estudiantes, incluyendo filtrado de información y agrupamiento.  
- Generar visualizaciones (gráficos de barras, dispersión e histogramas) para interpretar la distribución y relación de las variables.  

---

## 💡 Descripción del Proyecto o Taller
Este proyecto se desarrolla en un entorno **Google Colab** mediante un **Notebook (.ipynb)** que aborda ejercicios prácticos divididos en cuatro bloques principales:

1. **Análisis de sesgo y curtosis de las notas de los estudiantes.**  
2. **Demostración del Teorema del Límite Central** usando una distribución uniforme.  
3. **Aplicación de distribuciones de probabilidad (exponencial y Poisson)** con ejemplos del mundo real.  
4. **Análisis de correlaciones** (positiva, negativa y nula) mediante datos sintéticos.

El archivo principal del proyecto es:  
📄 [`Taller2_segundo_corte_AI.ipynb`](https://colab.research.google.com/github/asrivasSW/AI-CLASS/blob/main/IA_taller2_corte2/Taller2_segundo_corte_AI.ipynb)

---

## 🛠️ Tecnologías Utilizadas

| Librería / Tecnología | Versión (opcional) | Función Principal |
|-----------------------|-------------------|-------------------|
| **Python** | 3.x | Lenguaje de programación principal |
| **NumPy (np)** | - | Operaciones con vectores y matrices |
| **Pandas (pd)** | - | Análisis y manipulación de datos |
| **Matplotlib (plt)** | - | Visualización de datos |
| **SciPy (stats)** | - | Funcionalidades científicas y estadísticas |
| **Seaborn (sns)** | - | Gráficos estadísticos avanzados |
| **scikit-learn** | - | Modelado estadístico y regresión lineal |

---

## 💻 Desarrollo y Explicación

### 🧪 Metodología Aplicada
El desarrollo se basó en una metodología de **Análisis Exploratorio de Datos (EDA)**, siguiendo los pasos:

1. **Preparación del Entorno:** Importación de librerías y montaje de Google Drive.  
2. **Análisis con NumPy:** Cálculos de sesgo y curtosis para evaluar simetría y forma de distribución.  
3. **Demostración del Teorema del Límite Central:** Simulación de medias muestrales con diferentes tamaños de muestra.  
4. **Distribuciones de Probabilidad:**  
   - Exponencial: tiempos de espera entre clientes.  
   - Poisson: número de correos recibidos por hora.  
5. **Visualización:** Representaciones gráficas (histogramas, dispersión y curvas teóricas).  
6. **Correlaciones:** Ejemplos de correlación positiva, negativa y nula mediante datos sintéticos.

---

## 🔎 Interpretación y Análisis de Resultados

### 📊 Medidas de Dispersión:
El **rango de las notas** es de *2.40* y la **desviación estándar** de *0.7115*, reflejando una dispersión moderada.  
Esto indica que la mayoría de las calificaciones se agrupan relativamente cerca de la **media (3.901)**, sin valores extremos significativos.

### 📈 Normalidad de los Datos:
Según el **test de Shapiro-Wilk**, el *p-valor (0.0003)* < 0.05, lo que implica que las notas **no provienen de una distribución normal**.  
El histograma muestra una **curva platicúrtica y asimétrica hacia la izquierda**, lo que confirma esta conclusión.

### 🧮 Relación Edad–Nota:
El **coeficiente de correlación (0.046)** y la **covarianza (0.099)** indican una **relación positiva débil**, es decir, no existe una relación lineal fuerte entre la edad y la nota final.  
La pendiente positiva sugiere una ligera tendencia al aumento de notas con la edad, aunque no es estadísticamente significativa.

### 🧠 Distribuciones:
- **Exponencial:** Representa los tiempos de espera entre clientes, mostrando alta frecuencia de tiempos cortos y caída progresiva.  
- **Poisson:** Modela el número de correos recibidos por hora, con una media empírica de 3.984 correos, ajustando adecuadamente la distribución esperada (p = 0.4695).

### 🔗 Correlaciones:
- **Positiva:** Horas de estudio vs calificación (r = 0.97) → A mayor estudio, mayor rendimiento.  
- **Negativa:** Temperatura vs ventas de chocolate (r = -0.96) → A mayor temperatura, menor venta.  
- **Nula:** Zapatos vendidos vs accidentes de tráfico → Sin relación aparente.

---

## ✍️ Conclusión
El desarrollo de este taller permitió **aplicar con éxito herramientas clave de la ciencia de datos en Python**, integrando el uso de librerías como **NumPy**, **Pandas**, **Matplotlib**, **SciPy** y **Scikit-Learn** para realizar un análisis estadístico completo de un conjunto de datos reales y sintéticos.

Se evidenció que:

- **NumPy** facilita el cálculo eficiente de métricas estadísticas.  
- **Pandas** optimiza la manipulación y estructuración de la información.  
- **Matplotlib / Seaborn** permiten crear visualizaciones interpretables.  
- **SciPy / Scikit-Learn** respaldan el análisis inferencial y el modelado lineal.  

En conjunto, este trabajo cumple el objetivo planteado de **aplicar técnicas de análisis, interpretación y visualización de datos**, demostrando cómo la **Inteligencia Artificial** puede integrarse al estudio del rendimiento académico y a la comprensión de fenómenos estadísticos en distintos contextos.

---

📎 **Repositorio GitHub:**  
🔗 [AI-CLASS/IA_taller2_corte2](https://github.com/asrivasSW/AI-CLASS/tree/main/IA_taller2_corte2)

