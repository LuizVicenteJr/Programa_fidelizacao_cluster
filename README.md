# Insiders_Clustering

O objetivo deste projeto é utilizar a técnica de clusterização para trazer para a equipe de negócios os clientes mais valiosos para integrar o programa de fidelização da empresa, um e-commerce que disponibilizou sua base de vendas de período de 1 ano .

# Estratégia para solução do problema :
 Após receber a base de dados, trabalhei a solução em 10 passos:
 
 ## Passo 1 - DATA DESCRIPTION:
 **limpeza e tratamento dos dados** :verificando a quantidade de dados disponibilizados,possíveis nulos,tipo das variáveis e entendimento do que significavam as mesmas.
 
 ## Passo 2 - DATA FILTER :
 **Retirei da base os dados que não trariam relevância para o modelo** e derivei a variavél de quantidade para saber o que era compra e o que era devolução.
 
 ## Passo 3 - FEATURE ENGINEERING:
 **Derivei variáveis** importantes para o modelo , como o faturamento que o cliente trazia para o negócio,quantidade de produtos comprados/devolvidos,frequência de compra ,quantidade de produtos por compra e etc... Tudo para facilitar o modelo que será implementado.
 
 ## 4.0 Exploratory Data Analysis :
 **Dividi o estudo em análise de univariada e bivariada** ,este passo me ajudou a filtar alguns outliers que não faziam sentido para o modelo.
 
 ## 5.0 Data Preparation:
  Fiz testes com o StandardScalers,RobustScaler e MinMaxScaler e avaliei as primeiras formações de clusters.
  
  ## 6.0 FEATURE SELECTION:
  **Defini as variáveis finais do modelo** : Faturamento,intervalo entre compras, quantidade de produtos comprados,frequência de compra e quantidade de itens retornados.
  
  ## 7.0 Hyperparameter Fine-Tuning:
   **Avaliei a performance do modelo com diferentes métodos e defini que a melhor escolha,no momento, seria utilizar 8 clusters .
   
   ## 8.0 8.0 MODEL TRAINING
   Treinamento do modelo final .
   
   ## 9.0 Cluster Analysis
   Análise visual e das métricas de cada cluster formado, chegando também a **conclusão do cluster dos clientes INSIDERS**:
   Número de customers: 373 (12,56 % da base)
   
   Faturamento médio:10.503 dólares
   
   Recência média: 19 dias
   
   Média de Produtos comprados: 476 produtos
   
   Frequência de Produtos comprados: 0.11 produtos/dia
   
   Média de produtos retornados: 187 produtos
   
   ## 10.0. EDA :
   Respondi a perguntas da equipe de negócios:
   Os clientes do cluster insiders possuem um volume (produtos) de compras acima de 10% do total de compras?
   
   Os clientes do cluster insiders possuem um volume (faturamento) de compras acima de 10% do total de compras?
   
   Os clientes do cluster insiders tem um número de devolução médio abaixo da média da base total de clientes?
   
   A mediana do faturamento pelos clientes do cluster insider é 10% maior do que a mediana do faturamento geral?
   
   Qual a porcentagem de contribuição do faturamento, vinda do Insiders ?
   
   ## Conclusão : 
   **Com este trabalho, além de facilitar a criação do programa de fidelidade para os clientes que mais geram receita para a empresa,podemos utilizar os      outros cluster para gerar insights de como melhorar as vendas nestes grupos** . 
   

