## Análisis predictivo de riesgos de incendios forestales en Galicia con información satelital y meteorológica mediante técnicas de inteligencia artificial
Repositorio que almacena los notebooks del código fuente en los que se ha desarrollado el piloto experimental y archivos cuya descarga fue manual a través de las páginas web correspondientes.
### Notebooks
- “Descarga_limpieza_datos.ipynb”. Muestra el código para extraer, automatizando, los datos meteorológicos y satelitales y su posterior limpieza, junto también al dataset de incendios históricos en España. A su vez, se añade una conexión a MongoDB para almacenar resultados intermedios y el dataset final compuesto por los tres conjuntos de datos mencionados.
- “Modelo_predictivo.ipynb”. Código para la importación el dataset mediante MongoDB para preprocesar, entrenar el modelo de random forest y predecir el riesgo de incendios en Galicia por municipios. Finalmente, se evalúa la predicción y se exporta sus resultados, junto con las variables, a la base de datos mencionada.

### Conjuntos de datos
- “Xlsx_20260322_181842_1.xlsx” y “Xlsx_20260322_181842_2.xlsx”. Partes de incendios en España desde 2010 a 2023.
- “Concellos_IGN.zip”. Shapefile de los municipios de Galicia.
