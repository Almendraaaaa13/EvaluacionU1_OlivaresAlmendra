# Datos del Hito 1

Este repositorio contiene el flujo de trabajo reproducible para comparar datos sintéticos de deflexión medida con la predicción teórica lineal elástica (Euler-Bernoulli) para una viga simplemente apoyada con carga puntual centrada.



\## Estructura del repositorio



\* \*\*`data/`\*\*: Contiene los datos originales y parámetros del caso (`datos\_viga.csv` y `parametros\_viga.xlsx`). Estos archivos no han sido modificados.

\* \*\*`analisis/`\*\*: Contiene la planilla `analisis\_viga.xlsx` con el cálculo de la inercia, las deflexiones teóricas, la conversión de unidades y la diferencia relativa, todo automatizado mediante fórmulas.

\* \*\*`figuras/`\*\*: Contiene la gráfica comparativa `carga\_deflexion.png`.

\* \*\*`reportes/`\*\*: Contiene el código fuente en LaTeX (`main.tex`), el archivo de bibliografía (`referencias.bib`) y la nota técnica final compilada en PDF.

\* \*\*`USO\_IA.md`\*\*: Declaración sobre el uso de herramientas de IA generativa durante el desarrollo del trabajo.



\## Instrucciones de reproducibilidad



Para rastrear los cálculos, abra el archivo `analisis\_viga.xlsx` y revise las fórmulas en las columnas de deflexión teórica y diferencia relativa, las cuales referencian directamente los parámetros geométricos y mecánicos. La nota técnica fue redactada y compilada utilizando Overleaf.

