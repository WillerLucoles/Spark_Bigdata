# Trabalho de Big Data

## Descrição
Este repositório contém o trabalho prático de Big Data utilizando PySpark para processar um conjunto de dados de resenhas de filmes. O objetivo deste trabalho é realizar análises sobre as resenhas, especialmente focando nas classificações negativas.

## Conjunto de Dados
O conjunto de dados utilizado é o *imdb-reviews-pt-br.csv*, que contém resenhas de filmes em português e inglês, classificadas como positivas ou negativas. O arquivo foi obtido a partir de uma [fonte do Kaggle](https://www.kaggle.com/luisfredgs/imdb-ptbr/download).

## Funcionalidades
1. Cálculo da soma dos IDs de resenhas negativas.
2. Contagem de palavras nos textos negativos em português e inglês, e cálculo da diferença entre eles.

## Pré-requisitos
- Python 3.x
- Google Colab ou ambiente local com PySpark instalado.

## Como Executar
1. Faça o download do arquivo `imdb-reviews-pt-br.csv` e coloque na mesma pasta do script.
2. Instale o PySpark no Google Colab usando:
   ```bash
   !pip install pyspark
