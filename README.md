![banner](./assets/banner.png)

# Stockeasy · Data Science & Statistical Computing

| Integrante | RM |
|---|---|
| [Guilherme Santos Nunes](https://github.com/sannunez) | RM558989 |
| [Kaique Zaffarani](https://github.com/Z4ffarani) | RM556677 |
| [Kairo da Silva Silvestre de Carvalho](https://github.com/KairoSilvestre) | RM558288 |
| [Pedro Josué Pereira Almeida](https://github.com/Pedro-Josue) | RM554913 |

Challenge 2025.2 · DASA · Engenharia de Software · FIAP

---

## O projeto Stockeasy

A **[FIAP](https://www.fiap.com.br)**, com o objetivo de auxiliar a rede de saúde integrada **[DASA](https://dasa.com.br)** no aprimoramento de seus processos internos, incentivou a criação de um sistema de controle de estoques dinâmico, que apoia decisões sobre compras, redistribuições e balanceamento de estoque entre unidades da rede.

## Esta entrega: Data Science & Statistical Computing

### Sprint 3

Modelagem preditiva utilizando técnicas de regressão para estimar a demanda laboratorial.

- Implementação de Regressão Linear, Regressão Ridge (L2) e Regressão Lasso (L1).
- Utilização de `GridSearchCV`/`RidgeCV`/`LassoCV` para otimização de hiperparâmetros (alfa).
- Análise de coeficientes para seleção de features.
- Exploração de Regressão Polinomial (2º e 3º grau) para capturar tendências não lineares nos dados.

### Sprint 4

Problema de classificação para determinar a confiabilidade de fornecedores com base em critérios de qualidade e logística.

- Criação de um dataset sintético de fornecedores com pontuações em certificados, rastreabilidade, suporte, logística e qualidade.
- Implementação do algoritmo **KNN (K-Nearest Neighbors)** para classificação.
- Otimização do valor de `k` via validação cruzada.
- Implementação e comparação com **Regressão Logística**.
- Avaliação dos modelos com Acurácia, Precisão, Recall, F1-Score e Matriz de Confusão.

| Entregável | Onde |
|---|---|
| Notebook da Sprint 3 | [`SPRINT3/SPRINT3_DS_SC.ipynb`](SPRINT3/SPRINT3_DS_SC.ipynb) |
| Base da Sprint 3 | [`SPRINT3/SPRINT3_DS_SC.csv`](SPRINT3/SPRINT3_DS_SC.csv) |
| Notebook da Sprint 4 | [`SPRINT4/SPRINT4_DS_SC.ipynb`](SPRINT4/SPRINT4_DS_SC.ipynb) |
| Base da Sprint 4 | [`SPRINT4/fornecedores.csv`](SPRINT4/fornecedores.csv) |

## Como executar

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Abra o notebook da sprint desejada; cada um lê a base que está na própria pasta.

---

## Tecnologias

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)
[![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)](https://matplotlib.org)
[![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat-square)](https://seaborn.pydata.org)
