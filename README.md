# 📊 Proyecto de Inferencia Estadística: Análisis de Hábitos Saludables en Jóvenes Universitarios

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

## 📝 Descripción del Proyecto
Este proyecto es la evaluación final del módulo de **Inferencia Estadística** de **Alkemy**. El objetivo principal es analizar los factores que influyen en los hábitos de vida (sueño, estrés, horas de estudio y actividad física) de jóvenes universitarios y determinar su impacto probabilístico y estadístico en el rendimiento académico (GPA).

El análisis está diseñado para presentar hallazgos concretos al **Área de Salud Universitaria**, permitiendo orientar nuevas políticas de bienestar estudiantil basadas en evidencia de datos.

## 🎯 Objetivos
* Aplicar el método científico para formular y probar hipótesis.
* Analizar la distribución de variables de salud y comportamiento.
* Estimar intervalos de confianza para el rendimiento académico general.
* Identificar grupos de riesgo mediante el cálculo de probabilidades.
* Realizar pruebas de hipótesis (T-Student) para validar creencias comunes sobre el impacto del sueño en las calificaciones.

## 📂 Estructura del Repositorio
* `ABP_Modulo_6_Nicolás_Pérez.ipynb`: Notebook principal de Jupyter que contiene la limpieza de datos, el análisis descriptivo, la estimación de parámetros y las pruebas de hipótesis.
* `student_lifestyle_dataset.csv`: Dataset simulado con información de 2,000 estudiantes.
* `PPT Modulo 6 Nicolás Pérez.pptx`: Presentación ejecutiva resumida con los hallazgos para la Unidad de Salud.
* `README.md`: Documentación del proyecto.

## 📖 Diccionario de Datos Principales
| Variable | Descripción | Tipo |
| :--- | :--- | :--- |
| `Study_Hours_Per_Day` | Horas dedicadas al estudio diariamente | Continuo |
| `Sleep_Hours_Per_Day` | Horas de sueño promedio por noche | Continuo |
| `Stress_Level` | Nivel de estrés percibido (Bajo, Moderado, Alto) | Categórico |
| `Grades` (GPA) | Promedio de calificaciones del estudiante | Continuo |

## 💡 Hallazgos Clave y Conclusiones
1. **Distribución del Sueño:** Se verificó que las horas de sueño en la población estudiantil siguen una distribución normal perfecta, con una media de **7.5 horas**.
2. **Alerta de Salud Mental:** Un **51.4%** de la población estudiantil presenta niveles de estrés categorizados como "Altos".
3. **Zona de Riesgo Doble:** A través de la probabilidad de intersección, se determinó que el **26.9%** de los alumnos sufre simultáneamente de privación de sueño (< 7 horas) y estrés severo, requiriendo intervención inmediata.
4. **Prueba de Hipótesis (T-Student):** Al evaluar si dormir menos de 7 horas impacta negativamente las calificaciones de forma aislada, se obtuvo un valor p de **0.25**. Dado que es mayor al nivel de significancia (0.05), **no se rechaza la hipótesis nula**. La diferencia en calificaciones por falta de sueño es estadísticamente insignificante por sí sola, lo que sugiere que intervienen otros factores de peso (como el estrés y métodos de estudio).

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn, SciPy (stats)
* **Entorno:** Jupyter Notebook / Google Colab

## 👨‍💻 Autor
**Nicolás Pérez**
* Estudiante de Data Analysis en Alkemy.
