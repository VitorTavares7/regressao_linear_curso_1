# Análise de Regressão Linear com Python — Curso Alura

Este notebook foi desenvolvido como parte do curso **"Data Science: testando relações com Regressão Linear"**, 
oferecido pela [Alura](https://www.alura.com.br/) dentro do programa **Oracle Next Education (ONE)** — trilha de formação em Data Science.

## 📊 Objetivo

Aplicar conceitos estatísticos e computacionais de **regressão linear** para analisar diferentes conjuntos de dados e compreender relações entre variáveis. 
O projeto inclui visualizações, criação e comparação de modelos, além de análise de multicolinearidade com VIF.

## 📁 Datasets utilizados

Os arquivos `.csv` utilizados estão presentes no repositório:

- `hoteis.csv` — dados sobre hotéis e seus preços
- `usina.csv` — dados operacionais de uma usina

## 🔎 Etapas desenvolvidas

### 🏨 Modelo de Regressão com `hoteis.csv`

- Leitura dos dados com `pandas`
- Análise gráfica da relação entre o **preço** e variáveis como:
  - `Estrelas`
  - `ProximidadeTurismo`
  - `Capacidade`
- Construção de modelos de regressão:
  - Simples (uma variável)
  - Múltipla (mais de uma variável)
- Comparação dos modelos e interpretação dos coeficientes
- Visualização com **Seaborn PairPlot**

### ⚡ Modelo de Regressão com `usina.csv`

- Leitura de um segundo conjunto de dados sobre uma usina
- Construção de um novo modelo de regressão para análise de desempenho ou produção
- Aplicação dos mesmos princípios para comparação entre variáveis e impacto no resultado
- Cálculo do **VIF (Variance Inflation Factor)** para avaliação da multicolinearidade
- Interpretação dos coeficientes gerados
  
## 📚 Bibliotecas utilizadas

- `pandas` e `numpy` para manipulação e análise de dados
- `seaborn` e `matplotlib.pyplot` para visualizações
- `statsmodels.api` para regressão linear
- `statsmodels.stats.outliers_influence` para cálculo do VIF

## 🧠 Conceitos explorados

- Regressão linear simples e múltipla
- Multicolinearidade
- Visualização de relações entre variáveis
- Interpretação estatística de coeficientes
- Intervalos de confiança

---

**Desenvolvido por Vitor Tavares, Analista de Dados**
