<!-- HEADER BANNER -->
<div align="center">
  <img src="./assets/banner-binario.jpg" width="100%" alt="Cybersecurity & Binary Code Banner" />
</div>

<br />

<!-- HEADER WITH UNALM SHIELD -->
<table border="0" width="100%">
  <tr>
    <td width="78%" valign="top">
      <h1>📊 Applied Multivariate Analysis</h1>
      <h3>Statistical Inference, MANOVA/MANCOVA, PCA, Discriminant Analysis & Logistic Regression</h3>
      <p>
        👤 <b>Autor:</b> Brian Alva Aquino (<a href="https://github.com/blolchevere-ctrl">@blolchevere-ctrl</a>)<br />
        🎓 <b>Institución:</b> Universidad Nacional Agraria La Molina (UNALM)<br />
        📚 <b>Curso Académico:</b> Técnicas Multivariadas (EP4146)
      </p>
      <p>
        <img src="https://img.shields.io/badge/Language-R_%7C_Python-blue?style=flat-square&logo=r" alt="R y Python" />
        <img src="https://img.shields.io/badge/Format-Quarto_.qmd-75AADB?style=flat-square&logo=quarto" alt="Quarto" />
        <img src="https://img.shields.io/badge/Evaluations-2_Comprehensive_Exams-brightgreen?style=flat-square" alt="Status" />
      </p>
    </td>
    <td width="22%" align="center" valign="middle">
      <img src="./assets/escudo-unalm.png" width="120" alt="Escudo UNALM" />
    </td>
  </tr>
</table>

---

## 📋 Estructura de Evaluaciones del Curso

Este repositorio recopila las soluciones y reportes reproducibles elaborados en **Quarto (`.qmd`)** para las dos evaluaciones principales del curso de **Técnicas Multivariadas (EP4146)** de la UNALM.

---

### 📑 Prueba 1: Examen Parcial (`examen-parcial.qmd`)

Evaluación integral en un único documento maestro que abarca la inferencia avanzada, el modelado lineal multivariado y la reducción de dimensionalidad inicial:

- [x] **1. Inferencia Multivariada y Pruebas de Hipótesis**
  - Verificación y diagnóstico de Normalidad Multivariada (Pruebas de Mardia, Royston y gráficos Q-Q chi-cuadrado).
  - Inferencia sobre vectores de medias para muestras independientes y pareadas mediante el estadístico $T^2$ de Hotelling.
- [x] **2. Modelado MANOVA y MANCOVA**
  - Análisis de Varianza Multivariado bajo distintos diseños experimentales:
    - **DCA:** Diseño Completamente al Azar Multivariado.
    - **DBCA:** Diseño en Bloques Completamente al Azar Multivariado.
    - **DCA Factorial:** Interacciones complejas entre múltiples factores.
  - **MANCOVA:** Análisis de Covarianza Multivariado ajustado por covariables continuas.
  - Evaluación rigurosa de criterios de decisión multivariados (Wilks' Lambda, Pillai's Trace, Hotelling-Lawley Trace, Roy's Largest Root).
- [x] **3. Regresión Multivariada**
  - Ajuste de modelos lineales para múltiples variables de respuesta simultáneas ($Y_1, Y_2, \dots, Y_p$).
  - Estimación de parámetros, matriz de varianzas-covarianzas de errores y diagnóstico de residuos.
- [x] **4. Análisis de Componentes Principales (PCA)**
  - Reducción de dimensionalidad sobre matrices de covarianzas y de correlación.
  - Selección de componentes principales (Criterio de Kaiser, Scree Plot y porcentaje de varianza explicada acumulada).
  - Interpretación de cargas factoriales (*loadings*) y visualización mediante Biplots interactivos.

---

### 📑 Prueba 2: Examen Final (`examen-final.qmd`)

Evaluación integral en un único documento maestro centrado en técnicas de agrupación, clasificación supervisada y modelado categórico:

- [ ] **1. Análisis Factorial y de Correspondencia**
  - **Análisis Factorial Exploratorio (AFE):** Extracción de factores comunes y rotaciones ortogonales/oblicuas (Varimax, Promax).
  - **Análisis de Correspondencia Simple (ACS) y Múltiple (ACM):** Reducción dimensional para variables cualitativas y matrices de contingencia.
- [ ] **2. Análisis Discriminante**
  - Construcción y evaluación de modelos de clasificación supervisada:
    - **LDA:** Análisis Discriminante Lineal.
    - **QDA:** Análisis Discriminante Cuadrático.
    - **RDA:** Análisis Discriminante Regularizado.
  - Generación de fronteras de decisión, cálculo de matrices de confusión y evaluación de la Tasa de Error Aparente (APER).
- [ ] **3. Modelos de Regresión Logística**
  - **Regresión Logística Dicotómica:** Clasificación binaria, cálculo e interpretación de Odds Ratios.
  - **Regresión Logística Multinomial:** Modelado de respuestas categóricas nominales con más de dos niveles.
  - **Regresión Logística Ordinal:** Modelos de probabilidades acumuladas para respuestas con orden implícito.

---

## 📂 Estructura del Repositorio

```text
Applied-Multivariate-Analysis/
├── assets/
│   ├── banner-binario.jpg
│   └── escudo-unalm.png
├── parcial/
│   ├── examen-parcial.qmd       # Documento maestro Quarto (Código + Teoría)
│   ├── examen-parcial.html      # Reporte interactivo renderizado
│   └── data/                    # Datasets utilizados en el Examen Parcial
├── final/
│   ├── examen-final.qmd
