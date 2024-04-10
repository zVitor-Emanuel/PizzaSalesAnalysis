# PizzaSalesAnalysis

## 📘 Introdução

Qual sabor de pizza você pede com frequencia? Normalmente todos temos um sabor favorito, que sempre pedimos quando vamos fazer um pedido. Neste projeto, vou fazer uma analise utilizando MYSQL e EXCEL para Data VIZ, para mostrar o quanto nossos pedidos impactam diretamente nas vendas de uma pizzaria.

## 📁 Conjunto de dados
O dataset utlizado neste projeto foi retirado do kaggle: https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset/data<BR>
<BR>
Contem 48621 linhas com 21350 pedidos de diferentes tipos de pizza retirados do ano de 2015, os dados permitem visualização das datas e horario dos pedidos, preco, categoria e ingredientes.

## Preparação dos dados

Comecei criando um banco de dados para fazer nosso projeto. <br> <br>
![create_database](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/668f06c3-248d-49bc-9a82-a92c308265c2) <br> <br>
Em seguida a criação da tabela para receber os dados. <br> <br>
![create_table](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/66649948-c0ba-4801-bc13-fe139a4c5dfa) <br> <br>
Importação dos dados. <br> <br>
![data_import](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/dc511a16-d537-426b-bbef-659d2525756d)


## Limpeza dos dados
Como o DATASET esta em inglês, eu preferi fazer a limpeza dos dados e traduzir os dados das tabelas de dados importantes, que seriam utilizados no dashboard.

TAMANHO:<br> <br>
![clean_size](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/931f1fa4-8161-41bf-a957-917c8d61ae20) <br> <br>
CATEGORIA: <br> <br>
![clean_category](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/5020bb52-ce3d-4836-acba-f360f8defe96)

## Analise de dados
# KPI - INDICADORES CHAVES DE DESEMPENHO
1. Receita total<br> <br>
![query_totalrevenue](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/3ae6ae7c-414e-467c-bde3-956ff74eac56)
![result_queryrevenue](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/66836df3-a0fe-4647-99bf-4ef4cb6e750e)

