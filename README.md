# Projeto de Machine Learning Supervisionado - Titanic

## Objetivo

O objetivo deste projeto é utilizar técnicas de aprendizado supervisionado para prever se um passageiro do Titanic sobreviveu ou não ao naufrágio, com base em características como sexo, idade e classe da passagem.

## Fonte dos Dados

Foi utilizado o dataset Titanic disponível no Orange Data Mining.

O conjunto de dados contém informações sobre os passageiros e a variável alvo é "Survived", que indica se o passageiro sobreviveu ou não.

## Análise dos Dados

Inicialmente foi realizada uma análise exploratória do conjunto de dados.

Foram observados atributos como:

* Sexo
* Idade
* Classe do passageiro
* Número de familiares a bordo
* Sobrevivência

Foi possível identificar que mulheres apresentaram maior taxa de sobrevivência em comparação aos homens.

## Pré-processamento

Foram realizadas as seguintes etapas:

* Verificação de dados ausentes.
* Definição da variável "Survived" como classe alvo.
* Seleção dos atributos relevantes para o treinamento.

## Treinamento

Foram utilizados dois algoritmos de aprendizado supervisionado:

1. Regressão Logística
2. Árvore de Decisão

O treinamento foi realizado utilizando validação cruzada com 10 partições (10-fold cross validation).

## Resultados

Os resultados obtidos foram:

| Modelo              | Acurácia |
| ------------------- | -------- |
| Regressão Logística | 84%      |
| Árvore de Decisão   | 81%      |

A Regressão Logística apresentou o melhor desempenho.

## Conclusão

Os resultados demonstraram que técnicas de aprendizado supervisionado podem prever a sobrevivência dos passageiros com boa precisão.

A Regressão Logística foi o modelo mais eficiente entre os algoritmos avaliados, alcançando aproximadamente 84% de acurácia.

O projeto permitiu aplicar conceitos de análise de dados, pré-processamento, treinamento e validação de modelos de Machine Learning.
