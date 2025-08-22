# 📊 Análise de Comorbidades em Doenças Crônicas

Este projeto realiza uma análise aprofundada sobre a ocorrência e a relação entre diferentes doenças crônicas, utilizando uma base de dados processada. As análises são segmentadas por **Gênero**, **Faixa Etária** e **Raça/Cor** para identificar padrões e correlações específicas em cada grupo.

## 📜 Descrição do Projeto

O objetivo principal deste trabalho é explorar as associações entre diversas condições crônicas e fatores de risco, como hipertensão, diabetes, colesterol alto, depressão, e hábitos como tabagismo e consumo de álcool. Através de técnicas de mineração de dados, o projeto busca gerar insights sobre quais doenças tendem a ocorrer em conjunto, fornecendo informações valiosas para a área da saúde.

## ✨ Análises Realizadas

**Regras de Associação por Gênero**:
    -   Utilização do algoritmo **Apriori** para identificar as regras de associação mais fortes entre doenças para os sexos masculino e feminino.
    -   Análise de métricas como **suporte**, **confiança** e **lift** para validar a relevância das regras.
    -   Visualização das associações através de grafos para uma interpretação mais intuitiva.

-   **Análise de Correlação**:
    -   Criação de mapas de calor (heatmaps) para visualizar a correlação entre todas as variáveis de doenças.
    -   Geração de gráficos de barras para destacar os pares de doenças com maior correlação positiva.

-   **Prevalência de Doenças**:
    -   Cálculo e visualização da prevalência (ocorrência) de cada doença, com comparações diretas entre gêneros.

## 💾 Base de Dados

O estudo foi realizado com base no arquivo `DataBaseProcessedBinary.xlsx`, que contém dados binários indicando a presença ou ausência de cada condição ou hábito para os indivíduos analisados.

## 🛠️ Tecnologias Utilizadas

-   **Linguagem**: Python 3
-   **Bibliotecas Principais**:
    -   `pandas`: para manipulação e análise dos dados.
    -   `matplotlib` e `seaborn`: para a criação de gráficos e visualizações.
    -   `mlxtend`: para a aplicação do algoritmo Apriori e geração de regras de associação.
    -   `scikit-learn`: para a implementação de algoritmos de cluster.
    -   `networkx`: para a criação e visualização de grafos de associação.
-   **Ambiente**: O notebook foi desenvolvido utilizando o Google Colab.
