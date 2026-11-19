# Análisis de planes de telefonía de Megaline

Proyecto académico individual de Bryant Martínez Tena desarrollado en TripleTen. Comparé el consumo y los ingresos mensuales de Surf y Ultimate.

## Evidencia

[Ver notebook completo](videogames_sales.ipynb). El nombre histórico del archivo y del repositorio corresponde a videojuegos, pero el contenido es de telecomunicaciones.

[Ver proyecto de videojuegos](https://github.com/bryant-martinez/megaline-telecom-analysis/blob/main/video_games.ipynb).

## Mi contribución

- Preparé cinco tablas de usuarios, planes, llamadas, mensajes e internet.
- Convertí fechas, agregué consumo por usuario y mes y calculé cargos según las tarifas.
- Comparé distribuciones e ingresos con visualizaciones y pruebas de hipótesis.

## Resultado y decisiones

El notebook reporta consumo medio de aproximadamente 16,649 MB para Surf y 17,271 MB para Ultimate. Surf supera en promedio sus 15 GB incluidos y Ultimate queda por debajo de sus 30 GB. Esto permite explorar el papel de los excedentes en los ingresos. Apliqué reglas de redondeo de facturación y conservé los cargos monetarios con sus decimales.

## Alcance

Análisis histórico de una muestra académica. Las asociaciones observadas no demuestran causalidad. El notebook conserva el historial de revisión del curso.

## Herramientas y archivos

Python, pandas, NumPy, Matplotlib, SciPy y Jupyter Notebook.

- `videogames_sales.ipynb` contiene el análisis.
- Los cinco archivos `megaline_*.csv` contienen los datos.

Para reproducirlo, instala pandas, numpy, matplotlib, scipy y jupyter. Abre el notebook, ajusta las rutas a los CSV de esta carpeta y ejecuta las celdas en orden.

## Autor

[Bryant Martínez Tena](https://www.linkedin.com/in/bryant-martinez/)
