# 🛍️ Alura Store LATAM – Análisis de Rendimiento de Tiendas

Este proyecto realiza un análisis completo de las tiendas de **Alura Store LATAM** utilizando Python.  
El objetivo es identificar qué tienda presenta mejor desempeño en términos de ingresos, satisfacción del cliente, costos de envío y distribución geográfica de ventas.

El análisis fue desarrollado en el notebook **`AluraStoreLatam.ipynb`** e incluye gráficos, conclusiones y visualizaciones clave para respaldar las decisiones comerciales.

---

## 📘 Objetivos del proyecto

1. Analizar los **ingresos totales** de cada tienda.  
2. Evaluar las **calificaciones promedio** de los clientes.  
3. Identificar los **productos y categorías más vendidos**.  
4. Calcular el **costo de envío promedio**.  
5. Explorar la **distribución geográfica de las ventas** usando coordenadas (`latitud`, `longitud`).  
6. Generar **visualizaciones claras y profesionales** para resumir los hallazgos.

---

## 📂 Contenido del notebook

1. **Carga y limpieza de datos**
   - Importación de los archivos CSV de las 4 tiendas desde GitHub.
   - Estandarización de nombres de columnas y tratamiento de valores faltantes.

2. **Análisis financiero**
   - Cálculo del ingreso total (suma de precios).
   - Comparación de desempeño entre tiendas.

3. **Satisfacción del cliente**
   - Promedio de calificaciones por tienda.
   - Relación entre costo de envío y valoración de clientes.

4. **Análisis de productos**
   - Categorías más y menos vendidas.
   - Productos destacados por volumen de ventas.

5. **Análisis geográfico**
   - Visualización de ventas mediante coordenadas (`latitud`, `longitud`).
   - Mapas de dispersión y mapas de calor para detectar zonas de mayor actividad.

6. **Visualizaciones finales**
   - Gráfico de barras: **Ingresos Totales por Tienda**  
   - Gráfico de barras: **Calificación Promedio por Tienda**  
   - Gráfico circular: **Distribución de Categorías**  
   - Gráfico de dispersión: **Relación entre Calificación y Costo de Envío**

7. **Conclusiones**
   - Recomendación de la tienda más rentable y eficiente.
   - Sugerencia de qué tienda descontinuar.

---

## 📊 Principales hallazgos

| Métrica | Tienda 1 | Tienda 2 | Tienda 3 | Tienda 4 |
|----------|-----------|-----------|-----------|-----------|
| **Ingreso total (COP)** | Medio | 🟢 Alto | Medio | 🔴 Bajo |
| **Calificación promedio** | Alta | 🟢 Alta | Media | Alta |
| **Costo de envío promedio** | Medio | 🟢 Bajo | Medio | 🔴 Alto |
| **Desempeño geográfico** | Bueno | 🟢 Excelente | Medio | 🔴 Débil |

**Conclusión:**  
> La **Tienda 2** es la más recomendable para seguir con la venta de productos.  
> Presenta el mejor equilibrio entre **ingresos**, **calificaciones** y **costos de envío**.  
> La **Tienda 4** tiene bajo rendimiento y alta dispersión geográfica, por lo que se sugiere **dejar de vender en ella**.

---

## visualizaciones

### Ingresos Totales por Tienda
Comparación directa del ingreso generado por cada tienda.

### Calificación Promedio por Tienda
Evalúa la satisfacción del cliente en una escala de 1 a 5.

###  Distribución de Categorías
Muestra las categorías de productos más vendidas en la Tienda 2.

### 🔵 Relación entre Costo de Envío y Calificación
Revela el impacto de los costos logísticos sobre la satisfacción del cliente.

---

## 🧰 Tecnologías y librerías utilizadas

| Librería | Uso principal |
|-----------|----------------|
| **pandas** | Limpieza, manipulación y análisis de datos |
| **matplotlib** | Gráficos básicos (barras, líneas, pastel) |
| **seaborn** | Gráficos avanzados y estéticos |
| **folium** | Mapas interactivos y heatmaps geográficos |
| **fpdf** | Generación de reportes en PDF |
| **numpy** | Operaciones numéricas |
| **geopandas** *(opcional)* | Análisis espacial de ventas |

---

## ⚙️ Instalación y ejecución

### 1️⃣ Clonar el repositorio (o guardar el notebook)
```bash
git clone https://github.com/usuario/AluraStoreLatam.git
cd AluraStoreLatam
