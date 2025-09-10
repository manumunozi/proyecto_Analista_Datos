# Análisis de Ventas - Neptuno
# 📊 Resumen Ejecutivo
## Objetivo
Analizar datos históricos de ventas (1996-1998) para identificar patrones y realizar pronósticos futuros, considerando múltiples dimensiones como tiempo, categorías, productos y clientes.

## 🔧 Limpieza y Preparación de Datos
Conversión de la columna VENTAS de formato string a numérico

Unificación de columnas de fecha (Año, Mes, Día) en una columna Fecha datetime

Mapeo de nombres de meses en español a números para análisis temporal

## 📈 Análisis Exploratorio (EDA)
### Ventas por Año
1996: $208,088

1997: $617,125 (pico máximo)

1998: $440,664

### Ventas por Trimestre
Q1: $436,810 (mayor volumen)

Q2: $285,333

Q3: $233,684 (menor volumen)

Q4: $310,050

### Ventas por Categoría
Beverages: $267,890

Dairy Products: $234,527

Confections: $167,366

Condiments: $106,057

Grains/Cereals: $95,754

Productos Más Vendidos
Camembert Pierrot: $46,828

Alice Mutton: $32,700

Carnarvon Tigers: $29,173

Boston Crab Meat: $17,909

Aniseed Syrup: $3,044

Clientes Más Relevantes
Around the Horn: $13,392

Antonio Moreno Taquería: $7,026

B's Beverages: $6,090

Alfreds Futterkiste: $4,274

Ana Trujillo Emparedados y helados: $1,403

## 📊 Visualizaciones
El análisis incluye gráficas de:

Ventas por año, trimestre y categoría

Top 10 productos y clientes por ventas

Tendencia temporal de ventas
<img width="883" height="453" alt="{ADE80635-3A29-4DA5-A2B0-5E682FCFA7DB}" src="https://github.com/user-attachments/assets/668d14ad-b7ba-4497-b7e7-adc9f2e322bd" />


## 🎯 Hallazgos Clave
Tendencia temporal: Crecimiento significativo en 1997 seguido de disminución en 1998

Estacionalidad: Q1 muestra el mayor volumen de ventas, Q3 el más bajo

Categorías dominantes: Beverages y Dairy Products representan casi el 50% de las ventas

Productos estrella: Camembert Pierrot es el producto más vendido

Clientes prioritarios: Around the Horn es el cliente con mayor volumen de compras

## 🔮 Próximos Pasos

Análisis de tendencias estacionales más detallado

Segmentación de clientes por valor y frecuencia de compra

## ✅ Conclusión
El análisis reveló patrones estacionales claros, categorías y productos dominantes, y clientes clave. Estos insights proporcionan una base sólida para la toma de decisiones estratégicas y la planificación de ventas futuras.

## 🐍 Análisis en Python (Google Colab)

Puedes revisar el análisis completo en el notebook  

🔗 [Notebook en Colab](https://github.com/manumunozi/proyecto_Analista_Datos/blob/main/Analisis_Ventas_Neptuno.ipynb)


# 📊 Proyecto de Análisis de Ventas con Power BI y Python

Este proyecto combina Power BI y Python (Google Colab) para analizar ventas, identificar tendencias y visualizar métricas claves.  

---

### Ejemplos de Visualizaciones

📌 Relación ventas y diferencia con año pasado  
Se crea un grafico de dispersión dinamico que separa en 4 cuadrante los productos, en el eje y estan la ventas
en el x estan la diferencia porcentual de cada con respecto al año anterior. Hay una linea  vertical en cero (0%)
y una linea vertical que calcula el promedio de ventas de productos segun año-mes. Cada circulo representa un producto 
el color depende en que cuadrante este y el tamaño del numero de pedidos.

![Relacion ventas](https://github.com/manumunozi/proyecto_Analista_Datos/blob/main/grafico%20dispersi%C3%B3n.png)

📌 Ventas por categoría y año-mes  

![Ventas por Categoria](https://github.com/manumunozi/proyecto_Analista_Datos/blob/main/Grafico%20Columnas.png)

📌 Ventas por  año-mes  y categoría

![Ventas por Categoría](https://github.com/manumunozi/proyecto_Analista_Datos/blob/main/Graficos%20Barra.png)
---

## 📈 Dashboard en Power BI  

🔗 [Ver Reporte en Power BI](https://app.powerbi.com/view?r=eyJrIjoiMDRlYWM2MDctY2YwMi00ZTFjLWFmMDYtZDE4MjE5MzM0ZDYyIiwidCI6ImI1ZDc4OTI3LTI1ZDAtNDRhOS04MzcwLWQ4NmU1N2M3YmE5NiIsImMiOjR9)



-
