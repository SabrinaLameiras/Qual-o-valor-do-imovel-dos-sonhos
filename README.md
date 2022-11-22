# Qual o valor do imovel dos meus sonhos?
Neste modelo de trabalhei com dados de compra e venda de imóveis dos últimos 10 anos.

Optei por um modelo de regressão e trabalhei com Spark. Comecei conhecendo os dados, fiz a seleção de features e alguns tratamentos dos dados para trabalhar com eles sem grandes problemas.  

Depois, fiz a exploração dos dados para verificar se existia alguma relação ou correlação problemática e comecei a trabalhar com os modelos de regressão. O primeiro modelo com o qual trabalhei foi o de Regressão Linear. Então, passei para um modelo um tanto mais complexo, Árvore de Decisão. Ainda trabalhei com outro modelo que é ensemble (combinação de várias técnicas de machine learning ou uma mesma técnica repetida vezes) -- Random Forest. As métricas escolhidas para validação foram R2 e RMSE. 

Utilizei técnicas de otimização, mais especificamente, a Cross Validation. Com isso, consegui verificar quais os melhores parâmetros para trabalhar com o meu modelo. 

Ao final, obtive vários modelos, alguns melhores que outros e os comparei por meio de uma tabela para dizer qual o melhor deles. 

A partir do melhor modelo – **Randon Forest com Cross Validation**, utilizando dados reais, consegui prever quanto (R$) seria necessário para comprar uma casa, baseado em determinadas características do imóvel desejado. 

Para adquirir o imóvel dos meus sonhos, seria necessário R$ 1.500.000,00. 
