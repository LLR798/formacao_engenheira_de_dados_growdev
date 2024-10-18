## Projeto para o Acompanhamento de Ações na Bolsa de Valores

### Descrição:
Uma empresa que gerencia investimentos na bolsa de valores B3 precisa desenvolver uma solução para monitorar desempenho de ações ao longo de um período específico, por exemplo (semanal, mensal, trimestral). O objetivo é criar um sistema que permita a análise de dados históricos, comparando a performance de diferentes ativos, além de gerar relatórios e alertas para idetificar oportunidades de compra e venda. O projeto deve incluir:

- Coleta de Dados: Captura de dados de ações listadas na B3 (valores de abertura, fechamento, volume, etc) através de APIs ou fonte de dados públicas.

- Armazenamento: Organização dos dados históricos em uma base eficiente, possibilitando consultas rápidas.

- Análise: Desenvolvimento de modelos analíticos para identificar tendências e padrões, bem como cálculo de indicadores financeiros como P/L, D.Y, e volatilidade.

- Visualização: Criação de dashboard e relatórios para monitorar os resultados e gerar insights sobre performance das ações.

- Alertas: Definição de critérios de alerta para notificar a equipe sobre variações anormais ou oportunidades de mercado.


### Notebooks:
- [Monitoramento](https://github.com/LLR798/formacao_engenheira_de_dados_growdev/blob/main/projetos/projeto_2/analise_de_acoes.ipynb)
- [Integração Telegram](https://github.com/LLR798/formacao_engenheira_de_dados_growdev/blob/main/projetos/projeto_2/integracao_com_telegram.ipynb)

### Dashboard:
- [Dashboard](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3981966564692036/4417656920116746/4681527955680524/latest.html)

### Apresentação em PowerPoint:
- [Apresentação](https://docs.google.com/presentation/d/1CnxmEzCFdzFpkRhv6vMWNP_nwnbOl4dcmiojPyx-c1U/edit?usp=sharing)


### Documentações:
- [Biblioteca yfinance](https://pypi.org/project/yfinance/)
- [Api Bot do Telegram](https://core.telegram.org/bots/api)


### Considerações Finais:
- Este projeto demonstra como utilizar o databricks para realizar a coleta de dados por meio de uma biblioteca pública, nesse caso a [yfinance](https://pypi.org/project/yfinance/), e com base nesses dados, realizar consultas rápidas e eficientes, além de um dashboard para apoiar o negócio. Além de um bot no telegram, para enviar alertas de acordo com a variação monetária e percentual da ação escolhida.