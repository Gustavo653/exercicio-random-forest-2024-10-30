# Análise de Classificação do Conjunto de Dados Breast Cancer

## Descrição do Dataset

O conjunto de dados de Câncer de Mama contém 569 amostras com 30 características para cada amostra. Cada amostra é rotulada como uma das duas classes:
- **0**: Maligno
- **1**: Benigno

As 30 características incluem medições como o tamanho, textura e compactação das células. Esses dados são amplamente utilizados para criar e testar modelos de classificação binária.

## Resultados

### Relatório de Classificação - Árvore de Decisão

| Métrica         | Maligno | Benigno |
|-----------------|---------|---------|
| Precisão        | [0.90] | [0.97] |
| Recall          | [0.95] | [0.94] |
| F1-score        | [0.92] | [0.95] |
| **Precisão Geral** | **[0.9415204678362573]** |

### Relatório de Classificação - Random Forest

| Métrica         | Maligno | Benigno |
|-----------------|---------|---------|
| Precisão        | [0.98] | [0.96] |
| Recall          | [0.94] | [0.99] |
| F1-score        | [0.96] | [0.98] |
| **Precisão Geral** | **[0.9707602339181286]** |

### Matrizes de Confusão

- **Árvore de Decisão**:
  - ![image](https://github.com/user-attachments/assets/6311d209-ccda-4de0-892f-37b95f3f89da)

- **Random Forest**:
  - ![image](https://github.com/user-attachments/assets/648bc0c9-3ccc-4726-a002-b0df67b71bc4)

## Comparação dos Modelos

A **Random Forest** tem uma eficiência maior falando em precisão geral e F1-score por utilizar múltiplas árvores de decisão, o que reduz o risco de overfitting comparado à Árvore de Decisão única.
