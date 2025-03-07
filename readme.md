# 📊 Análisis Exploratorio de Datos (EDA) - GapMinder
## 🔍 Objetivo  
El objetivo de este proyecto es realizar un análisis exploratorio de datos (**EDA**) sobre el conjunto de datos de **GapMinder** y, si procede, sobre los datos de calidad del aire en **Barcelona**. Se aplicarán técnicas de **preprocesamiento, normalización y visualización** para comprender mejor las tendencias y relaciones entre las variables.  

## 📝 Tareas a realizar  

### 1️⃣ **Carga y Exploración Inicial de Datos**  
- Cargar los datos de **GapMinder** e identificar la disparidad de escalas entre las variables (ejemplo: `life_exp` vs `GDP_per_cap`).  
- Explorar el dataset para detectar valores nulos, valores atípicos y estructuras de datos problemáticas.  

### 2️⃣ **Escalado y Normalización**  
- Aplicar técnicas de **escalado** para reducir la disparidad entre las variables.  
- Comparar diferentes métodos de escalado:  
  - **StandardScaler** (media 0, desviación estándar 1)  
  - **MinMaxScaler** (escala entre 0 y 1)  
  - **RobustScaler** (basado en la mediana, resistente a valores atípicos)  

### 3️⃣ **Visualización de Dimensiones Principales**  
- Aplicar **PCA (Análisis de Componentes Principales)** para visualizar la información en menos dimensiones.  
- Generar **pairplots** antes y después del escalado para observar cómo afectan las transformaciones.  


## 📌 Librerías Utilizadas  
- `pandas` para la gestión de datos  
- `numpy` para cálculos numéricos  
- `scipy` para estadística y preprocesamiento  
- `matplotlib` y `seaborn` para visualización  

## 🚀 Resultados Esperados  
- Identificar **relaciones y patrones** en los datos de GapMinder y calidad del aire.  
- Mejorar la interpretabilidad de los datos aplicando escalado.  
- Visualizar el impacto del escalado en las distribuciones de datos.  

---

✍️ *Autor: [Arnau González Almirall]*  
📅 *Fecha de inicio: [28/02/25]*  

