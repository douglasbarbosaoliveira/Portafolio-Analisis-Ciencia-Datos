# Análisis de los Determinantes de la Felicidad Global 🌍

<div align="center">
  <a href="#-versión-en-español">🇪🇸 Español</a> |
  <a href="#-english-version">🇺🇸 English</a> |
  <a href="#-versão-em-português">🇧🇷 Português</a>
</div>

---

## 🇪🇸 Versión en Español

### 📋 Descripción del Proyecto
Este repositorio contiene un análisis econométrico enfocado en comprender los determinantes de la felicidad en 122 países, basado en datos del **World Happiness Report 2022**.

El estudio compara un modelo de **Regresión Lineal Simple** (considerando solo el PIB) contra un modelo de **Regresión Lineal Múltiple** para probar la hipótesis de que la felicidad es un fenómeno multidimensional. Se integran factores como la salud, la generosidad y la corrupción política para mejorar la capacidad predictiva del modelo.

### 📂 Contenido del Repositorio

| Archivo | Descripción |
| :--- | :--- |
| **[A1.2_Happiness_Analysis.ipynb](A1.2_Happiness_Analysis.ipynb)** | **Código Fuente:** Jupyter Notebook con la fusión de datos, modelos de regresión OLS y visualizaciones comparativas. |
| **[A1.2_Happiness_Analysis.html](A1.2_Happiness_Analysis.html)** | **Reporte Visual:** Versión exportada en HTML para visualizar el análisis directamente en el navegador. |
| **[WHR2022.csv](WHR2022.csv)** | **Dataset Extendido:** Conjunto de datos externo utilizado para enriquecer el modelo con variables de Salud y Sociales. |
| **[A1.2_Felicidad_y_GDP.csv](A1.2_Felicidad_y_GDP.csv)** | **Dataset Base:** Datos originales conteniendo Felicidad y PIB (Log GDP). |

### 💾 Sobre la Base de Datos
Los datos provienen del **Reporte Mundial de la Felicidad 2022**, una encuesta histórica sobre el estado del bienestar global.

#### Diccionario de Variables
* **Variable Objetivo:** `Felicidad` (Puntaje de felicidad: 0-10).
* **Económica:** `Log_GDP` (PIB per cápita en escala logarítmica).
* **Salud:** `Life_Expectancy` (Esperanza de vida saludable al nacer).
* **Social/Ética:** `Generosity` (Comportamiento altruista y donaciones).
* **Política:** `Corruption` (Percepción de corrupción en gobierno/negocios).

### 🔍 Hallazgos Clave
* El **Modelo Múltiple** ($R^2 \approx 0.62$) triplicó el poder explicativo del **Modelo Simple** ($R^2 \approx 0.22$).
* La **Salud** demostró ser un predictor mucho más fuerte que el PIB al analizarse juntos, sugiriendo que el dinero genera felicidad principalmente a través de la salud.
* La **Confianza Institucional** (baja corrupción) resultó ser estadísticamente significativa para el bienestar nacional.

### 🛠️ Tecnologías Utilizadas
* **Python 3**
* **Pandas** (Manipulación y Cruce de datos)
* **Statsmodels** (Regresión OLS y Pruebas Estadísticas)
* **Seaborn / Matplotlib** (Visualización de datos)

---

## 🇺🇸 English Version

### 📋 Project Description
This repository contains an Econometric Analysis focused on understanding the determinants of happiness across 122 countries, based on the **World Happiness Report 2022**.

The study compares a **Simple Linear Regression** model (considering only GDP) against a **Multiple Linear Regression** model to test the hypothesis that happiness is multidimensional. It integrates factors such as health, generosity, and political corruption to improve predictive power.

### 📂 Repository Contents

| File | Description |
| :--- | :--- |
| **[A1.2_Happiness_Analysis.ipynb](A1.2_Happiness_Analysis.ipynb)** | **Source Code:** Jupyter Notebook containing the data merging, OLS regression models, and comparative visualizations. |
| **[A1.2_Happiness_Analysis.html](A1.2_Happiness_Analysis.html)** | **Visual Report:** HTML version exported for viewing the analysis directly in the browser. |
| **[WHR2022.csv](WHR2022.csv)** | **Extended Dataset:** The external dataset used to enrich the model with Health and Social variables. |
| **[A1.2_Felicidad_y_GDP.csv](A1.2_Felicidad_y_GDP.csv)** | **Base Dataset:** The original dataset containing Happiness and GDP data. |

