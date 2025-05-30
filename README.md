# Análisis de Hongos utilizando Clustering y PCA

Este proyecto presenta un análisis de un conjunto de datos sobre hongos utilizando métodos de clustering y análisis de componentes principales (PCA). El proyecto incluye análisis exploratorio de datos, visualización y aplicación de varios métodos de aprendizaje automático.

## Descripción del Conjunto de Datos

El conjunto de datos contiene información sobre diversas características de los hongos, incluyendo:
- Forma del sombrero
- Superficie del sombrero
- Color del sombrero
- Presencia de moretones
- Olor
- Características de las láminas
- Características del tallo
- Y otros rasgos morfológicos

La variable objetivo es la toxicidad del hongo (clasificación binaria).

## Requisitos

El proyecto utiliza las siguientes bibliotecas principales:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- kneed
- plotly

La lista completa de dependencias se puede encontrar en el archivo `requirements.txt`.

## Instalación

1. Clone el repositorio
2. Cree un entorno virtual:
```bash
python -m venv .venv
```
3. Active el entorno virtual:
```bash
# Windows
.venv\Scripts\activate
# Linux/Mac
source .venv/bin/activate
```
4. Instale las dependencias:
```bash
pip install -r requirements.txt
```

## Estructura del Proyecto

- `workshop_clustering_pca_Version_final.ipynb` - archivo principal con el análisis de datos
- `requirements.txt` - archivo de dependencias del proyecto
- `README.md` - documentación del proyecto

## Uso

1. Inicie Jupyter Notebook:
```bash
jupyter notebook
```
2. Abra el archivo `workshop_clustering_pca_Version_final.ipynb`
3. Siga las instrucciones en el notebook para realizar el análisis

## Etapas Principales del Análisis

1. Carga y preprocesamiento de datos
2. Análisis exploratorio de datos
3. Aplicación de métodos de clustering
4. Análisis de componentes principales (PCA)
5. Visualización de resultados

