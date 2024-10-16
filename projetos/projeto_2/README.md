## Desafio: Acompanhamento de Ações na Bolsa de Valores

Uma empresa que gerencia investimentos na bolsa de valores B3 precisa desenvolver uma solução para monitorar desempenho de ações ao longo de um período específico, por exemplo (semanal, mensal, trimestral). O objetivo é criar um sistema que permita a análise de dados históricos, comparando a performance de diferentes ativos, além de gerar relatórios e alertas para idetificar oportunidades de compra e venda. O projeto deve incluir:

- Coleta de Dados: Captura de dados de ações listadas na B3 (valores de abertura, fechamento, volume, etc) através de APIs ou fonte de dados públicas.

- Armazenamento: Organização dos dados históricos em uma base eficiente, possibilitando consultas rápidas.

- Análise: Desenvolvimento de modelos analíticos para identificar tendências e padrões, bem como cálculo de indicadores financeiros como P/L, D.Y, e volatilidade.

- Visualização: Criação de dashboard e relatórios para monitorar os resultados e gerar insights sobre performance das ações.

- Alertas: Definição de critérios de alerta para notificar a equipe sobre variações anormais ou oportunidades de mercado.


### Link para o Notebook:
[Notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3981966564692036/4417656920116746/4681527955680524/latest.html)

### Link para o Dashboard
[Dashboard](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3981966564692036/4417656920116746/4681527955680524/latest.html)



### Considerações Finais
- Este projeto demonstra como utilizar o databricks para realizar a coleta de dados por meio de uma biblioteca pública, nesse caso a [yfinance](https://pypi.org/project/yfinance/), e com base nesses dados, realizar consultas rápidas e eficientes, além de um dashboard para apoiar o negócio.