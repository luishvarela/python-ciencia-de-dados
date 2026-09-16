# Estudos em Machine Learning & Data Science

Este repositório reúne meus notebooks pessoais de anotações, códigos conceituais e guias de referência rápida criados durante meus estudos de Ciência de Dados e Aprendizado de Máquina. O objetivo é consolidar a base matemática e computacional para futuros projetos de **Iniciação Científica (IC)** no **ICMC/USP**.

---

## Estrutura do Repositório

O projeto está organizado de forma modular, cobrindo o pipeline clássico de Ciência de Dados:

* **`notas-pandas.ipynb`**: Manipulação de dados tabulares, estruturas fundamentais (`Series` e `DataFrame`), técnicas de filtragem, ordenação, gerenciamento de memória (View vs. Copy), tratamento de valores nulos, agrupamentos com `groupby` e junções com `merge`.
* **`notas-matplotlib.ipynb`**: Fundamentos de visualização de dados, mapeamento da hierarquia `Figures` e `Axes`, gráficos estatísticos (linhas, dispersão, barras, histogramas) e matrizes de correlação com mapas de calor.
* **`notas-analise-e-pre-processamento.ipynb`**: Limpeza de dados reais utilizando o dataset do Titanic. Inclui engenharia de recursos, tratamento avançado de dados ausentes com imputação por mediana filtrada e detecção de *outliers* através de boxplots.
* **`notas-scikit-learn.ipynb`**: Introdução prática aos paradigmas de Machine Learning (Supervisionado e Não Supervisionado), cobrindo regressão linear, classificação linear, mapeamento espacial com kernels e algoritmos de agrupamento (*Clustering*) como o DBSCAN.

---

## Pipeline Prático Desenvolvido

Como aplicação prática desses estudos, o repositório demonstra um pipeline rigoroso de machine learning utilizando a base de dados **Iris**:
1. **Análise Exploratória (EDA)** com Seaborn e Matplotlib para validar a separabilidade das classes.
2. **Seleção de Algoritmo** robusta através de Validação Cruzada (*5-Fold Cross-Validation*) comparando **SVC**, **Random Forest** e **KNN**.
3. **Diagnóstico Final** com divisão determinística (`random_state=42`), avaliação via relatório de classificação e análise geométrica de erros com matriz de confusão.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

---

## 👤 Autor

Desenvolvido por **Luís Henrique Varela Medeiros Bezerra** 
* Aluno de Bacharelado em Ciência de Computação (BCC) — **ICMC/USP**
* [Meu GitHub](https://github.com/luishvarela)
