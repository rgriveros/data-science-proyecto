# Proyecto Final – Data Science I: E-Commerce Analytics
Este repositorio contiene el desarrollo completo del Proyecto Final del curso Data Science I en Coderhouse. Se abordan desde la exploración de datos hasta la construcción y evaluación de modelos predictivos para e-commerce.

## Descripción
El objetivo es analizar un dataset transaccional de comercio electrónico y:
Explorar la calidad de datos, patrones y relaciones clave.
Formular hipótesis sobre devoluciones, descuentos y satisfacción del cliente.
Implementar un pipeline de preprocesamiento y selección de características.
Entrenar y evaluar modelos de regresión (valor de la orden) y clasificación (solicitud de devolución).
Generar conclusiones accionables para decisiones de negocio.

## Estructura del repositorio
.
├── data/
│   ├── raw/           # CSVs originales
│   └── processed/     # (opcional) datos limpios o transformados
├── notebooks/
│   └── ProyectoParteIII_RiverosLobos.ipynb  # Notebook principal
├── environment.yml    # Entorno Conda reproducible
├── requirements.txt   # Dependencias pip
└── README.md          # Documentación de uso

## Contenido del Notebook
Imports y configuración
Definición de paths (rutas relativas)
Carga y limpieza de datos
Análisis Exploratorio (EDA)
Valores faltantes
Univariado, bivariado y multivariado
Preprocesamiento
Selección de variables
Modelado
Regresión (order_value)
Clasificación (return_requested)
Ajuste de hiperparámetros
Validación final y visualizaciones
Conclusiones e insights de negocio

## Requisitos
Python 3.10+
Conda (Miniconda o Anaconda) o pip

## Configurar el entorno
### Con Conda

git clone https://github.com/rgriveros/data-science-proyecto.git
cd data-science-proyecto

### Crear el entorno
conda env create -f environment.yml

### o, si ya existe:
conda env update -f environment.yml

conda activate ds1-proyecto

### Con pip

git clone https://github.com/rgriveros/data-science-proyecto.git
cd data-science-proyecto

pip install -r requirements.txt

### Ejecutar el Notebook
Activar el entorno (Conda o pip).
Lanzar Jupyter Lab/Notebook:

jupyter lab
Abrir notebooks/ProyectoParteIII_RiverosLobos.ipynb.

Seleccionar Run All para reproducir el análisis completo.

## Resultados Esperados
Reporte de calidad de datos y patrones de negocio.
Comparativa de desempeño con y sin selección de variables.
Métricas de regresión: MAE, RMSE, R².
Métricas de clasificación: accuracy, precision, recall, F1, ROC.
Gráficos de importancia de variables y matrices de confusión.
Conclusiones sobre descuentos, devoluciones y recomendaciones de marketing.

### Licencia
Este proyecto está bajo la licencia MIT.

## Autor
Rodolfo Gabriel Riveros Lobos
rgriveroslobos@gmail.com