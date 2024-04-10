# PizzaSalesAnalysis

## 📘 Introdução

Qual sabor de pizza você pede com frequencia? Normalmente todos temos um sabor favorito, que sempre pedimos quando vamos fazer um pedido. Neste projeto, vou fazer uma analise utilizando MYSQL e EXCEL para Data VIZ, para mostrar o quanto nossos pedidos impactam diretamente nas vendas de uma pizzaria.

## 📁 Conjunto de dados
O dataset utlizado neste projeto foi retirado do kaggle: https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset/data<BR>
<BR>
Contem 48621 linhas com 21350 pedidos de diferentes tipos de pizza retirados do ano de 2015, os dados permitem visualização das datas e horario dos pedidos, preco, categoria e ingredientes.

# Preparação dos dados

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
### KPI - INDICADORES CHAVES DE DESEMPENHO
1. Receita total<br> <br>
![query_totalrevenue](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/3ae6ae7c-414e-467c-bde3-956ff74eac56)
![result_queryrevenue](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/66836df3-a0fe-4647-99bf-4ef4cb6e750e)<br> <br>
2. Preço Médio or pedidol<br> <br>
![query_avgprice](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/9099878f-9bb7-471b-8184-3b25e33eb4be)
![result_avgprice](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/bec59bd8-8ba7-4225-990b-71a13c082504)<br> <br>
3. Quantidade de pizzas vendidas<br> <br>
![query_qntpizza](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/c7d1e06a-ff43-4bfb-a059-bf164c34ce57)
![result_qntpizza](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/d12eb8e5-b7da-4fac-b9e4-8f799f38173b)<br> <br>
4. Numero de pedidos<br> <br>
![query_numorder](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/13226d3a-95bb-45ef-84f3-0513d98925b1)
![result_numorder](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/cadc02b0-fde9-4cf6-a345-54db4b15e5e2)<br> <br>






