📊 Alura Store – Análisis de Ventas y Rendimiento
📌 Descripción del proyecto

Este proyecto corresponde al Desafío Alura Store – Data Science, cuyo objetivo es analizar el desempeño comercial de cuatro tiendas de la cadena Alura Store con el fin de apoyar una decisión estratégica de negocio: determinar qué tienda debería vender el Sr. Juan para invertir en un nuevo emprendimiento.

El análisis se realiza utilizando Python, aplicando técnicas de análisis de datos, visualización y exploración geográfica, simulando un escenario real de trabajo para una persona analista de datos.

🎯 Objetivo

Evaluar comparativamente el rendimiento de las cuatro tiendas a partir de:

Ingresos totales

Ventas por categoría de producto

Calificación promedio de los clientes

Productos más y menos vendidos

Costo promedio de envío

Distribución geográfica de las ventas (análisis extra)

Con base en estos factores, se entrega una recomendación final fundamentada en datos.

🛠️ Herramientas utilizadas

Python 3

Pandas – Manipulación y análisis de datos

Matplotlib – Visualización de gráficos

Folium – Visualización geográfica (mapas reales de calor)

Google Colab – Entorno de desarrollo

📂 Estructura del proyecto
alura-store-analisis/
│
├── README.md
├── alura_store_analisis.ipynb
└── data/
    ├── tienda_1.csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv


Los archivos CSV se cargan directamente desde el repositorio oficial de Alura mediante URLs.

📈 Análisis realizados
1. Ingresos totales por tienda

Se calculó la facturación total de cada tienda a partir de la suma de la columna Precio, permitiendo comparar el rendimiento económico general.

2. Ventas por categoría (por tienda)

Se analizaron las categorías más y menos vendidas de forma individual por tienda, identificando patrones de consumo y diferencias en el mix de productos.

3. Calificación promedio de clientes

Se calculó la media de la columna Calificación para evaluar el nivel de satisfacción de los clientes en cada tienda.

4. Productos más y menos vendidos

Se identificaron los productos con mayor y menor rotación por tienda, permitiendo detectar fortalezas comerciales y posibles problemas de inventario.

5. Costo promedio de envío

Se calculó el costo medio de envío por tienda para evaluar su impacto en la experiencia del cliente.

6. Análisis geográfico (Extra)

Utilizando las columnas lat y lon, se generaron mapas reales de calor para:

Analizar la concentración geográfica de ventas

Detectar patrones territoriales

Evaluar si alguna tienda presenta ventajas o debilidades según la ubicación

📊 Visualizaciones

El proyecto incluye distintos tipos de gráficos:

Gráficos de barras

Gráficos circulares (tortas)

Gráficos horizontales

Mapas reales de calor interactivos

Estas visualizaciones permiten una interpretación clara y accesible de los resultados, incluso para perfiles no técnicos.

🧠 Conclusión

Tras el análisis integral de todos los indicadores, se concluye que:

👉 La Tienda 4 presenta el menor desempeño global, considerando facturación, diversificación de categorías, rotación de productos y distribución geográfica.

✅ Recomendación final:

Vender la Tienda 4, ya que su salida genera el menor impacto negativo en el rendimiento total de la cadena y permite liberar capital para nuevas inversiones.

🚀 Cómo ejecutar el proyecto

Abrir el archivo alura_store_analisis.ipynb en Google Colab

Ejecutar las celdas en orden

Revisar los gráficos y el informe final incluido en el notebook

📚 Contexto académico

Este proyecto forma parte del curso:

Oracle + Alura | Data Science – Practicando Python para Data Science

Desafío orientado a desarrollar habilidades prácticas en análisis de datos y toma de decisiones basada en evidencia.
