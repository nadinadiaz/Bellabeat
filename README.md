# 📊 Bellabeat Case Study: Análisis de Bienestar Basado en Datos

![Bellabeat Logo](https://img.shields.io/badge/Project-Data%20Analytics-pink?style=for-the-badge) 
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) 
![Tidyverse](https://img.shields.io/badge/Tidyverse-B08EAD?style=for-the-badge)

## 🧠 Objetivo del Proyecto
Este análisis busca identificar patrones de comportamiento en el uso de dispositivos de seguimiento de actividad física para generar **insights estratégicos** que impulsen el crecimiento de **Bellabeat**.

El proyecto forma parte del **Google Data Analytics Professional Certificate** y utiliza datos públicos de Fitbit para simular un escenario real de consultoría de negocios.

---

## 🧾 Pregunta de Negocio
> *¿Cómo utilizan las usuarias los dispositivos inteligentes y qué oportunidades puede identificar Bellabeat para mejorar sus productos y estrategias de marketing?*

---

## 🛠️ Stack Tecnológico
Para este análisis se utilizó el lenguaje **R** y su ecosistema de procesamiento de datos:

* **Manipulación de Datos:** `tidyverse`, `dplyr`, `tidyr`, `lubridate`.
* **Visualización:** `ggplot2`, `scales`.
* **Reporte Dinámico:** `RMarkdown`, `kableExtra`.

**Habilidades aplicadas:** Limpieza profunda de datos, transformación de variables, análisis exploratorio (EDA) y visualización de patrones de comportamiento.

---

## 📂 El Dataset
Se utilizaron registros de 30+ usuarios voluntarios de Fitbit.
* **Variables clave:** Pasos diarios, niveles de intensidad (minutos), gasto calórico, registros de sueño y tiempo en cama.
* **Proceso de Calidad:**
    * Eliminación de duplicados y valores nulos.
    * Filtro de integridad metabólica (correlación pasos vs. calorías).
    * Validación de rangos fisiológicos (pasos por kilómetro y límites de 1440 min/día).

---

## 🔎 Proceso de Análisis

1.  **Preparación:** Consolidación de múltiples datasets en una tabla maestra única.
2.  **Validación:** Auditoría de coherencia entre distancia, pasos y calorías.
3.  **Exploración:** Análisis de segmentación de usuarias (Élite vs. Sedentario).
4.  **Tendencias:** Análisis de estacionalidad semanal y ritmos horarios.
5.  **Sueño:** Cruce de datos de descanso con actividad diaria.



---

## 📈 Insights Clave

| Hallazgo | Detalle Estadístico |
| :--- | :--- |
| **Brecha de Consistencia** | Solo el **39.5%** de los días se alcanza la meta de 10k pasos. |
| **Pico de Actividad** | La mayor intensidad ocurre entre las **17:00 y 19:00 hs**. |
| **Paradoja Sedentaria** | El **78%** del día es sedentario, incluso en usuarias activas. |
| **Independencia del Sueño** | La calidad del descanso ($r \approx 0$) no depende solo del ejercicio físico. |

---

## 💡 Recomendaciones Estratégicas

* **🚀 Notificaciones Inteligentes:** Implementar alertas de movimiento a las 15:30 hs (valle de energía) y motivación de entrenamiento a las 18:30 hs.
* **🎮 Gamificación:** Fomentar "rachas de actividad" para combatir la falta de consistencia en el cumplimiento de los 10,000 pasos.
* **🧘 Enfoque Holístico:** Integrar el monitoreo de sueño con datos de estrés y hábitos nocturnos para ofrecer una visión 360 del bienestar.

---

## 📊 Visualizaciones Seleccionadas
* Distribución de pasos según nivel de actividad.
* Variabilidad de pasos por día de la semana (Boxplot).
* Ritmo de vida: Intensidad media por hora.
* Relación entre sedentarismo e inquietud nocturna.

---

## 👩‍💻 Autora
**Nadina Díaz** *Data Analyst en formación* *Enfoque en investigación académica y visualización de datos estadísticos.*

---
*Este proyecto fue realizado con fines educativos para el Certificado de Análisis de Datos de Google.*
