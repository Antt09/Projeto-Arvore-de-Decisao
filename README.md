# Módulo 21 - Projeto de Credit Score: Árvore de Decisão

Este repositório contém o desenvolvimento do projeto prático referente ao **Módulo 21** da formação de **Cientista de Dados da EBAC** (Escola Britânica de Artes Criativas e Tecnologia).

## 📋 Sobre o Projeto

O objetivo deste projeto é aplicar o algoritmo de aprendizado supervisionado **Árvore de Decisão** (`DecisionTreeClassifier`) em um problema de classificação de *Credit Score* (Pontuação de Crédito). 

Nas etapas anteriores da formação (Módulos 17 e 14), foram realizadas as fases fundamentais de engenharia de dados, tais como:
* Tratamento e limpeza dos dados;
* Balanceamento das classes (para lidar com desbalanceamento no target);
* Transformação de variáveis categóricas;
* Separação das bases de treino e teste;
* Aplicação inicial do algoritmo Naive Bayes.

Neste módulo, o foco é a modelagem preditiva utilizando Árvores de Decisão, avaliando o desempenho do modelo, identificando possíveis indícios de *overfitting* e interpretando a importância das variáveis (*feature importances*).

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido em **Python**, utilizando o ambiente Jupyter Notebook e as seguintes bibliotecas:
* `pandas` e `numpy` (Manipulação e estruturação de dados)
* `scikit-learn` (Modelagem preditiva, métricas e árvore de decisão)
* `matplotlib` e `seaborn` (Visualização de dados e plotagem de matriz de confusão e da árvore)

## 📊 Principais Etapas do Notebook

1. **Carregamento e Validação dos Dados:** Importação das bases de treino (balanceadas) e teste, conferindo dimensões e integridade.
2. **Fundamentos Teóricos:** Discussão estruturada sobre o passo a passo da aplicação do algoritmo, critérios de parada/divisão e métricas de avaliação.
3. **Treinamento do Modelo:** Ajuste do classificador utilizando o critério de **Gini** e `random_state=0`.
4. **Avaliação de Desempenho:** 
   * Análise comparativa da acurácia entre as bases de treino e teste.
   * Geração do relatório de classificação (*Precision*, *Recall* e *F1-Score* para as classes 1, 2 e 3).
   * Construção e interpretação da **Matriz de Confusão**.
5. **Visualização Gráfica:** Plotagem da árvore de decisão gerada pelo modelo e análise de sua profundidade.

## 🚀 Como Executar o Projeto

1. Clone o repositório em sua máquina:
   ```bash
   git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
