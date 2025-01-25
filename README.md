# Comercio-electronico
Análisis y visualización de una base de datos de comercio electrónico de Brasil con SQL y Python.

El archivo analiza un conjunto de datos de comercio electrónico de la plataforma brasileña Olist, con el objetivo de explorar y extraer información valiosa sobre las operaciones comerciales, patrones de clientes y desempeño de productos. Aquí está un resumen de lo que se hizo:
**1. Contexto**
El conjunto de datos incluye información sobre pedidos, clientes, productos, vendedores, reseñas y métodos de pago.
Utiliza SQLite para almacenar y consultar los datos, junto con Python para análisis y visualización.
**2. Análisis Realizado**
*Exploración de datos:*
Revisión de las tablas principales, incluyendo pedidos, clientes, productos y vendedores.
Visualización de las distribuciones de estados, categorías de productos y tendencias temporales.
*Análisis descriptivo:*
Patrones de pedidos: Identificación de picos en Navidad y días de semana más activos.
Distribución de clientes: Análisis geográfico y demográfico por estados y ciudades.
Precios de pedidos: Evaluación del valor promedio y rangos de costos.
*Tiempos de entrega:*
Comparación de tiempos de entrega por ciudad.
Análisis de variaciones estacionales en los tiempos de envío.
*Segmentación de clientes:*
Segmentación mediante el modelo RFM (Recencia, Frecuencia, Valor Monetario).
Identificación de grupos como "Campeones" y "Clientes perdidos".
*Valor de vida del cliente (CLV):*
Cálculo del CLV por cliente y análisis de distribución geográfica.
*Reseñas y comentarios:*
Análisis de puntuaciones de reseñas y motivos principales de insatisfacción (retrasos en envíos).
*Afinidad de productos:*
Identificación de productos frecuentemente comprados juntos.
Visualización de relaciones entre categorías mediante gráficos de red.
*Desempeño de vendedores:*
Análisis de puntuaciones de reseñas y ventas totales por vendedor.
Comparación de tiempos de envío entre vendedores grandes y pequeños.
*Conversión de clientes potenciales:*
Evaluación de tasas de conversión por canal de adquisición.
**3. Conclusiones principales**
*Crecimiento constante:*
Olist mostró un crecimiento en pedidos durante el período analizado, con un aumento significativo en Navidad.
*Patrones de consumo:*
Los clientes compran más entre semana y prefieren ciertas categorías de productos como "Salud y belleza".
*Problemas operativos:*
Los tiempos de envío varían significativamente entre ciudades, con retrasos comunes en temporadas altas.
*Satisfacción del cliente:*
Las quejas se centran principalmente en retrasos en los envíos.
*Valor del cliente:*
El CLV se concentra en ciudades grandes como São Paulo y Río de Janeiro.
*Segmentación efectiva:*
Identificación de grupos de clientes para estrategias personalizadas.
*Vendedores pequeños y grandes:*
Los pequeños suelen ser más rápidos en envíos, pero tienen menos volumen de pedidos.


***Recomendaciones***
Mejorar los tiempos de envío, especialmente en ciudades con mayores retrasos.
Optimizar estrategias de adquisición en canales de alta conversión como búsqueda orgánica y paga.
Enfocar campañas de retención en clientes de alto valor y segmentos en riesgo, como "Clientes por dormir".
