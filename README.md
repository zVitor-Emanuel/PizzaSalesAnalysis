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
2. Preço Médio or pedido<br> <br>
![query_avgprice](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/9099878f-9bb7-471b-8184-3b25e33eb4be)
![result_avgprice](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/bec59bd8-8ba7-4225-990b-71a13c082504)<br> <br>
3. Quantidade de pizzas vendidas<br> <br>
![query_qntpizza](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/c7d1e06a-ff43-4bfb-a059-bf164c34ce57)
![result_qntpizza](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/d12eb8e5-b7da-4fac-b9e4-8f799f38173b)<br> <br>
4. Numero de pedidos<br> <br>
![query_numorder](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/13226d3a-95bb-45ef-84f3-0513d98925b1)
![result_numorder](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/cadc02b0-fde9-4cf6-a345-54db4b15e5e2)<br> <br>
5. Numero de pizzas por pedido<br> <br>
![query_pizzaporder](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/bae93169-d87e-4a68-b6ec-0af7bc077674)
![result_pizzaporder](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/abff65da-08a8-4498-9796-b20ecdc6fb5b)

### Insights 

1. Pedidos por dia da semana <br> <br>
![q_p_por_dia_semana](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/1e548d36-5ff0-43fc-b1b9-278e86c72861) <br> <br>
![p_por_dia_semana_r](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/248bcd24-5b35-4cc2-a566-9a0e82821931)<br> <br>
2. Horario dos Pedidos<br> <br>
![2_1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/ef348cd0-b997-427c-819f-01134b3ef3cb)<br> <br>
![2_2](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/03deb8c3-1b35-42f3-9e4c-a1b6870e2b80)<br> <br>
3. Porcentagem de Vendas por categoria de pizza durante os meses<br> <br>
![3_1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/016a6f9d-8f61-47b5-a931-983fae62d539)<br> <br>
![3_2](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/6845bbf2-d8c7-4c49-80d0-9a4f455be01d)<br> <br>
4. Porcentagem de vendas por tamanho da pizza no trimestre.<br> <br>
![4_1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/521241a9-d0d5-4b9a-8257-5040cb1834b4)<br> <br>
![4_2](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/4c26e248-ac32-4704-b9aa-1d750ccf0545)<br> <br>
5. Total de pizzas vendidas por categoria<br> <br>
![5_1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/58bdf32d-96fc-4804-9b64-3fb3af4f9f6a)<br> <br>
![5_2](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/16d875a7-7313-4afc-81f3-9e6e3a406fee)<br> <br>
6. As 5 pizzas  mais vendidas<br> <br>
![6_1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/eb12f212-d344-466f-9402-3f22ba50aa04)<br> <br>
![6_2](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/5ebf7ed2-16fe-4097-8202-c227421006b9)<br> <br>
7. Pizzas menos vendidas<br> <br>
![7_1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/61242d5e-d96a-4acc-a324-944451e733cf)<br> <br>
![7_2](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/59830b36-3146-4996-aaa6-226282c06393)<br> <br>

## Conexão entre MySQL e Excel atravéz do ODBC

### Processamento de dados no Excel:
1. Adicionei uma coluna na tabela no excel para facilitar a exibição dos dias dos pedidos de acordo com as datas <br> <br>
=TEXTO([@[data_pedido]];"dddd") <br> <br>
![excel1](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/8631458c-952e-4645-ad0f-c3fda5a0cccf)<br> <br>
2. No excel não tem a funcao distinct, por isso criarei uma nova coluna na tabela para fazer isso <br> <br>
=1/CONT.SE(B:B;[@[id_pedido]])<br> <br>
Cada linha da tabela é referente há um tipo de pizza, sendo assim, quando tiver mais de uma pizza por pedido, terá 2 linhas de codigo para o mesmo pedido.<br> <br>
A formula faz a contagem de acordo com o numero de vezes que o numero aparece na coluna id_pedido e dividinho 1 pela formula, recebemos os valores para ocasionar 1 unico pedido.<br> <br>
![image](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/7bcf398b-d528-4c0e-b8d4-328f4a42d032)
![image](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/5e567675-7b9a-409f-b7f2-ada428db05ba)
3. Utilizei uma tabela dinâmica no excel para fazer o KPI <br> <br>
![image](https://github.com/zVitor-Emanuel/PizzaSalesAnalysis/assets/148022061/e6ef2826-666d-4171-b660-094d4f3a0e55)<br> <br>

## Dashboard














