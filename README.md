# TP1: Análisis de Datos - Fútbol Argentino ⚽

Este repositorio contiene la resolución del Trabajo Práctico 1 de Librerías de Python. El objetivo del proyecto es aplicar herramientas de limpieza, análisis y visualización de datos (EDA) sobre un registro de jugadores del fútbol argentino.

## 📂 Sobre el Dataset
* **Fuente:** Kaggle
* **Dataset:** `futbolargentino`
* **Autor original:** rodrigogastonrubio
* **Archivo:** `futbolargentino.xlsx` (Hoja: "Worksheet")

Contiene información detallada de los jugadores, incluyendo su posición, edad, altura, pie hábil, equipo, valor de mercado, entre otras variables.

## 🛠️ Tecnologías utilizadas
* **Python**
* **Jupyter Notebook**
* **Pandas** (Manejo, limpieza y transformación de datos)
* **Matplotlib & Seaborn** (Generación de gráficos)
* **Openpyxl** (Lectura de archivos Excel)

## 🚀 Cómo ejecutar el proyecto localmente (Conda)

1. **Crear el entorno virtual con Conda:**
   Recomendamos usar Python 3.10 o superior.
   ```bash
   conda create --name tp1_futbol python=3.10
   ```

2. **Activar el entorno:**
   ```bash
   conda activate tp1_futbol
   ```

3. **Instalar los requerimientos:**
   Asegurate de que el archivo `requirements.txt` esté en la misma carpeta y ejecutá:
   ```bash
   pip install -r requirements.txt
   ```
   *(Si preferís instalar los paquetes manualmente vía Conda, podés usar: `conda install pandas matplotlib seaborn jupyter openpyxl`).*

4. **Iniciar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Esto abrirá una pestaña en tu navegador. Desde ahí, simplemente abrí el archivo `.ipynb` para ver el código y los gráficos.

## 📊 Resumen del Análisis

Dentro de la notebook vas a encontrar:
* **Análisis inicial:** Exploración de columnas, tipos de datos y cantidad de registros.
* **Tratamiento de valores nulos:** Decisiones justificadas sobre qué hacer con los datos faltantes o inconsistentes (por ejemplo, el tratamiento especial que requirió la variable `Edad`, manteniéndola original para no introducir datos falsos).

## 👥 Autores
* Giacomucci Stefano
