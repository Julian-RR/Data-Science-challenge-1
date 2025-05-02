# 🛍️ AluraStore LATAM — Análisis de Tiendas Online

Este proyecto consiste en un análisis exploratorio y visual de datos de cuatro tiendas simuladas en Latinoamérica. Se investiga su eficiencia, desempeño en ventas, calificaciones de clientes, productos clave y otros aspectos logísticos y comerciales.

El análisis está desarrollado en Python utilizando herramientas como pandas, matplotlib y seaborn.

---

## 📚 Aprendizaje previo

Antes de iniciar con el análisis principal, se desarrollaron y probaron funciones personalizadas reutilizables que forman la base del proyecto. Estas incluyen:

- `grafica_barras()` – Función para crear gráficos de barras con etiquetas personalizadas.
- `grafica_latitud_longitud()` – Visualiza coordenadas geográficas agrupadas y contadas.
- Funciones para determinar productos más y menos vendidos.
- Cálculos de eficiencia basados en ventas vs. gastos de envío.

Estas funciones están bien documentadas dentro del notebook y permiten modularizar el análisis para aplicar en diferentes subconjuntos de datos.

---

## 🧪 Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Collections (`Counter`)
- Jupyter Notebook / Google Colab

---

## 📁 Estructura del proyecto

- `AluraStoreLatam.ipynb`: Notebook principal con todo el flujo de trabajo.
- Celdas separadas por secciones:
  - Importación y preparación de datos
  - Funciones auxiliares
  - Análisis general por tienda
  - Visualizaciones geográficas
  - Evaluación de eficiencia y conclusiones

---

## 🔍 Qué se analiza

- 📦 Distribución de productos por categoría
- 💰 Ventas totales por tienda
- ⭐ Valoraciones promedio por tienda
- 📈 Comparativas de desempeño entre tiendas
- 📍 Ubicación geográfica de los pedidos
- 🚚 Costos de envío y relación con ingresos
- 🧠 Determinación de eficiencia y deficiencia operativa

---

## 📊 Visualizaciones utilizadas

- Gráficos de barras (verticales y horizontales)
- Gráficos circulares (*pie charts*)
- Gráficos de líneas (tendencias)
- Diagramas de dispersión (`scatter`)
- Mapas de calor (*heatmaps*) por coordenadas
- Etiquetas dinámicas con porcentajes y valores

---

## 💡 Conclusiones

Tras explorar múltiples métricas:

- La **Tienda 1** presenta los mayores ingresos, pero tiene también el gasto en envíos más elevado y la calificación más baja, lo cual cuestiona su eficiencia.
- La **Tienda 2**, con un producto digital como más vendido, logra equilibrio entre ventas, calificación y bajos costos.
- La **Tienda 4**, aunque con menor volumen de ventas y un pedido menos, muestra una calificación baja y eficiencia dudosa al considerar el margen neto entre ganancias y envíos.
- A través de coordenadas y conteo de ocurrencias, se identifican zonas de mayor actividad comercial.

Este análisis ayuda a **detectar patrones, debilidades y oportunidades de mejora** en la operación de tiendas digitales.

---

## 🚀 Cómo ejecutar

1. Abre el archivo `.ipynb` en [Google Colab](https://colab.research.google.com/) o en Jupyter Notebook local.
2. Ejecuta cada celda en orden desde el inicio.
3. Asegúrate de tener los datos cargados (si se usan archivos externos).

---

## ✍️ Autor

**[Julian Esteban Rendón Ruiz]**  
Estudiante de análisis de datos — Proyecto desarrollado como parte del curso de Data Science en Alura LATAM.

---
