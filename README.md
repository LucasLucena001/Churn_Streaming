# Predição de Evasão de Clientes em Serviços de Streaming

## Visão Geral

Este repositório contém um notebook Jupyter projetado para analisar e prever a evasão de clientes em um serviço de streaming. Utilizando Python e diversas bibliotecas de análise de dados e aprendizado de máquina, este projeto abrange desde a limpeza dos dados até o treinamento e a avaliação de modelos preditivos.

## Características

- Limpeza e pré-processamento de dados
- Análise exploratória de dados (EDA)
- Engenharia de recursos
- Treinamento e validação de modelos
- Ajuste de hiperparâmetros com pesquisa em grade
- Métricas de desempenho (Acurácia, Acurácia Balanceada, ROC-AUC)

## Dados

O conjunto de dados utilizado (`streaming_data.csv`) inclui as seguintes colunas:
- ID do Usuário
- Gênero
- Tipo de Assinatura
- Idade
- Tempo gasto na plataforma
- Número de serviços de streaming
- Número de perfis ativos
- Avaliação média dada
- Número de dispositivos conectados
- Evasão (variável alvo)

## Modelos

Foram treinados diversos modelos para prever a evasão de clientes:
- Regressão Logística
- Classificador de Florestas Aleatórias

Os melhores parâmetros do modelo foram otimizados usando pesquisa em grade.

## Configuração e Instalação

### Pré-requisitos
- Python 3.8 ou superior
- Jupyter Notebook ou JupyterLab

### Bibliotecas
Para instalar as bibliotecas necessárias, execute o seguinte comando:
```bash
pip install pandas scikit-learn matplotlib seaborn
