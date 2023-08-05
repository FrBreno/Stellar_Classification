# Stellar Classification

&nbsp;

<div align="center">
    <img alt="Via Láctea acima do Observatório La Palma" src="https://apod.nasa.gov/apod/image/2307/MwLaPalma_Rosadzinski_960_annotated.jpg"/>
</div>

Crédito da imagem e direitos autorais: [Marcin Rosadziński](https://www.instagram.com/krakow_astrophotography/)  
Veja também em [nasa.gov](https://apod.nasa.gov/apod/ap230718.html)

&nbsp;

## Colaboradores

- [Francisco Breno](https://github.com/FrBreno)
- [David Alves](https://github.com/dev-david-alves)

## Objetivo do trabalho

O objetivo deste trabalho é comparar os resultados das métricas de avaliação de diferentes modelos de aprendizagem, utilizando técnicas para o tratamento de dados e a melhoria no processo de treinamento.

## Descrição do problema

Na astronomia, o esquema de classificação de galáxias, quasares e estrelas é um dos mais fundamentais. O dataset [Stellar Classification Dataset - SDSS17](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17) contém dados espectrais de diferentes corpos estelares visando classificar estrelas, galáxias e quasares com base nessas características.

### Conjunto de Dados

Esse dataset consiste em 100.000 observações (linhas) do espaço feitas pelo SDSS (Sloan Digital Sky Survey), onde cada observação é descrita por 17 colunas (colunas) de recursos e 1 coluna (label) de classe que a identifica as observações como uma estrela, galáxia ou quasar.

É importante observar que o nosso problema envolve aprendizado supervisionado, mais especificamente, um problema de classificação. Com isso, o resultado que buscamos alcançar é a classificação em uma das três categorias (estrela, galáxia ou quasar) com base nos dados analisados.