# 🌍 Huellas del Mundo – Análisis del Turismo Extranjero en España (2014–2016)

Este proyecto explora el comportamiento y evolución del turismo internacional en España entre 2014 y 2016, con un enfoque analítico orientado a la obtención de insights accionables. Mediante técnicas estadísticas, visualización interactiva y análisis territorial, se identifican patrones de gasto, preferencias y evolución de los flujos turísticos.

---

## 📌 Objetivo

Analizar el turismo extranjero en España desde múltiples dimensiones (temporal, geográfica, conductual y económica) para detectar tendencias clave y relaciones significativas entre variables. El proyecto pone especial atención en:

- El gasto turístico y su evolución
- Las preferencias según comunidad autónoma y motivo de viaje
- La duración de los viajes y su impacto en el gasto medio
- Las diferencias entre países de origen, estacionalidad y tipos de alojamiento

---

## 📈 Principales análisis realizados

- **Evolución del volumen de turistas** según país de residencia y por meses del año
- **Crecimiento anual (%) del turismo extranjero**
- **Motivos del viaje** (ocio, negocios, visita a familiares/amigos, etc.) y su impacto en el comportamiento del visitante
- Comparación entre **gasto medio total, gasto medio anual y gasto medio diario**
- Evolución de la **duración media del viaje**
- **Relación entre gasto medio y duración** según el motivo del viaje
- Análisis de **preferencias de alojamiento** (el 73% elige hotel a nivel nacional)
- **Análisis por Comunidad Autónoma (CCAA)**:
  - Flujo turístico según destino principal
  - Gasto medio vs gasto diario por CCAA
  - Evolución anual del gasto por comunidad
  - Duración media del viaje por comunidad
  - **Correlación fuerte** entre gasto medio y duración media del viaje por comunidad (relación lineal clara)
- **Visualización geoespacial** del comportamiento turístico en España mediante mapas interactivos

---

## 🧪 Metodología y técnicas

- **ETL**: Importación, transformación y limpieza de 9 datasets del INE (Instituto Nacional de Estadística)
- **EDA**: Análisis exploratorio de datos con visualizaciones dinámicas
- **Normalidad**: Prueba de Shapiro-Wilk para evaluar la distribución de variables clave
- **Estadística inferencial**:
  - ANOVA
  - Kruskal-Wallis
  - Pruebas post-hoc (Tukey HSD / Dunn)
  - Correlaciones (Pearson, Spearman, Kendall)
- **Visualización**:
  - Dashboards e informes interactivos en Power BI
  - Gráficos dinámicos y mapas con Python

---

## 🧰 Herramientas utilizadas

- **Python**:
  - `Pandas`, `NumPy` – procesamiento y análisis de datos
  - `Matplotlib`, `Seaborn`, `Plotly Express` – visualización estadística
  - `GeoPandas` – visualización geográfica y mapas por Comunidad Autónoma
  - `Scipy`, `Pingouin` – pruebas estadísticas
- **Power BI**: Informe visual e interactivo para análisis detallado
- **Jupyter Notebook**: Desarrollo técnico del análisis
- **Datos**: fuentes oficiales del INE (2014–2016)

---

## 🗂️ Contenido del repositorio

| Archivo                              | Descripción                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| `Datasets_Proyecto.ipynb`           | Notebook con ETL, EDA, visualización, mapas y pruebas estadísticas         |
| `Visualización_BI_Proyecto.pbix`    | Informe en Power BI con visualizaciones y análisis por comunidad autónoma  |
| `Presentación Huellas del mundo.pdf`| Documento resumen con introducción, gráficos clave y conclusiones          |

---

## 💡 Conclusiones destacadas

- Las comunidades autónomas con mayor volumen turístico presentan también un gasto medio superior y estancias más largas.
- El **motivo del viaje** influye fuertemente en el **gasto diario** y la **duración de la estancia**.
- Se confirma una correlación positiva entre **duración media del viaje y gasto medio total**, especialmente a nivel regional.
- A pesar de ligeras variaciones, **el hotel es la opción de alojamiento preferida** por el 73% de los visitantes internacionales.
- Los **mapas geográficos** permiten detectar patrones regionales de preferencia turística y gasto de forma visual e inmediata.

---

## 📫 Sobre el autor

👋 Soy **Giuseppe Buompane**, Analista de Datos con formación en Business Intelligence y análisis estadístico. Ayudo a equipos y empresas a transformar datos en decisiones informadas.

🔗 [Conecta conmigo en LinkedIn](https://www.linkedin.com/in/giuseppebuompane)  


---

> ¿Te interesa este enfoque de análisis aplicado? ¿Buscas talento junior con mirada analítica, rigor estadístico y mentalidad de mejora continua?  
> 📬 ¡Estoy abierto a nuevas oportunidades profesionales y colaboraciones!

