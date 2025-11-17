# 🏡 **TALLER I – CORTE III**  
## **ANÁLISIS EXPLORATORIO DE DATOS (EDA) DE VIVIENDAS**
---

## 🏛️ **Información Académica**

- **Universidad:** Universidad del Pacifico 
- **Carrera:** Ingeniería en Sistemas  
- **Asignatura:** Inteligencia Artificial (IA)  
- **Integrante:**  
  - 🧑‍🎓 *Andrés Steven Rivas Salas*

---

## 🎯 **Objetivo del Trabajo**

El propósito de este taller es aplicar técnicas de **Análisis Exploratorio de Datos (EDA)** para comprender el comportamiento y las características de los precios de viviendas en un dataset obtenido desde Kaggle.

### Objetivos específicos:

- Descargar y cargar un *dataset* real de precios de viviendas.  
- Identificar los **tipos de datos** presentes (categóricos y numéricos).  
- Analizar medidas estadísticas como **media**, **mediana**, **desviación estándar**, **cuartiles** e **IQR**.  
- Visualizar la información mediante **histogramas**, **boxplots** y **gráficos de dispersión**.  
- Detectar **asimetrías**, **correlaciones** y **valores atípicos** relevantes.  

---

## 💡 **Descripción del Proyecto**

Este proyecto fue desarrollado en **Google Colab** utilizando Python y sus principales librerías de análisis de datos.  
El dataset utilizado proviene de Kaggle:  
📦 `kainatjamil12/housing`

### El proceso incluyó:

1. Descarga y carga del archivo `Housing.csv`.  
2. Exploración y clasificación de los tipos de datos.  
3. Cálculo de las métricas estadísticas principales.  
4. Agrupación de la variable `area` según rangos definidos.  
5. Análisis de variables clave como `price`, `area`, `furnishingstatus` y `bedrooms`.  
6. Identificación de *outliers* mediante el método de **Rango Intercuartil (IQR)**.

---

## 🛠️ **Tecnologías Utilizadas**

| Tecnología | Función |
|-----------|---------|
| 🐍 **Python 3.x** | Lenguaje principal de programación |
| 📊 **Pandas** | Manipulación y análisis de datos |
| 📈 **Matplotlib** | Gráficos estáticos (histogramas, boxplots) |
| 🌈 **Seaborn** | Visualización estadística avanzada |
| 📥 **KaggleHub** | Descarga del dataset desde Kaggle |
| 📂 **OS** | Manejo del sistema de archivos |

---

## 💻 **Desarrollo y Metodología**

### 🧪 **Metodología EDA (Exploratory Data Analysis)**

El flujo del análisis fue el siguiente:

---

### **1️⃣ Carga y Limpieza del Dataset**

- Se cargó `Housing.csv` en un DataFrame.  
- Se inspeccionaron las columnas, identificando:  
  - **Variables numéricas:** `price`, `area`, `bedrooms`, `bathrooms`, `stories`, `parking`.  
  - **Variables categóricas:** `mainroad`, `guestroom`, `furnishingstatus`, etc.

---

### **2️⃣ Medidas de Tendencia Central y Dispersión**

Los cálculos principales fueron:

- **Media de price:** ≈ 4,766,729  
- **Mediana de price:** 4,340,000  
- **Desviación estándar de price:** ≈ 1,870,440  

Esto evidencia **asimetría a la derecha**, ya que la media > mediana.

Se calcularon cuartiles e IQR:

- **IQR:** 2,310,000  
- **Límite superior de outliers:** 9,205,000  

Cualquier vivienda por encima de este valor se considera atípica (*outlier*).

---

### **3️⃣ Análisis de Outliers**

A través de boxplots se identificó la presencia de viviendas:
- Con precios extremadamente altos  
- Con áreas mayores a lo común  
- No necesariamente relacionadas con mayor número de habitaciones  

---

### **4️⃣ Correlaciones y Relaciones Entre Variables**

#### 📌 **Precio vs Área**
- Alta correlación positiva.  
- A mayor área, mayor precio.  
- Confirmado mediante scatterplot y jointplot.

#### 🛏️ **Habitaciones (Bedrooms)**
- Las casas con más habitaciones tienden a ser más grandes y más costosas.  
- Sin embargo, **hay casas costosas con pocas habitaciones**, demostrando que no es el factor más determinante.

#### 🏷️ **Estado de Amueblamiento (Furnishing Status)**
- **Furnished:** mayor dispersión y presencia de viviendas de lujo.  
- **Unfurnished:** más homogéneas y de menor precio.  
- **Semi-furnished:** casos mixtos y algunas casas de alto valor.  

#### 🧱 **Categorías de Área**
Al clasificar el área en grupos (‘Muy pequeña’, ‘Pequeña’, ‘Media’, ‘Grande’, ‘Muy grande’):
- Se observa un aumento claro de precios según el tamaño del área.  

---

## 🔎 **Interpretación General**

### 📈 Hallazgos principales:

- Las distribuciones de área y precio presentan **asimetría positiva**.  
- Existen numerosos **outliers**, especialmente en precios altos.  
- El área es un fuerte predictor del precio.  
- El estado del amueblamiento NO siempre determina el valor final.  
- Las variables categóricas aportan información útil, pero no son decisivas por sí solas.

---

## 💡 **Recomendación de Vivienda (Calidad–Precio)**

Dentro del grupo de viviendas **de área pequeña**, la mejor opción calidad-precio es:

✔️ **Semi-amueblada**  
✔️ **Sin parqueadero**  
✔️ **Hasta tres habitaciones**

Esto proporciona buen equilibrio entre comodidad y precio accesible.

---

## ✍️ **Conclusión Final**

Este taller permitió aplicar herramientas esenciales de **Análisis Exploratorio de Datos**, utilizando Python y librerías especializadas para comprender el comportamiento del mercado inmobiliario dentro del dataset.

Los análisis realizados permitieron:

- Identificar asimetrías en los datos  
- Detectar valores atípicos  
- Determinar correlaciones clave  
- Comprender cómo características como tamaño y amueblamiento impactan el precio  

Este trabajo demuestra la importancia del EDA en proyectos de Inteligencia Artificial, Ciencia de Datos y toma de decisiones basadas en evidencia.

---
