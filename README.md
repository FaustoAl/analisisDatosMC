# Trabajo N°3
# Grupo 4
- FAUSTO RENE ALMEIDA FONSECA
- JESSICA VANESSA TIPANTUÑA QUILUMBAQUIN
- ANGEL GUSTAVO TOAPANTA LLANO

# 🌍 Análisis de la Felicidad Mundial 2023
Este proyecto aplica técnicas de **Análisis Exploratorio de Datos (EDA)** y **Machine Learning** sobre el dataset de Felicidad Mundial para identificar qué factores influyen más en el bienestar de las naciones.

## 🚀 Instalación y Uso
1. Clona el repositorio:
   git clone https://github.com/FaustoAl/analisisDatosMC.git
2. Instala las dependencias:
   pip install -r requirements.txt
3. Abre el notebook 'AnalisisM.ipynb en Jupyter o VS Code.


## 📊 Manejo del Dataset
Para asegurar la reproducibilidad del proyecto, el notebook está configurado para cargar los datos de forma remota. Sin embargo, se ha incluido una copia local por seguridad.

* **Opción A (Remota):** El script intenta cargar el CSV directamente desde el repositorio para facilitar la ejecución inmediata.
* **Opción B (Local):** Si la URL no está disponible o prefieres trabajar offline, puedes cambiar la ruta de carga en la celda de "Carga de Datos" por:
    df = pd.read_csv('data/whr2023.csv')

> **Nota:** El archivo local se encuentra en la carpeta `/data` de este repositorio.
## 🛠️ Tecnologías Utilizadas
* **Análisis de Datos:** Pandas, Numpy.
* **Visualización:** Matplotlib, Seaborn, Plotly (Mapas interactivos).
* **Machine Learning:** Scikit-learn (Regresión Lineal y K-Means Clustering).

## 💡 Hallazgos Principales (Insights)
* **El peso del PIB:** Se confirmó una correlación de ~0.XX entre el PIB y la felicidad.
* **Anomalías:** Países con alta percepción de corrupción mantienen niveles de felicidad altos, lo que sugiere que el **Apoyo Social** actúa como un amortiguador.
* **Predicción:** El modelo de regresión alcanzó una precisión (R2 Score) de **0.XX**, demostrando que la felicidad es altamente predecible con datos económicos y de salud.
