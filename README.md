# IELE756 · Preparación y Análisis de Datos — Región 05

Portafolio de análisis de datos del curso **IELE756 – Preparación y Análisis de Datos**, desarrollado sobre datos públicos chilenos (Censo 2024, notificaciones epidemiológicas ENO y egresos hospitalarios GRD). El proyecto recorre el flujo completo de un analista: carga y limpieza de datos, análisis exploratorio, modelamiento cruzado entre fuentes y detección y defensa de una anomalía.

- **Equipo:** Tomás Allende · Felipe Castillo
- **Región / Comunas:** Ñuñoa (13120), San Joaquín (13129), San José de Maipo (13203)
- **Stack:** Python · pandas · NumPy · Matplotlib · Jupyter

---

## 📂 Contenido

| Carpeta | Tarea | De qué trata |
|---|---|---|
| [`tarea-0-fundamentos`](tarea-0-fundamentos/) | Tarea 0 | Fundamentos de pandas y primeros ratios sobre el Censo. |
| [`tarea-1-censo`](tarea-1-censo/) | Tarea 1 | Análisis del Censo 2024: razón de dependencia y perfil demográfico por comuna. |
| [`tarea-2-eno`](tarea-2-eno/) | Tarea 2 | Datos epidemiológicos (ENO): limpieza, anonimización y análisis de notificaciones. |
| [`tarea-3-modelamiento-ecologico`](tarea-3-modelamiento-ecologico/) | Tarea 3 | Modelamiento ecológico cruzando Censo + egresos hospitalarios (GRD). |
| [`proyecto-final-anomalia`](proyecto-final-anomalia/) | Proyecto final | "One Anomaly, Defended": la tasa de egresos hospitalarios de San José de Maipo. |

## 🔍 Hallazgo principal

San José de Maipo (≈17.400 hab.) presenta la **tasa de egresos hospitalarios más alta** de las 37 comunas analizadas —**1.630 por cada 10.000 habitantes**— pese a ser una de las comunas menos pobladas de la Región Metropolitana. El proyecto final documenta y defiende esta anomalía. 📺 [Video explicativo](https://youtu.be/LHqMzbrKAwk)

## 🗂️ Fuentes de datos

- **Censo 2024** (INE Chile) — personas, hogares y viviendas.
- **ENO** — Enfermedades de Notificación Obligatoria.
- **GRD** — Grupos Relacionados por Diagnóstico (egresos hospitalarios).

> Los datos crudos no se versionan en este repositorio (ver `.gitignore`). Los notebooks documentan el origen y el procesamiento de cada fuente.

## ▶️ Cómo ejecutar

```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook
```

Abre cualquiera de los notebooks dentro de su carpeta y ejecútalo de arriba hacia abajo.

---

*Trabajo académico · Universidad · 2026.*
