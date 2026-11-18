# 📊 Dashboard Interactivo de Ventas con Python y Plotly

Proyecto práctico desarrollado como parte de mi formación en un **curso de Data Analytics**. El objetivo principal de esta práctica fue construir un tablero de control (dashboard) visual, limpio e interactivo para analizar el rendimiento comercial a partir de un conjunto de datos previamente procesado (`ventas_limpios`).

## 🎯 Objetivos de la Práctica
* **Agrupación y transformación de datos:** Uso de `pandas` para calcular métricas clave (KPIs) y resumir ventas por mes, categoría y producto.
* **Diseño de cuadrículas complejas (Subplots):** Implementación de `make_subplots` en Plotly utilizando un sistema de 6 columnas (`colspan`) para combinar tarjetas de indicadores en la parte superior, un gráfico de ancho completo en el centro y dos gráficos en paralelo en la base.
* **Visualización efectiva:** Selección del tipo de gráfico adecuado según la variable a analizar (líneas para series temporales, torta/donut para proporciones y barras para rankings) manteniendo una paleta de colores coherente.

## 🧩 Estructura del Dashboard
1. **Tarjetas de Indicadores (KPIs):**
   * **Facturación Total:** Suma monetaria total de las ventas registradas.
   * **Operaciones Registradas:** Cantidad total de transacciones.
   * **Productos Diferentes:** Conteo de ítems únicos comercializados.
2. **Evolución de Ventas Mensuales:** Gráfico de líneas con área sombreada que muestra la tendencia de ingresos mes a mes.
3. **Distribución por Categoría:** Gráfico de anillo (*Donut Chart*) ubicado en la parte inferior izquierda que representa la participación porcentual de las principales categorías.
4. **Top 10 Productos:** Gráfico de barras vertical ubicado en paralelo a la derecha con los 10 artículos de mayor facturación.

## 🛠️ Tecnologías Utilizadas
* **Python 3**
* **Pandas** (manipulación y agrupación de datos)
* **Plotly (`graph_objects` & `subplots`)** (visualización interactiva)

## 🚀 Cómo ejecutarlo
1. Asegúrate de tener instaladas las librerías necesarias:
   ```bash
   pip install pandas plotly