### 💾 About the Data
The data originates from the **World Happiness Report 2022**, a landmark survey of the state of global happiness.

#### Variable Dictionary
* **Target Variable:** `Felicidad` (Happiness Score: 0-10).
* **Economic:** `Log_GDP` (GDP per capita in logarithmic scale).
* **Health:** `Life_Expectancy` (Healthy life expectancy at birth).
* **Social/Ethical:** `Generosity` (Residual of regressing national average of donations).
* **Political:** `Corruption` (Perceptions of corruption in government/business).

### 🔍 Key Findings
* The **Multiple Model** ($R^2 \approx 0.62$) tripled the predictive power of the **Simple Model** ($R^2 \approx 0.22$).
* **Health (Life Expectancy)** proved to be a stronger predictor than GDP when analyzed together, suggesting that money buys happiness primarily through health.
* **Institutional Trust** (low corruption) is statistically significant for national well-being.

### 🛠️ Tech Stack
* **Python 3**
* **Pandas** (Data Manipulation & Merging)
* **Statsmodels** (OLS Regression & Statistical Tests)
* **Seaborn / Matplotlib** (Data Visualization)

---

## 🇧🇷 Versão em Português

### 📋 Descrição do Projeto
Este repositório contém uma análise econométrica focada em compreender os determinantes da felicidade em 122 países, com base no **World Happiness Report 2022**.

O estudo compara um modelo de **Regressão Linear Simples** (apenas PIB) contra um modelo de **Regressão Linear Múltipla** para testar a hipótese de que a felicidade é multidimensional. Fatores como saúde, generosidade e corrupção política são integrados para melhorar o poder preditivo.

### 📂 Conteúdo do Repositório

| Arquivo | Descrição |
| :--- | :--- |
| **[A1.2_Happiness_Analysis.ipynb](A1.2_Happiness_Analysis.ipynb)** | **Código Fonte:** Jupyter Notebook contendo a fusão de dados, modelos de regressão OLS e visualizações comparativas. |
| **[A1.2_Happiness_Analysis.html](A1.2_Happiness_Analysis.html)** | **Relatório Visual:** Versão exportada em HTML para visualizar a análise diretamente no navegador. |
| **[WHR2022.csv](WHR2022.csv)** | **Dataset Estendido:** Conjunto de dados externo usado para enriquecer o modelo com variáveis de Saúde e Sociais. |
| **[A1.2_Felicidad_y_GDP.csv](A1.2_Felicidad_y_GDP.csv)** | **Dataset Base:** Dados originais contendo Felicidade e PIB. |

### 💾 Sobre a Base de Dados
Os dados originam-se do **Relatório Mundial da Felicidade 2022**, uma pesquisa histórica sobre o estado do bem-estar global.

#### Dicionário de Variáveis
* **Variável Alvo:** `Felicidad` (Pontuação de felicidade: 0-10).
* **Econômica:** `Log_GDP` (PIB per capita em escala logarítmica).
* **Saúde:** `Life_Expectancy` (Expectativa de vida saudável ao nascer).
* **Social/Ética:** `Generosity` (Generosidade e comportamento altruísta).
* **Política:** `Corruption` (Percepção de corrupção no governo/negócios).

### 🔍 Principais Resultados
* O **Modelo Múltiplo** ($R^2 \approx 0.62$) triplicou o poder explicativo do **Modelo Simples** ($R^2 \approx 0.22$).
* A **Saúde** provou ser um preditor mais forte que o PIB quando analisados juntos, sugerindo que o dinheiro compra felicidade principalmente através da saúde.
* A **Confiança Institucional** (baixa corrupção) é estatisticamente significativa para o bem-estar nacional.

### 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** (Manipulação e Fusão de dados)
* **Statsmodels** (Regressão OLS e Testes Estatísticos)
* **Seaborn / Matplotlib** (Visualização de dados)

---
