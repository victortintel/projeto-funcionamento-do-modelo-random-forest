# Projeto: Decision Tree e Random Forest - Implementação Prática
Descrição
Este projeto demonstra de forma prática e passo a passo o funcionamento dos algoritmos de Machine Learning Decision Tree (Árvore de Decisão) e Random Forest (Floresta Aleatória). O objetivo é mostrar como esses algoritmos realizam previsões e calculam probabilidades em modelos preditivos, utilizando um conjunto de dados de habitação da Califórnia.

O notebook implementa desde a importação e exploração dos dados até a construção, treinamento e avaliação dos modelos, passando por considerações importantes sobre overfitting e ajuste de hiperparâmetros.

## Conteúdo do Projeto
### 1. Pré-requisitos e Configuração
- Importação das bibliotecas necessárias (pandas, numpy, matplotlib, scikit-learn)

- Carregamento do dataset "housing.csv"

### 2. Análise Exploratória dos Dados
- Visualização das primeiras linhas do dataset

- Separação das variáveis preditoras e target

- Divisão dos dados em conjuntos de treino e teste

### 3. Implementação da Árvore de Decisão
- Criação e treinamento do modelo DecisionTreeRegressor

- Avaliação do modelo usando Mean Squared Error (MSE)

- Discussão sobre overfitting e importância da profundidade da árvore

- Experimentos com diferentes profundidades máximas

### 4. Implementação do Random Forest
- Criação e treinamento do modelo RandomForestRegressor

- Comparação de desempenho com a Árvore de Decisão simples

- Análise da importância das variáveis

### 5. Visualizações e Interpretação
- Plotagem da árvore de decisão

- Análise gráfica dos resultados

## Principais Aprendizados
### Como funcionam os algoritmos:

- Decision Tree divide os dados em nós baseados em regras de decisão

- Random Forest combina múltiplas árvores para melhorar a precisão

### Considerações sobre overfitting:

- Árvores muito profundas tendem a memorizar os dados de treino

- Random Forest reduz overfitting através do ensemble de árvores

### Avaliação de modelos:

- Uso do Mean Squared Error (MSE) como métrica de avaliação

- Importância da validação cruzada e conjuntos de teste
