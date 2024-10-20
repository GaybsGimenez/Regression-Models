# Estudo de Regressão Linear Simples

Este projeto realiza uma análise básica usando regressão linear simples para entender a relação entre a idade e o custo de planos de saúde. A base de dados utilizada contém apenas 10 registros, portanto, não foi realizada a separação entre conjunto de treinamento e teste. O foco principal é explorar o funcionamento do algoritmo de regressão linear e interpretar os resultados.

## Descrição do Projeto

- **Base de Dados:** A base de dados utilizada contém registros de idades e os respectivos custos de planos de saúde.
- **Objetivo:** O objetivo é prever o custo de um plano de saúde com base na idade do cliente usando um modelo de regressão linear simples.
- **Análise de Correlação:** Inicialmente, foi calculado o coeficiente de correlação entre idade e custo, resultando em uma correlação forte e positiva.
- **Modelagem:** O modelo de regressão linear foi treinado com todos os dados, e foi avaliado com base no coeficiente de determinação \(R^2\) e na análise dos resíduos.
- **Visualização:** Foram gerados gráficos para visualizar a relação entre as variáveis e os resíduos do modelo, utilizando bibliotecas como Plotly e Yellowbrick.

## Conclusões

O modelo de regressão linear apresentou um bom ajuste aos dados, com um coeficiente de determinação \(R^2\) de 0,867, explicando a maior parte da variabilidade do custo em função da idade. No entanto, a análise dos resíduos sugere que pode haver algumas limitações, especialmente em casos específicos onde o modelo não foi tão preciso.
