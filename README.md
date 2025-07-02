# 🌍 Huellas del Mundo – Análisis del Turismo Extranjero en España (2016–2024)

**Huellas del Mundo** es un proyecto de análisis de datos centrado en la evolución del turismo extranjero en España durante los años 2016 a 2024. A partir de fuentes oficiales del INE (Instituto Nacional de Estadística), este estudio profundiza en patrones de comportamiento, gasto y distribución geográfica de visitantes internacionales.

---

## 🎯 Objetivo

Obtener insights accionables a partir de datos oficiales del INE sobre el turismo extranjero, aplicando técnicas de análisis exploratorio, validación estadística y visualización para detectar:

- Tendencias temporales
- Patrones por comunidad autónoma
- Comportamientos diferenciados por nacionalidad y motivo del viaje
- Relaciones entre duración del viaje y gasto
- Oportunidades para la toma de decisiones basadas en datos

---

## 🧩 Datasets

Se integraron 8 datasets oficiales del INE relacionados con el turismo extranjero, incluyendo información mensual por comunidad autónoma, país de residencia, tipo de alojamiento, motivo del viaje, gasto medio y duración.

---

## 🔍 Análisis Realizado

✔️ **ETL (Extracción, Transformación y Carga)**  
Importación, limpieza, normalización y unificación de los 8 datasets.

✔️ **Análisis exploratorio de datos (EDA)**  
Estudio de la evolución del volumen de turistas por país de origen, análisis de estacionalidad (Julio, Agosto y Septiembre son los meses con más afluencia, aunque los países nórdicos destacan en Octubre y Noviembre), destinos favoritos (Cataluña, Baleares y Canarias concentran el 52% del total) y duración media del viaje.

✔️ **Gasto y duración**  
- Evolución del gasto medio, gasto medio diario y duración media.
- Comparativa por comunidad autónoma y por motivo del viaje.
- Se observa una **relación lineal positiva entre duración y gasto medio**, especialmente por comunidad autónoma.

✔️ **Motivo del viaje**  
- Alta duración media y gasto total en viajes por estudios, trabajo estacional o motivos religiosos.
- Mayor gasto medio diario en viajes por congresos y ferias.

✔️ **Estudios estadísticos**  
- Pruebas de normalidad (Shapiro-Wilk)
- ANOVA, Kruskal-Wallis
- Pruebas post-hoc (TukeyHSD, Dunn)
- Correlaciones (Pearson, Spearman, Kendall)

✔️ **Crecimiento del turismo extranjero**  
📈 Entre 2016 y 2024, el número de turistas internacionales creció un **24,49%**.

---

## 🧰 Herramientas y Librerías

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly express`, `datetime`, `scipy`, `statsmodels`, `geopandas`
- **Power BI**: Visualización interactiva y presentación del informe final
- **Jupyter Notebook**: Desarrollo del análisis y visualizaciones

---

## 📊 Visualización

- Dashboards y gráficos interactivos desarrollados en Power BI (.pbix)
- Gráficos de líneas, barras, mapas y dispersión con `matplotlib`, `seaborn`, `plotly`
- Mapa geográfico de gasto y duración media por comunidad autónoma generado con `geopandas`

---

## 📁 Archivos del Repositorio

- `Datasets_Proyecto.ipynb` → ETL, EDA, análisis y pruebas estadísticas
- `Visualización_BI_Proyecto.pbix` → Informe interactivo con Power BI
- `Presentación Huellas del Mundo.pdf` → Introducción y conclusiones clave

---

## 📫 Sobre el autor

👋 Soy **Giuseppe Buompane**, Analista de Datos con formación en Business Intelligence y análisis estadístico. Ayudo a equipos y empresas a transformar datos en decisiones informadas.

¿Te interesa este enfoque de análisis aplicado?  
¿Buscas talento junior con mirada analítica, rigor estadístico y mentalidad de mejora continua?

🔗 Conecta conmigo en [LinkedIn](https://www.linkedin.com/in/giuseppebuompane)  
📬 ¡Estoy abierto a nuevas oportunidades profesionales y colaboraciones!


