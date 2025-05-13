# 📊 Regras de Associação com Apriori

Este projeto demonstra a aplicação do algoritmo **Apriori** para mineração de regras de associação, utilizando o conjunto de dados de compras de um supermercado. O notebook inclui a etapa de pré-processamento dos dados. As análise das regras foram realizadas no `Weka`.

## 🔍 Objetivo

Extrair padrões e regras de associação relevantes entre itens comprados juntos, com o objetivo de auxiliar na tomada de decisões, como estratégias de marketing, promoções e disposição de produtos em lojas.

## 🧠 Algoritmo Utilizado

- **Apriori**: Algoritmo de aprendizado não supervisionado utilizado para descobrir relações frequentes entre itens em grandes bases de dados transacionais.

## 📂 Estrutura do Projeto

- `notebook.ipynb`: Notebook principal contendo:
  - Leitura e preparação dos dados
  - Transformação dos dados no formato apropriado
  - Aplicação do algoritmo realizada no **Weka**, com exportação dos dados para o formato `.csv`.
  - Análise e visualização dos resultados

## 🛠️ Bibliotecas Utilizadas

- `pandas`
- `numpy`
- `scipy`

## 💡 Principais Métricas Avaliadas

- **Suporte**
- **Confiança**
- **Lift**
- **Leverage**

Essas métricas foram utilizadas para selecionar as regras mais relevantes.

## 👨‍💻 Autores

- Flávio Tomás Peña Villa
- Ítalo Fraga Botelho
- Tiago Noda Von Zuben
