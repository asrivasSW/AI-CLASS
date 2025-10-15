# 📊 TALLER SEGUNDO CORTE: ANÁLISIS DE DATOS CON PYTHON

## 📋 Integrantes

* **ANDRES STEVEN RIVAS SALAS**
* **KEVIN JOSEPH VALBUENA PÉREZ**
* **RUBEN DARIO BARAHONA**

## ✨ Descripción del Proyecto

Este repositorio contiene un Notebook (`.ipynb`) desarrollado como taller del segundo corte para realizar **análisis y manipulación de datos** utilizando las librerías fundamentales de Python: **NumPy** y **Pandas**.

El proyecto se centra en dos áreas principales:
1.  **Fundamentos de NumPy:** Creación de arreglos y cálculo de medidas de tendencia central y dispersión.
2.  **Análisis de Datos con Pandas:** Importación, manipulación, cálculo de estadísticas descriptivas y visualización de un conjunto de datos de estudiantes (`Dataset_Estudiantes.xlsx`).

## ⚙️ Tecnologías y Librerías Utilizadas

El proyecto fue desarrollado en un entorno de **Python** (probablemente Google Colab, dado el uso de `http://google.colab.drive`) y utiliza las siguientes librerías:

| Librería | Propósito |
| :--- | :--- |
| **NumPy** (`np`) | Manejo de arreglos numéricos y operaciones matemáticas de alto rendimiento. |
| **Pandas** (`pd`) | Manipulación y análisis de datos a través de DataFrames. |
| **Matplotlib** (`plt`) | Creación de visualizaciones estáticas (gráficos de barras, dispersión, histogramas). |
| **SciPy** (`stats`) | Funcionalidades científicas y estadísticas (usada para calcular la moda). |

## 🚀 Instalación y Ejecución

Para reproducir este análisis, sigue estos pasos:

1.  **Clonar el repositorio** (si aplica, en un entorno local de Git):
    ```bash
    git clone [URL_DEL_REPOSITORIO]
    cd TALLER_SEGUNDO_CORTE_IA
    ```
2.  **Instalar las dependencias de Python:**
    ```bash
    pip install numpy pandas matplotlib scipy openpyxl
    ```
    *(Se incluye `openpyxl` ya que se trabaja con un archivo `.xlsx`)*
3.  **Configuración del Entorno de Datos (Google Colab):**
    Si usas Google Colab, asegúrate de **montar Google Drive** para acceder al archivo de datos, tal como se hace en el código:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
    Y verifica que el archivo `Dataset_Estudiantes.xlsx` esté en la ruta especificada (`/content/drive/MyDrive/kaggle/`).
4.  **Ejecutar el Notebook:**
    Abre y ejecuta las celdas del archivo `.ipynb` en orden.

## 📝 Puntos de Análisis Realizados

Los siguientes análisis se abordan en el código:

### I. Fundamentos de NumPy
* Creación de un arreglo numérico del 1 al 1000.
* Cálculo de la **suma total** del arreglo (Resultado: 500500).
* Cálculo de **Medidas de Tendencia Central** (Media, Mediana, Moda) y **Dispersión** (Varianza, Desviación Estándar) para un conjunto de datos simple.

### II. Análisis del DataFrame de Estudiantes
* **Carga de Datos:** Se carga el archivo `Dataset_Estudiantes.xlsx` en un DataFrame de Pandas (`df_datasetestu`).
* **Estadísticas Descriptivas:** Cálculo de la media, mínimo, máximo y desviación estándar de la columna `Notas`.
* **Filtrado de Datos:** Se identifican los estudiantes con una nota mayor o igual a 4.0.
* **Análisis por Grupo:** Se calcula el **promedio de notas por género**.
* **Medidas de Dispersión:** Cálculo de Rango, Varianza y Desviación Estándar de la distribución de notas.

### III. Visualizaciones
Se generaron las siguientes visualizaciones con Matplotlib:
* **Gráfico de Barras** de las Notas de los Estudiantes.
* **Gráfico de Dispersión** para visualizar la relación entre `Edad` y `Nota`.
* **Histograma** para mostrar la distribución de la columna `Notas`.

## 🧑‍💻 Archivos del Proyecto

* `Parte_2_de_Taller1_segundo_corte_AI.ipynb.ipynb`: Archivo principal de Jupyter Notebook con todo el código y análisis.
* `Dataset_Estudiantes.xlsx`: Conjunto de datos de entrada utilizado para el análisis de estudiantes.
