# Predição da Resistência à Compressão do Concreto

Este repositório contém código e recursos para prever a resistência à compressão do concreto utilizando técnicas de aprendizado de máquina. O projeto utiliza diversos modelos de regressão para analisar a relação entre os ingredientes do concreto e sua resistência resultante.

## Visão Geral

O concreto é um dos materiais de construção mais utilizados, e sua resistência à compressão é um indicador fundamental de qualidade. Por meio do aprendizado de máquina, é possível construir modelos preditivos que estimam a resistência do concreto com base em sua composição e tempo de cura.

## Funcionalidades

- Pré-processamento de dados e análise exploratória (EDA)
- Implementação de múltiplos modelos de regressão (por exemplo, Regressão Linear, Árvore de Decisão, Floresta Aleatória, etc.)
- Avaliação dos modelos usando métricas como RMSE, MAE e R²
- Visualização de resultados e importância das variáveis

## Conjunto de Dados

O conjunto de dados utilizado neste projeto contém registros de amostras de concreto com as seguintes variáveis:
- Cimento (kg em uma mistura de m³)
- Escória de Alto-Forno
- Cinzas Volantes
- Água
- Superplastificante
- Agregado Graúdo
- Agregado Miúdo
- Idade (dias)
- Resistência à compressão do concreto (MPa) — variável alvo

## Como Começar

### Pré-requisitos

- Python 3.7+
- Jupyter Notebook (opcional)
- Bibliotecas Python necessárias (veja abaixo)

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/veiberlim/ml_Concrete_Compressive_Strength.git
   cd ml_Concrete_Compressive_Strength
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

### Uso

- Execute o notebook principal ou o script para realizar a análise de dados e o treinamento dos modelos.
- Modifique os parâmetros para experimentar diferentes modelos ou técnicas de pré-processamento.

## Estrutura do Projeto

```
ml_Concrete_Compressive_Strength/
├── data/                 # Arquivos do conjunto de dados
├── notebooks/            # Notebooks Jupyter para EDA e modelagem
├── src/                  # Código fonte (scripts, módulos)
├── requirements.txt      # Dependências Python
├── README.md             # Documentação do projeto
```

## Resultados

O repositório inclui resultados da avaliação dos modelos e visualizações para comparar o desempenho de diferentes abordagens. A análise de importância das variáveis ajuda a entender o impacto de cada ingrediente na resistência à compressão.

## Contribuindo

Contribuições são bem-vindas! Por favor, abra issues ou envie pull requests para melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a Licença MIT.

## Referências

- [UCI Machine Learning Repository: Concrete Compressive Strength Data Set](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength)
