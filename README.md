**Analise de Credito Previsao de Inadimplencia com Python e algoritmo Naive Bayes**

*Machine Learning: Naive Bayes*

## Análise de Crédito: Previsão de Inadimplência

**Introdução:**

Este projeto tem como objetivo desenvolver um modelo de classificação para predir a probabilidade de inadimplência de clientes de crédito. Utilizando um conjunto de dados contendo informações sobre renda, idade e histórico de crédito, foi treinado um modelo de árvore de decisão (GaussianNB).

**Metodologia:**

Coleta de Dados: O conjunto de dados, composto por 2000 registros.

* **Pré-processamento:**

    * Tratamento de valores ausentes: Valores ausentes na variável 'renda' foram imputados pela média, considerando a distribuição dos dados.
    * Padronização: Foi utilizado o StandardScaler para normalizar as features numéricas.

* **Modelagem:**

    * Um modelo de árvore de decisão (GaussianNB) foi treinado utilizando os dados pré-processados.

* **Avaliação:**
    
    * A acurácia do modelo foi de 93%.
    * A matriz de confusão (Figura 1) mostra que o modelo teve um bom desempenho na classificação dos clientes adimplentes, mas apresentou algumas dificuldades em classificar os inadimplentes.
 
      ![image](https://github.com/user-attachments/assets/722ff0ba-a14f-43fd-84f1-688d7e2a1421)


**Resultados:**

As variáveis mais importantes para a classificação foram a renda e o histórico de crédito. Isso indica que clientes com renda mais baixa e histórico de crédito negativo têm maior probabilidade de inadimplência.

**Conclusão:**

Este projeto demonstrou a viabilidade de utilizar árvores de decisão para prever a inadimplência de clientes de crédito. No entanto, há espaço para melhorias, como a inclusão de mais features e a exploração de outros algoritmos.
