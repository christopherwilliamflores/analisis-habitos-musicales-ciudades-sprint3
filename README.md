# 🎧 Análisis de hábitos de escucha musical – Sprint 3

**Bootcamp de Ciencia de Datos | TripleTen**  
**Autor:** Christopher William Flores Rimac

---

## 📌 Descripción del proyecto

Este proyecto forma parte del Módulo 1 del bootcamp de ciencia de datos de TripleTen. En él se analiza el comportamiento de escucha musical de usuarios de dos ciudades ficticias: **Springfield** y **Shelbyville**, utilizando datos reales de una plataforma de streaming musical.

---

## 🎯 Objetivos

1. Realizar una **descripción general** de los datos del usuario.
2. Aplicar **preprocesamiento** para limpiar datos faltantes y duplicados.
3. Analizar si existen diferencias en los hábitos de consumo musical según:
   - Día de la semana
   - Ciudad del usuario
   - Género musical

---

## 🧰 Herramientas utilizadas

- **Python 3**
- **Pandas**
- **Jupyter Notebook**
- **Visualización básica**
- **Análisis exploratorio de datos (EDA)**

---

## 🗃️ Dataset utilizado

Archivo: `/datasets/music_project_en.csv`

### 📑 Diccionario de datos:

| Columna   | Descripción                                              |
|-----------|----------------------------------------------------------|
| userID    | ID único del usuario                                     |
| Track     | Título de la canción                                     |
| artist    | Nombre del artista                                       |
| genre     | Género musical                                           |
| City      | Ciudad del usuario (Springfield o Shelbyville)          |
| time      | Hora de reproducción (formato HH:MM:SS)                  |
| Day       | Día de la semana en el que ocurrió la reproducción       |

---

## 🔍 Etapas del proyecto

1. **Descripción de los datos**
   - Exploración inicial
   - Observación de distribuciones
2. **Preprocesamiento**
   - Corrección de nombres de columnas
   - Manejo de valores duplicados y ausentes
3. **Análisis**
   - Comparación de preferencias por género, ciudad y día
   - Evaluación de patrones de escucha
4. **Conclusiones**
   - Resumen de hallazgos clave

---

## 📌 Conclusión

El análisis permitió descubrir patrones significativos en la actividad musical de los usuarios según ciudad y día. Esto puede usarse para personalizar campañas de marketing y mejorar la recomendación de contenido en plataformas de streaming.

---

## 🧠 Aprendizajes clave

- Aplicación de limpieza de datos con Pandas
- Comparación de subgrupos mediante filtros
- Extracción de conclusiones basadas en datos reales
