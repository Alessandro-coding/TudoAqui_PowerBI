# TudoAqui_PowerBI
Projeto voltado para a criação de Dashboards da empresa fictícia Tudo Aqui, através do Power BI e utilizando dados públicos disponibilizados pela Airbnb. Todos os dados utilizados nesse projeto são de domínio público e não infringem nenhuma regra da Lei Geral de Proteção dos Dados.

## 1. O Problema de Negócio
A partir do trabalho que você tem realizado, o CEO e o Corpo Diretivo da Tudo Aqui estão com planos de expandir a empresa de modo a abranger o ramo de locação de quartos. Neste cenário, você deverá desenvolver uma análise criteriosa em um novo relatório do Power BI com os dados de New York do ano de 2019 disponibilizado pelo Airbnb. O CEO deseja um relatório com apenas 2 dashboards, sendo 1 com as análises gráficas e 1 com os detalhes (tabela ou matriz). Os dados que devem ser analisados estão disponibilizados no seguinte link: [Link do Repositório no Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

Após conversar com o CEO, vocês concluíram que as colunas consideradas na análise e seus respectivos tipos de dados deverão ser: 

* last_review - Data;
* id - Número Inteiro;
* name - Texto;
* host_id - Número Inteiro;
* host_name - Texto;
* neighbourhood_group - Texto;
* neighbourhood - Texto;
* latitude - Número Decimal Localidade Estados Unidos);
* longitute - Número Decimal Localidade Estados Unidos);
* room_type - Texto;
* price - Número Decimal;
* minimum_nights - Número Inteiro;
* number_of_reviews - Número Inteiro.

Também foi solicitado pelo CEO que você considere apenas as linhas que possuam todos os dados preenchidos em cada uma das colunas escolhidas como também colocar cada palavra em maiúsculo nos campos do tipo texto. O CEO também deseja um menu interativo para acessar as análises com uma imagem que remeta a viagem de plano de fundo. Considere o tema “Bloomˮ do Power BI como identidade visual da empresa.

**Considere:** 
1) Regra da coluna Price:  
Considere como preço por noite.

2) O CEO deseja fazer uma classificação própria para os tipos de 
acomodação:  
Se o Preço Mínimo Final é menor ou igual a 1.000 é "Baixo Padrão",  
Se o Preço Mínimo Final é maior que 1.000 e menor ou igual a 10.000, então é "Médio Padrão",  
Se o Preço Mínimo Final é maior que 10.000 e menor ou igual a 100.000 então é "Alto Padrão",  
Se o Preço Mínimo Final é maior que 100.000 é "Altíssimo Padrão".  
A regra do Preço Mínimo Final é: Preço por noite multiplicado pela quantidade mínima de noites.
