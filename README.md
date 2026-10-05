# 🏗️ Hito 1: Análisis de Deflexión en Viga Simplemente Apoyada

Este repositorio contiene el flujo de trabajo reproducible para comparar datos sintéticos de deflexión medida con la predicción teórica lineal elástica (Euler-Bernoulli) para una viga simplemente apoyada con carga puntual centrada.

---

## 📂 Estructura del Repositorio

* 📁 **`data/`**: Contiene los datos originales y parámetros del caso (`datos_viga.csv` y `parametros_viga.xlsx`). *Estos archivos no han sido modificados.*
* 📊 **`analisis/`**: Contiene la planilla `analisis_viga.xlsx` con el cálculo de la inercia, las deflexiones teóricas, la conversión de unidades y la diferencia relativa, todo automatizado mediante fórmulas.
* 📈 **`figuras/`**: Contiene la gráfica comparativa `carga_deflexion.png`.
* 📄 **`reportes/`**: Contiene el código fuente en LaTeX (`main.tex`), el archivo de bibliografía (`referencias.bib`) y la nota técnica final compilada en PDF.
* 🤖 **`USO_IA.md`**: Declaración sobre el uso de herramientas de IA generativa durante el desarrollo del trabajo.

---

## ⚙️ Instrucciones de Reproducibilidad

### Requisitos Previos
* Software de hojas de cálculo (Microsoft Excel recomendado para garantizar la compatibilidad de las fórmulas).
* Entorno de compilación LaTeX (se recomienda Overleaf, o una instalación local con TeXstudio/VSCode).

### Pasos para reproducir los resultados

Para auditar correctamente este trabajo, se recomienda seguir el flujo lógico de los datos:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/Almendraaaaa13/EvaluacionU1_OlivaresAlmendra.git](https://github.com/Almendraaaaa13/EvaluacionU1_OlivaresAlmendra.git)
   cd EvaluacionU1_OlivaresAlmendra
