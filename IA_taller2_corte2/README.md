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
El objetivo principal de este taller es aplicar los fundamentos de la programación en **Python** para la manipulación y análisis de datos, utilizando las librerías especializadas **NumPy**, **Pandas**, **SciPy** y **Matplotlib**.  
En particular, se busca:

- Dominar el uso de estructuras numéricas y estadísticas en NumPy.  
- Analizar y limpiar datos reales en Pandas.  
- Generar visualizaciones interpretativas (barras, dispersión, histogramas).  
- Aplicar conceptos estadísticos como sesgo, curtosis, pruebas de hipótesis y correlaciones.  
- Validar supuestos de normalidad e independencia de variables mediante pruebas estadísticas.

---

## 💡 Descripción del Proyecto o Taller
Este proyecto se desarrolla en **Google Colab** a través de un **Notebook (.ipynb)** que contiene ejercicios prácticos organizados en seis bloques temáticos:

1. **Medidas de forma:** cálculo de sesgo y curtosis en notas de estudiantes.  
2. **Teorema del Límite Central:** demostración de la normalidad muestral.  
3. **Distribuciones de probabilidad:** ejemplos reales con distribución Exponencial y Poisson.  
4. **Correlaciones:** análisis de relaciones positiva, negativa y nula con datos sintéticos.  
5. **Pruebas de normalidad:** comparación entre muestras normales y no normales (Shapiro–Wilk).  
6. **Prueba de independencia:** test Chi-cuadrado aplicado a variables categóricas.

📄 Notebook:  
🔗 [Taller2_segundo_corte_AI.ipynb](https://colab.research.google.com/github/asrivasSW/AI-CLASS/blob/main/IA_taller2_corte2/Taller2_segundo_corte_AI.ipynb)

---

## 🛠️ Tecnologías Utilizadas

| Librería / Tecnología | Versión (opcional) | Función Principal |
|-----------------------|-------------------|-------------------|
| **Python** | 3.x | Lenguaje de programación principal |
| **NumPy (np)** | - | Operaciones numéricas y manejo de arreglos |
| **Pandas (pd)** | - | Manipulación y análisis de datos estructurados |
| **Matplotlib (plt)** | - | Visualización de datos y gráficos |
| **Seaborn (sns)** | - | Gráficos estadísticos avanzados |
| **SciPy (stats)** | - | Pruebas estadísticas y distribuciones de probabilidad |
| **scikit-learn** | - | Modelado y regresión lineal |

---

## 💻 Desarrollo y Metodología Aplicada
El taller siguió una **metodología de Análisis Exploratorio de Datos (EDA)**, con las siguientes etapas:

1. **Preparación del entorno:** Importación de librerías y montaje del entorno en Google Drive.  
2. **Análisis descriptivo:** Cálculo de sesgo, curtosis, media y desviación estándar.  
3. **Distribuciones:** Simulación y ajuste de modelos Exponencial y Poisson, incluyendo pruebas de bondad de ajuste (K-S y Chi²).  
4. **Visualización:** Creación de histogramas, diagramas de dispersión y curvas teóricas.  
5. **Correlación:** Evaluación de relaciones lineales positivas, negativas y nulas entre variables.  
6. **Inferencia estadística:** Aplicación de pruebas de normalidad e independencia para validar supuestos.

---

## 🔎 Interpretación y Análisis de Resultados

### 📊 Medidas de Forma
El **sesgo (-0.246)** indica una ligera asimetría hacia la izquierda, mientras que la **curtosis (-1.143)** refleja una distribución **platicúrtica**, es decir, más aplanada que la normal.  
Esto sugiere una concentración moderada de calificaciones alrededor de la media (≈3.90).

---

### 📈 Teorema del Límite Central
A medida que el tamaño de las muestras aumenta (n=5, 30, 100), las distribuciones de las medias muestrales se aproximan a una **distribución normal**, incluso cuando la población original es uniforme.  
Esto confirma empíricamente el **Teorema del Límite Central**, base fundamental de la estadística inferencial.

---

### 📉 Distribuciones de Probabilidad
- **Exponencial (tiempos de espera entre clientes):**  
  Media empírica = 6.086, desviación estándar = 6.166.  
  Prueba K-S: p-valor = 0.8967 → no se rechaza H₀ → buen ajuste.  

- **Poisson (emails por hora):**  
  Media empírica = 3.984, p-valor (Chi²) = 0.4695 → ajuste adecuado.  

Ambos modelos representan correctamente fenómenos del mundo real: el **tiempo entre eventos** y el **conteo de sucesos discretos**.

---

### 🔗 Correlaciones
- **Positiva:** Horas de estudio vs calificación (r = 0.97) → A mayor estudio, mejor rendimiento.  
- **Negativa:** Temperatura vs ventas de chocolate (r = -0.96) → A mayor temperatura, menores ventas.  
- **Nula:** Zapatos vendidos vs accidentes → No existe relación entre las variables.

---

### 🧪 Test de Hipótesis — Prueba de Normalidad
Se generaron dos muestras:
- **X₁ (Uniforme):** p = 0.001 → no es normal.  
- **X₂ (Normal):** p = 0.0857 → sí es normal.  

El **test de Shapiro–Wilk** demuestra que esta prueba es adecuada para determinar si una muestra proviene o no de una distribución normal, requisito clave para análisis paramétricos.

---

### ⚖️ Prueba de Independencia
Se construyó una tabla de contingencia entre las variables **“Fuma”** y **“Tos Crónica”**.  
El **test Chi-cuadrado** obtuvo:  
χ² = 2.5802, p = 0.1082 → no se rechaza H₀.  

Esto indica que **no existe una asociación estadísticamente significativa** entre ambas variables, mostrando independencia entre los factores analizados.

---

## ✍️ Conclusión
El taller permitió aplicar de forma integral los conceptos de **análisis estadístico y científico de datos** mediante Python.  
A través de las librerías NumPy, Pandas, Matplotlib, Seaborn, SciPy y Scikit-learn, se abordaron desde cálculos descriptivos hasta pruebas de hipótesis, reforzando la relación entre teoría y práctica.

Se concluye que:
- Las notas de los estudiantes presentan **asimetría leve y no normalidad**.  
- El **Teorema del Límite Central** y las **distribuciones teóricas** se verifican empíricamente.  
- Las **correlaciones y pruebas inferenciales** complementan el análisis descriptivo, mostrando cómo los métodos estadísticos son esenciales en Inteligencia Artificial y ciencia de datos aplicada.

---

📎 **Repositorio GitHub:**  
🔗 [AI-CLASS/IA_taller2_corte2](https://github.com/asrivasSW/AI-CLASS/tree/main/IA_taller2_corte2)
