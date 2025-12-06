# ✈️ Análise de Atrasos em Voos de NYC (2013)

## 📋 Sobre o Projeto

Este projeto consiste em uma análise exploratória de dados (EDA) utilizando o dataset `nycflights`. O objetivo principal é investigar os fatores que influenciam a pontualidade dos voos que partem de Nova York (JFK, LGA, EWR), com foco específico no impacto das **rotas**, **aeronaves** e **sazonalidade**.

A análise busca responder perguntas como:
* O atraso na decolagem do voo tem correlação com o atraso na chegada?
* Quais companhias aéreas mais atrasam nos vôos?
* Existem aeronaves (`tailnum`) ou rotas específicas que são sistemicamente problemáticas?
* Qual o comportamento dos atrasos ao longo do dia?
* Qual o comportamento dos atrasos ao longo dos meses do ano?

## 🗂️ Fonte de Dados

Os dados foram obtidos a partir do repositório público:
- **URL:** [nycflights.csv](https://raw.githubusercontent.com/JackyP/testing/master/datasets/nycflights.csv)
- **Conteúdo:** Dados de mais de 300.000 voos partindo de NYC em 2013.

## 🛠️ Tecnologias Utilizadas

*   **Python** (Linguagem Principal)
*   **Pandas** (Limpeza, manipulação e agregação de dados)
*   **Seaborn & Matplotlib** (Visualização dos dados)
*   **Jupyter Notebook** (Ambiente de desenvolvimento)

## 🚀 Como Executar

1.  Instale as dependências necessárias:
    ```
    pip install pandas seaborn matplotlib
    ```
2.  Execute o notebook da análise:
    ```
    jupyter notebook analise_voos_nyc.ipynb
    ```

## 📈 Principais Insights

*   **Horário:** Os dados mostram uma progressão linear de atrasos ao longo do dia. A partir da manhã, a média de atraso sobe consistentemente a cada hora, atingindo seus picos à noite.
*   **Sazonalidade:** Observou-se que os meses de Junho, Julho e Dezembro apresentam as maiores médias de atraso na partida.
*   **Rotas:** Rotas não alteram significativamente a probabilidade de um pequeno atraso corriqueiro, mas certas rotas específicas aumentam drasticamente a volatilidade e o risco de atrasos severos.
*   **Infraestrutura:** Observou-se que uma aeronave específica não exerce influência significativa nos atrasos. Os grandes atrasos observados na média são eventos pontuais, não estruturais da aeronave.