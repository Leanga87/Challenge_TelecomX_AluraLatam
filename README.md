# Análisis de Evasión de Clientes - TelecomX LATAM

Este proyecto analiza el fenómeno de **evasión de clientes (churn)** en una compañía de telecomunicaciones ficticia llamada **TelecomX LATAM**. El objetivo principal es identificar patrones de abandono, extraer insights clave y proponer estrategias que permitan reducir la tasa de cancelación del servicio.

---

## 📊 Objetivo del Proyecto

- Comprender el comportamiento de los clientes que **cancelan su suscripción**.
- Detectar **patrones** asociados a la evasón mediante el análisis exploratorio de datos.
- Presentar visualizaciones claras y variadas que permitan comunicar resultados a stakeholders no técnicos.
- Proponer **recomendaciones estratégicas** basadas en datos.

---

## 📚 Estructura del Análisis

1. **Importación y limpieza de datos**  
   - Conversión de valores categóricos a formato binario
   - Eliminación de nulos y corrección de tipos de datos
   - Renombrado de columnas para mayor claridad

2. **Análisis Exploratorio de Datos (EDA)**  
   - Visualización de la distribución de `Churn`
   - Comparaciones entre `Churn` y variables categóricas (sexo, contrato, método de pago, etc.)
   - Comparaciones entre `Churn` y variables numéricas (gasto total, tiempo de contrato, etc.)
   - Gráficos interactivos (tortas, histogramas, heatmaps, líneas, scatter, etc.)

3. **Análisis de Correlaciones** *(opcional)*  
   - Estudio de la relación entre número de servicios contratados, cuenta diaria y evasón.

4. **Conclusiones e Insights**  
   - Síntesis de hallazgos más relevantes

5. **Recomendaciones Estratégicas**  
   - Acciones propuestas basadas en el análisis

---

## 👨‍💻 Tecnologías y Librerías

- Python 3.11+
- Jupyter Notebook
- Pandas
- Plotly
- Seaborn
- Matplotlib

---

## 📈 Resultados Clave

- **Mayor tasa de abandono** en clientes con contrato mensual y sin servicios adicionales (seguridad online, soporte técnico, streaming).
- **Usuarios sin pareja ni personas a cargo** presentan tasas de evasón levemente superiores.
- Clientes con **menor antigüedad** y **menor gasto acumulado** muestran mayor propensión a cancelar.
- Los métodos de pago automáticos y contratos a largo plazo **reducen la probabilidad de churn**.

---

## 📊 Recomendaciones Finales

- Ofrecer **beneficios exclusivos a usuarios con contrato mensual** para fomentar la retención.
- Promover paquetes que incluyan **múltiples servicios combinados**.
- Implementar **alertas tempranas** para clientes con baja antigüedad y poco compromiso.
- Estimular el uso de **métodos de pago automáticos** con promociones o descuentos.

---

## 🏑 Autor
**Leandro Puebla Martínez**  
Estudiante de Ciencia de Datos | Chubut Puerto Madryn

Este proyecto forma parte del curso de Ciencia de Datos de **Alura Latam + Oracle Next Education**.

---

> 🔗 Repositorio del dataset y código fuente disponible en este repositorio.
🖼️ Nota: Todos los gráficos generados con Plotly han sido convertidos a imágenes estáticas (formato PNG) utilizando Kaleido, para asegurar su correcta visualización en GitHub.
📁 Las visualizaciones están embebidas en el notebook principal TelecomX_LATAM.ipynb.

---

