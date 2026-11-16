# 📊 Visualización de Datos: Matplotlib vs Seaborn

Este repositorio contiene una comparativa práctica entre **Matplotlib** y **Seaborn**, dos de las librerías de visualización de datos más utilizadas en Python. El proyecto incluye 5 tipos de gráficas fundamentales implementadas en ambas herramientas y desplegadas en una aplicación interactiva mediante **Streamlit**.

---

## 🚀 Ver la Aplicación en Vivo

Puedes acceder a la aplicación web interactiva desplegada en Streamlit Cloud a través del siguiente enlace:

👉 **[Aplicación Web en Streamlit Cloud](https://pruebasgraficas-jjayp54gkcxrk42rf5eslu.streamlit.app)**

---

## 📈 Gráficas Incluidas

En el proyecto se comparan lado a lado las siguientes 5 visualizaciones:

1. **Gráfico de Líneas:** Evolución temporal de ventas.
2. **Gráfico de Barras Agrupadas:** Comparativa entre Ventas y Gastos por día.
3. **Gráfico de Dispersión (Scatter Plot):** Relación entre Horas de Estudio y Nota de Examen.
4. **Histograma:** Distribución de frecuencia de notas (incluyendo estimación de densidad KDE en Seaborn).
5. **Diagrama de Caja (Boxplot):** Resumen estadístico y distribución de ventas.

---

## 📁 Estructura del Repositorio

* **`Gráficas_streamlit.py` / `app.py`:** Código fuente en Python adaptado con los comandos de Streamlit (`st.pyplot`) para construir el cuadro de mando interactivo.
* **`Graficas_streamlit.ipynb`:** Cuaderno de Jupyter / Google Colab para ejecutar y visualizar los 5 gráficos directamente dentro del entorno de desarrollo usando `plt.show()`.
* **`requirements.txt`:** Lista de dependencias y librerías necesarias para el despliegue automático en Streamlit Cloud.
* **`README.md`:** Documentación del proyecto.

---

## 🛠️ Tecnologías Utilizadas

* **Python 3.x**
* **Streamlit** (para el desarrollo de la interfaz web)
* **Matplotlib** (para visualizaciones base)
* **Seaborn** (para visualizaciones estadísticas avanzadas)
* **Pandas** y **NumPy** (para manipulación y generación de datos)

---

## 💻 Ejecución Local

Si deseas ejecutar la aplicación de Streamlit en tu máquina local, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/LucasFaura18/Pruebas_graficas.git](https://github.com/LucasFaura18/Pruebas_graficas.git)
   cd Pruebas_graficas
