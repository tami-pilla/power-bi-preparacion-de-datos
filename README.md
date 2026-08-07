# Preparación de Datos con Power Query

## Dataset

Para este proyecto se utilizó el dataset **Superstore Sales Analytics**, disponible en Kaggle:

https://www.kaggle.com/datasets/thuandao/superstore-sales-analytics

## Descripción del proyecto

Se preparó un conjunto de datos de ventas mediante Power Query, aplicando procesos de limpieza, transformación y modelado.

También se creó una tabla calendario (DimFechas), se establecieron las relaciones del modelo y se desarrollaron medidas DAX para preparar el conjunto de datos para su análisis y visualización.

## Diccionario de datos

| order_id | Identificador único de cada pedido. |
| order_date | Fecha en que se realizó el pedido. |
| ship_date | Fecha en que se envió el pedido. |
| ship_mode | Método de envío elegido para el pedido. |
| customer_name | Nombre del cliente. |
| segment | Segmento del cliente (Consumer, Corporate o Home Office). |
| country | País del cliente. |
| state | Estado o provincia. |
| market | Mercado geográfico. |
| region | Región dentro del mercado. |
| product_id | Identificador del producto. |
| category | Categoría principal del producto. |
| sub_category | Subcategoría del producto. |
| product_name | Nombre del producto. |
| sales | Importe de venta de la línea del pedido. |
| quantity | Cantidad de unidades vendidas. |
| discount | Descuento aplicado. |
| profit | Ganancia o pérdida obtenida. |
| shipping_cost | Costo de envío. |
| order_priority | Prioridad del pedido. |
| year | Año del pedido. |

## Procesos realizados

- Importación y validación del dataset.
- Corrección de tipos de datos.
- Conversión de valores decimales.
- Verificación de calidad de los datos.
- Creación de columnas calculadas.
- Creación de la tabla calendario (DimFechas).
- Modelado de datos.
- Desarrollo de medidas DAX.
