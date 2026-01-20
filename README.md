**Análisis Predictivo y de Tendencias de Ventas E-commerce.**

Objetivos generales
- Identificar las tendencias de las ventas del mercado de comercialización de productos químicos industriales y alimentarios.
  
Objetivos específicos
- Visualización en gráfica de barras temporales de las ventas de los productos que se expresan en SKU en función del tiempo (meses) de los años 2024 y 2025.
- Detectar la rotación de cantidad de venta de los SKUs comparandolos entre  los años 2024 y 2025.

Análisis explorativo de Datos
- Para realizar una exploración y visualización de datos acertada se importaron las librerias: pandas para la manipulación y matplotlib y seaborn para las series temporales
- Al contar con datos de origen en formato Excel (.xlsx) de los años 2024 y 2025 fue necesario cambiar de formato mediante la función melt
- Posteriormente, se realizó un merge para juntar ambos archivos y poder comparar ambos años.
- Como verificación del melt y merge se analizó un SKU (PAA-160) mediante un filtrado de columna
- Al tener satisfactorio el resultado, se procedió a analizar todos los SKUs mediante la clase FacetGrid, para desglosar por cada SKU ya que cada SKU tiene diferentes cantidades de rotación de venta

Resultados
- Visualización en formato de gráfica de barras y conteo de todos los SKU de la empresa comercializados  durante los años 2024 y 2025.
- Diferencia entre las ventas de los años 2024 y 2025
  
Conclusiones
- Es de alta importancia la calidad de los datos desde el origen, dado que así, se obtiene el análisis e interpretación de los resultados necesarios para comunicarlos de manera efectiva a stakeholders.
- Se identificó que el 15% de los SKUs presentaban una tendencia creciente en el segundo semestre del año, recomendando su promoción para incentivar una mayor rotación de inventario
