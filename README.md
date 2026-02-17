# Projeto de Credit Scoring - Árvore de Decisão

Este repositório contém o desenvolvimento de um modelo de Machine Learning para a classificação de risco de crédito, utilizando algoritmos de Árvore de Decisão.

## 📌 Objetivo
O objetivo principal é classificar clientes em diferentes níveis de score, permitindo que uma instituição financeira tome decisões de concessão de crédito baseadas em dados.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 🚀 Etapas do Projeto
1.  **Carga de Dados:** Importação das bases de treino e teste previamente tratadas e balanceadas.
2.  **Treinamento:** Implementação do `DecisionTreeClassifier` utilizando o critério de **Gini** e `random_state=0`.
3.  **Avaliação:** Análise de performance utilizando métricas de Acurácia, Precision, Recall e F1-Score.
4.  **Visualização:** Plotagem da árvore de decisão completa e extração de sua profundidade.
5.  **Otimização:** Identificação das features de maior importância para simplificação do modelo.
6.  **Benchmarking:** Comparação de resultados com o modelo Naive Bayes.

## 📊 Principais Insights
* A Árvore de Decisão apresentou uma capacidade de generalização superior ao modelo Naive Bayes para este conjunto de dados específico.
* Foi possível reduzir o modelo às duas variáveis mais importantes sem perda drástica de performance, facilitando a explicabilidade do negócio.

---
Desenvolvido por [Emerson de Melo]
