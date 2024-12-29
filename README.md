# Descrição do Desafio

## Cálculo de Métricas de Avaliação de Aprendizado

Neste projeto, vamos calcular as principais métricas para avaliação de modelos de classificação de dados, como acurácia, sensibilidade (recall), especificidade, precisão e F-score. Para que seja possível implementar estas funções, você deve utilizar os métodos e suas fórmulas correspondentes (Tabela 1).

Para a leitura dos valores de VP, VN, FP e FN, será necessário escolher uma matriz de confusão para a base dos cálculos. Essa matriz você pode escolher de forma arbitrária, pois nosso objetivo é entender como funciona cada métrica.

### Tabela 1: Visão geral das métricas usadas para avaliar métodos de classificação

| **Método**          | **Fórmula**                  |
|----------------------|------------------------------|
| **Sensibilidade**    | VP / (VP + FN)              |
| **Especificidade**   | VN / (FP + VN)              |
| **Acurácia**         | (VP + VN) / N               |
| **Precisão**         | VP / (VP + FP)              |
| **F-score**          | 2 × (P × S) / (P + S)       |

Legenda:
- **VP**: Verdadeiros Positivos
- **VN**: Verdadeiros Negativos
- **FP**: Falsos Positivos
- **FN**: Falsos Negativos
- **P**: Precisão
- **S**: Sensibilidade
- **N**: Total de elementos
