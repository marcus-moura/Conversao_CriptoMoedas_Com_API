# Consumindo API para conversão de CriptoMoedas


- Conversão de Real para CriptoMoedas utilizando api da alphavantage.

- Moedas Convertidas:
  - BTC
  - ETH
  - BNB

- Link da Documentação da alphavantage:
  - https://www.alphavantage.co/documentation/
- URI base para bolsa de valores e critomoedas:
  - https://www.alphavantage.co/query?

- Após a interrogação nós colocaremos os campos para nossa consulta. Por exemplo, para fazer uma consulta sem autenticação para valores da IBM, de 5 em 5 minutos, o endereço completo fica:

  https://www.alphavantage.co/query?function=TIME_SERIES_INTRADAY&symbol=IBM&interval=5min&apikey=demo

