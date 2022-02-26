
## Projeto de classificação de clientes para seguro de saúde

<figure>
  <img src="./imagens/insurance.jpg " alt="Figura 1" />
</figure>

Nosso cliente é uma Seguradora que forneceu Seguro Saúde para seus clientes agora eles precisam de sua ajuda na construção de um modelo para prever se os segurados (clientes) do ano passado também terão interesse no Seguro de Veículos fornecido pela empresa.

Uma apólice de seguro é um acordo pelo qual uma empresa se compromete a fornecer uma garantia de compensação por perda, dano, doença ou morte especificados em troca do pagamento de um prêmio especificado. Um prêmio é uma quantia em dinheiro que o cliente precisa pagar regularmente a uma companhia de seguros por essa garantia.

Por exemplo, você pode pagar um prêmio de Rs. 5000 por ano para uma cobertura de seguro de saúde de $R\$ 200.000,00$ de modo que se, Deus me livre, você adoecer e precisar ser hospitalizado naquele ano, a seguradora arcará com o custo da hospitalização etc. por até $R\$ 200.000,00$. Agora, se você está se perguntando como a empresa pode arcar com um custo de hospitalização tão alto quando cobra um prêmio de apenas $R\$. 5000,00$, é aí que entra o conceito de probabilidades. Por exemplo, como você, pode haver 100 clientes que pagariam um prêmio de $R\$. 5.000,00$ por ano, mas apenas alguns deles (digamos 2-3) seriam hospitalizados naquele ano e nem todos. Desta forma, todos compartilham o risco de todos os outros.

Assim como o seguro médico, existe o seguro de veículo onde todos os anos o cliente precisa pagar um prêmio de certo valor à seguradora para que, em caso de acidente infeliz com o veículo, a seguradora forneça uma indenização (chamada de "soma assegurado") para o consumidor.

Construir um modelo para prever se um cliente estaria interessado em Seguro de Veículo é extremamente útil para a empresa, pois ela pode planejar adequadamente sua estratégia de comunicação para alcançar esses clientes e otimizar seu modelo de negócios e receita.

Agora, para prever se o cliente estaria interessado em seguro de veículo, você tem informações sobre dados demográficos (gênero, idade, tipo de código de região), veículos (idade do veículo, danos), política (premium, canal de fornecimento) etc.

O dataset pode ser encontrado em: https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction

## Planejamento da solução
1. Carregar o conjunto de dados;
2. Descrever os dados;
3. Criar hipóteses;
4. Criar variáveis baseadas nas hipóteses;
5. Análise exploratória dos dados;
6. Prepara os dados para criar o modelo preditivo;
7. Selecionar os melhores recursos para o modelo preditivo;
8. Criar os modelos preditivos;
9. Avaliar as métricas para o  modelo;
10. Encontrar os melhores parâmetros para o modelo selecionado;
11. Criar o modelo final.

Para visualizar o projeto completo em detalhes só acessar o arquivo `health_insurance_prediction.ipynb` ou acessar o link abaixo:

* https://fhfraga.github.io/projetos/health_insurance_prediction.html