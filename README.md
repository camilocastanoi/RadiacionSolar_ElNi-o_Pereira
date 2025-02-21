# Radiación Solar y Predicción del Fenómeno de El Niño en Pereira

## 📌 Descripción
Este proyecto analiza la relación entre la **radiación solar** y la ocurrencia del fenómeno de **El Niño y La Niña** en Pereira, Colombia. Se utilizan datos históricos y técnicas de análisis de datos para desarrollar modelos predictivos basados en variables climáticas.

---

## 📊 Datos Utilizados
- **Fuente**: IDEAM, NOAA y otras bases de datos meteorológicas.
- **Variables principales**:
  - **Radiación solar promedio mensual** ☀️
  - **Temperatura media mensual** 🌡️
  - **Precipitación mensual** 🌧️
  - **Índice de Oscilación del Sur (ENSO)** 📉
  - **Otras variables climáticas relevantes** 🌍

---

## 🛠️ Metodología

1. **Recolección y Limpieza de Datos**  
   - Se recopilan datos de fuentes confiables.
   - Se realiza limpieza de valores nulos y manejo de outliers.

2. **Análisis Exploratorio**  
   - Se visualizan tendencias de la radiación solar en Pereira.
   - Se analizan correlaciones entre la radiación solar y la aparición de El Niño.

3. **Modelado Predictivo**  
   - Se prueban modelos como:
     - Regresión logística.
     - Random Forest.
     - Redes neuronales.
   - Se evalúan métricas como **precisión**, **recall** y **MSE**.

4. **Predicción y Visualización**  
   - Se entrenan modelos para predecir futuras ocurrencias de El Niño y La Niña.
   - Se presentan gráficos de tendencias y patrones climáticos.

---

## 🚀 Instalación y Uso

### **Requisitos**
- Python 3.x
- Librerías necesarias: `pandas`, `numpy`, `matplotlib`, `sklearn`, `seaborn`

### **Ejecución**
1. Clona el repositorio:
   ```bash
   git clone https://github.com/camilocastanoi/RadiacionSolar_ElNiño_Pereira.git
   cd RadiacionSolar_ElNiño_Pereira
