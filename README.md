# 📊 Análisis Exploratorio - UCI Credit Card

Este proyecto forma parte de la **Evidencia 1** y tiene como objetivo realizar un análisis exploratorio de datos (EDA) utilizando el dataset **UCI Credit Card**, disponible en [Kaggle](https://www.kaggle.com/).  
El análisis se desarrolla en un entorno de **Python 3.11**, empleando herramientas como `pandas` y `ydata_profiling`.

---

## 🧩 Objetivos del proyecto
1. Analizar la estructura y calidad de los datos.  
2. Identificar duplicados, valores nulos y tipos de datos.  
3. Examinar distribuciones y correlaciones entre variables.  
4. Generar un reporte automatizado de perfilado de datos mediante `ydata_profiling`.

---

## 🧰 Librerías principales utilizadas
- **pandas** → manipulación y análisis de datos tabulares.  
- **ydata-profiling** → creación automática de reportes exploratorios.  
- **numpy** → soporte matemático y manejo de matrices.  
- **matplotlib / seaborn** → visualización de datos.  
- **jupyter notebook** → entorno interactivo para el análisis.

---

## 📁 Estructura del repositorio

| Archivo | Descripción |
|----------|--------------|
| `exploracion.ipynb` | Notebook con el análisis exploratorio completo |
| `UCI_Credit_Card.csv` | Dataset de clientes de tarjeta de crédito |
| `requirements.txt` | Dependencias necesarias para reproducir el entorno |
| `README.md` | Descripción completa del proyecto (este archivo) |

---

## ⚙️ Requisitos de entorno

Se utilizó **Python 3.11.x** con las siguientes dependencias:

```txt
# requirements.txt

pandas==2.2.3
numpy==1.26.4
ydata-profiling==4.7.0
jupyter==1.1.1
ipython==8.12.3
ipywidgets==8.1.5
matplotlib==3.9.2
seaborn==0.13.2
notebook==7.2.2
scipy==1.13.1
````

📦 Instala todas las dependencias con:

```bash
pip install -r requirements.txt
```

---

## 🚀 Cómo ejecutar el proyecto

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/tu_usuario/evidencia1.git
   cd evidencia1
   ```

2. **Crear y activar el entorno virtual**

   ```bash
   python -m venv venv
   venv\Scripts\activate      # En Windows
   # o
   source venv/bin/activate   # En macOS/Linux
   ```

3. **Instalar dependencias**

   ```bash
   pip install -r requirements.txt
   ```

4. **Abrir el notebook**

   ```bash
   jupyter notebook exploracion.ipynb
   ```

5. **Ejecutar el análisis**
   El notebook generará automáticamente el archivo `Reporte_UCI_Credit_Card.html` con el perfil completo del dataset.


## 👩‍💻 Autor
GRUPO 10
📚 Curso / Asignatura: PROYECTO INTEGRADO
🏫 Universidad: IUD
📅 Fecha: *Noviembre 2025*

```