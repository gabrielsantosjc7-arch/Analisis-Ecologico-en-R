# Análisis Ecológico en R

Este repositorio reúne diversos análisis estadísticos aplicados a datos ecológicos y biológicos, realizados con **R** y documentados mediante **Quarto**.  
Cada carpeta contiene el script de análisis, el archivo `.qmd`  generado y los conjuntos de datos empleados (datasets abiertos o integrados en R).

---

## 🎯 Objetivos

- Aplicar diferentes enfoques estadísticos para el análisis de datos ecológicos.  
- Explorar las relaciones entre variables ambientales y biológicas mediante técnicas multivariadas.  
- Fortalecer la práctica de escritura reproducible con **Quarto** y buenas prácticas en análisis de datos.

---

## 🧩 Contenido del repositorio

| Carpeta | Descripción | Técnicas principales |
|----------|--------------|---------------------|
| **Análisis exploratorio** | Resumen de datos, visualización inicial y detección de patrones. | Histogramas, Boxplots, Correlaciones |
| **Índices ecológicos** | Cálculo de diversidad, equidad y rarefacción. | Shannon, Simpson, rarefacción |
| **Pruebas de hipótesis** | Comparaciones entre grupos y pruebas paramétricas/no paramétricas. | t-test, ANOVA, Kruskal-Wallis |
| **PCA-nMDS** | Reducción de dimensionalidad y ordenación ecológica. | PCA, NMDS, `envfit` |
| **CCA-RDA** | Análisis canónico de correspondencia y redundancia. | CCA, RDA, R² ajustado |
| **Clúster-Discriminante** | Agrupamiento y clasificación de comunidades. | Cluster jerárquico, LDA |
| **Regresiones lineales** | Modelos simples y múltiples. | lm(), diagnóstico de residuos |
| **MANOVA-perMANOVA** | Comparaciones multivariadas entre grupos. | MANOVA, perMANOVA |
| **GLM & GLMM** | Modelos lineales generalizados y mixtos. | Poisson, Binomial, efectos aleatorios |

---

## 📊 Datasets utilizados

Se emplearon **conjuntos de datos libres** integrados en R o disponibles públicamente:
- `iris`
- `palmerpenguins`
- `varespec` y `varechem` (paquete *vegan*)
- `USArrests`

---

## 💡 Conclusiones generales

- Los métodos multivariados permiten identificar gradientes ecológicos y patrones de comunidad.  
- La visualización adecuada mejora la interpretación de los resultados.  
- Documentar cada análisis en **Quarto** facilita la transparencia y reproducibilidad científica.

---

## ⚙️ Tecnologías utilizadas

- **R (tidyverse, vegan, MASS, ggplot2, dplyr, etc.)**  
- **Quarto** para informes reproducibles  
- **GitHub** para control de versiones y documentación

---

## 🧠 Autor

**Gabriel Santos**  
Biólogo | Análisis de datos | Consultoría ambiental  
📧 gabrielsantosjc7@gmail.com  
