# Qualidade de Vinhos Tintos: Análise e Machine Learning

Kauane dos Santos Leite  
Universidade Federal de Pernambuco (UFPE)  
Estatística  
Introdução à Ciência de Dados

## Sobre o projeto

Este projeto tem como objetivo analisar dados físico-químicos de vinhos tintos e investigar como essas características podem contribuir para a classificação da qualidade dos vinhos por meio de técnicas de Machine Learning.

## Base de dados

Foi utilizado o conjunto de dados **Red Wine Quality**, disponibilizado pela UCI Machine Learning Repository, contendo 1.599 observações e 11 variáveis físico-químicas, além da variável qualidade.

## Metodologia

O projeto foi desenvolvido em Python e contemplou:

- Análise exploratória dos dados;
- Preparação e divisão da base de dados;
- Construção de modelos de classificação;
- Avaliação e comparação dos resultados.

Foram utilizados dois modelos:

1. Árvore de Decisão (*Decision Tree*);
2. Floresta Aleatória (*Random Forest*).

## Resultados

Os modelos foram avaliados por métricas de desempenho, incluindo acurácia, acurácia balanceada, F1-score e coeficiente Kappa de Cohen.

A Floresta Aleatória apresentou desempenho superior ao da Árvore de Decisão nos resultados obtidos no conjunto de teste.

## Arquivos do projeto

- `Relatorio_vinhos.pdf`: relatório final do trabalho;
- `Códigos_do_projeto_e_resultados.ipynb`: notebook com o desenvolvimento da análise e dos modelos;
- `relatorio_vinhos.qmd`: arquivo-fonte do relatório;
- `distribuicao_qualidade.png`: gráfico da distribuição da qualidade;
- `matriz_correlacao.png`: matriz de correlação das variáveis;
- `winequality-red.csv`: base de dados utilizada.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- R e Quarto
