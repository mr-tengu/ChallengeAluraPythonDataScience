# Desafío Alura Store - Análisis de Ventas y Rendimiento Latam

Este repositorio contiene la solución al desafío de Data Science "Alura Store Latam", cuyo objetivo es analizar el rendimiento de cuatro tiendas virtuales para ayudar a tomar la decisión estratégica de cuál de ellas debe ser vendida.

## 📋 Descripción del Proyecto

El señor Juan es dueño de cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) y necesita invertir en un nuevo negocio. Para obtener el capital necesario, ha decidido vender la tienda con el menor rendimiento. 

Este proyecto realiza un análisis de datos en Python (utilizando la librería `pandas`) sobre los registros de ventas de cada tienda para evaluar cinco métricas fundamentales:

1. **Facturación total:** Ingresos brutos generados por cada tienda.
2. **Categorías más populares:** Los tipos de productos con mayor volumen de ventas.
3. **Calificación promedio:** Nivel de satisfacción de los clientes.
4. **Productos más y menos vendidos:** Análisis de rotación de inventario específico.
5. **Costo promedio de envío:** Valor promedio que asumen los clientes por la entrega.

## 📊 Resultados Principales

Tras analizar las bases de datos, los resultados consolidados son los siguientes:

* **Facturación:** La **Tienda 4** presentó los ingresos más bajos con `$1,038,375,700.00`, frente a la Tienda 1 que lideró con `$1,150,880,400.00`.
* **Categoría Top:** En las cuatro tiendas, la categoría de productos más vendida fue **"Muebles"**.
* **Satisfacción:** Todas las tiendas mantienen una calificación promedio sólida, oscilando entre **3.98 y 4.05 estrellas**.
* **Envíos:** La **Tienda 4** tiene el costo promedio de envío más económico (`$23,459.46`).

## 🎯 Conclusión y Recomendación

A pesar de que la **Tienda 4** cuenta con los costos de envío más bajos y una buena calificación de sus clientes, es la tienda que genera la menor facturación económica total. 

Por lo tanto, la recomendación basada en los datos es que **el señor Juan debería vender la Tienda 4** para obtener liquidez e invertir en su nuevo proyecto.

## 🛠️ Tecnologías y Herramientas

* Python 3
* Librería `pandas`
* Google Colaboratory / Jupyter Notebook

## 🚀 Cómo usar este repositorio

1.  Clona el repositorio o descarga el archivo `AluraStoreLatam.ipynb`.
2.  Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com/) o ábrelo en tu entorno local de Jupyter.
3.  El código ya incluye las URLs directas a los archivos `.csv` originales alojados en GitHub, por lo que no necesitas descargar los datasets manualmente.
4.  Ejecuta las celdas secuencialmente para ver el proceso de carga, análisis y la conclusión.