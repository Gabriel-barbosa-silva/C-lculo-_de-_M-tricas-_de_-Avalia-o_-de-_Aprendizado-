# Análise de Métricas de Classificação

## Descrição do Projeto
Este projeto tem como objetivo principal demonstrar o cálculo das principais métricas de avaliação para modelos de classificação de dados. O script implementa as fórmulas para **acurácia**, **sensibilidade (recall)**, **especificidade**, **precisão** e **F-score** a partir de uma matriz de confusão.

A base de dados utilizada para o cálculo das métricas pode ser escolhida de forma arbitrária, sendo o foco principal do projeto a implementação e o entendimento das fórmulas de avaliação.
A Base de dados usa foi https://www.kaggle.com/datasets/crawford/emnist?resource=download 
## Estrutura do Projeto
- `projeto.ipynb`: Notebook do Google Colab que contém o código para o cálculo das métricas.
- `README.md`: Este arquivo, que descreve o projeto.

## Como Executar o Projeto

1.  **Acesso ao Google Colab:** Abra o arquivo `projeto.ipynb` no Google Colab.
2.  **Importação dos Dados:** Faça o upload do seu arquivo de dados para o ambiente de execução do Colab.
3.  **Execução do Código:** Execute as células do notebook para calcular e exibir a matriz de confusão e as métricas de avaliação.

O código está estruturado para ser facilmente adaptado a diferentes bases de dados, bastando ajustar o nome das colunas de rótulos verdadeiros e previsões.

## Métricas Calculadas
As seguintes métricas são calculadas com base na matriz de confusão:

- **Acurácia:** Proporção de previsões corretas.
- **Sensibilidade (Recall):** Capacidade do modelo de identificar corretamente os casos positivos.
- **Especificidade:** Capacidade do modelo de identificar corretamente os casos negativos.
- **Precisão:** Proporção de verdadeiros positivos em relação a todas as previsões positivas.
- **F-score:** Média harmônica entre precisão e sensibilidade.

## Contribuições
Sinta-se à vontade para abrir issues ou pull requests para melhorias.

---
