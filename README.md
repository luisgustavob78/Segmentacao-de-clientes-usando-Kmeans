# Segmentação de clientes usando Kmeans

O projeto é fruto de um desafio do kaggle onde o objetivo é criar uma segmentação de clientes para identificar classes de clientes e tomar decisões a partir disso. 

## 1. Exploração e análise dos dados

O primeiro passo realizado foi analisaar os dados para entender as informações existentes na base

![](https://github.com/luisgustavob78/Segmentacao-de-clientes-usando-Kmeans/blob/master/GIF%20explora%C3%A7%C3%A3o%20de%20dados%20mall.gif)

## 2. Construção do modelo Kmeans

Após a análise dos dados, buscou-se identificar quais os atributos que influenciavam algum tipo de agrupamento nos dados.

![](https://github.com/luisgustavob78/Segmentacao-de-clientes-usando-Kmeans/blob/master/kmeans_1.png)

Com esse resultado, o modelo de agrupamento por Kmeans foi construido, resultando na seguinte distribuição de clusters:

![](https://github.com/luisgustavob78/Segmentacao-de-clientes-usando-Kmeans/blob/master/kmeans_2.png)

## Exemplos de uso

Esse tipo de análise permite a categorização de clientes para desenvolvimento especializado de produtos e criação de estratégias de marketing segmentadas para maiores taxas de assertividade e conversão

## Instalação Pandas

```bash
pip install pandas
```

## Instalação Spark

OS e Linux: https://medium.com/luckspark/installing-spark-2-3-0-on-macos-high-sierra-276a127b8b85

Windows: https://changhsinlee.com/install-pyspark-windows-jupyter/
