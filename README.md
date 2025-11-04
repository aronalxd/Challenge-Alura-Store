# Alura Store LATAM – Análisis de Ventas y Rendimiento de Tiendas

Este proyecto analiza el rendimiento de las distintas tiendas de **Alura Store LATAM** utilizando Python.  
El objetivo principal es identificar cuál de las tiendas presenta mejor desempeño comercial y geográfico,  
analizando métricas de ingresos, calificaciones, categorías vendidas y distribución de ventas por ubicación.

---

## 📘 Descripción general

El notebook **`AluraStoreLatam.ipynb`** contiene un análisis exploratorio y visual de datos provenientes de cuatro tiendas digitales.  
Cada tienda tiene registros de ventas con variables como:

- `Precio`: monto de la venta  
- `Calificación`: satisfacción del cliente  
- `Costo de envío`: costo logístico (pagado por el cliente)  
- `Categoría del Producto`: tipo de producto vendido  
- `latitud` y `longitud`: ubicación geográfica de la compra  

A través de este análisis se busca responder preguntas como:
- ¿Qué tienda genera más ingresos?
- ¿Qué categorías de productos son más populares?
- ¿Qué tienda tiene mejor calificación de clientes?
- ¿Cómo se distribuyen las ventas geográficamente?
- ¿Qué tienda presenta bajo rendimiento y debería ser descontinuada?

---

## 📊 Contenido del análisis

1. **Carga y limpieza de datos**
   - Lectura de archivos CSV desde GitHub.
   - Normalización de nombres de columnas y manejo de valores nulos.

2. **Análisis financiero**
   - Cálculo de ingresos totales por tienda.
   - Comparación de ventas por categoría.

3. **Satisfacción del cliente**
   - Promedio de calificaciones por tienda.
   - Detección de correlaciones entre precio y calificación.

4. **Costo de envío**
   - Análisis del costo promedio pagado por los clientes.
   - Comparativa entre tiendas.

5. **Análisis geoespacial**
   - Visualización de ventas mediante coordenadas (`latitud`, `longitud`).
   - Mapas de dispersión y mapas de calor (heatmaps) por tienda.
   - Identificación de regiones con mayor concentración de ventas.

6. **Conclusiones**
   - Tienda recomendada para continuar vendiendo: **Tienda 2**  
   - Tienda recomendada para dejar de operar: **Tienda 4**

---

## 🧰 Tecnologías y librerías utilizadas

| Librería | Uso |
|-----------|-----|
| `pandas` | Limpieza, manipulación y análisis de datos |
| `matplotlib` | Visualizaciones gráficas |
| `seaborn` | Gráficos estadísticos y mapas de calor |
| `folium` | Creación de mapas interactivos (heatmaps) |
| `numpy` | Cálculos numéricos |
| `geopandas` *(opcional)* | Análisis geográfico avanzado |

---

## ⚙️ Instalación y ejecución

### 1️⃣ Requisitos previos
Asegúrate de tener instalado Python 3.9 o superior.

### 2️⃣ Instalar dependencias
Crea un entorno virtual (opcional) y ejecuta:

```bash
pip install pandas matplotlib seaborn folium fpdf geopandas





