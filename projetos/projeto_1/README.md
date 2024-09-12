## Projeto de Análise de Influenciador no Instagram e Dashboard no Looker Studio

### Descrição
Este projeto fictício, que consiste em coletar dados de perfis de influenciadores no Instagram utilizando a API RapidAPI e criar um dashboard interativo no Looker Studio para visualizar e analisar as métricas de desempenho desse perfil. O projeto foi desenvolvido para o time de Marketing da SUNO RESEARCH, com o objetivo de monitorar campanhas realizadas em seu influenciador na área de finanças.

### Etapas do Projeto
1. **Coleta de Dados com API do Instagram:**
   - Utilizando a API [Instagram Scraper](https://instagram-scraper-api3.p.rapidapi.com/), os dados dos perfis patrocinados são coletados.
   - As informações extraídas incluem o número de seguidores, engajamento nas postagens, tipos de conteúdo (fotos, vídeos, carrosséis) e outros detalhes relevantes para a análise de desempenho dos influenciadores.
   - A autenticação na API é realizada com a variável `x-rapidapi-key` através de uma secret key configurada no Google Colab.

2. **Armazenamento de Dados e Processamento:**
   - Os dados extraídos da API são processados usando a biblioteca **PySpark** para manipulação de grandes volumes de dados.
   - As métricas essenciais como engajamento, crescimento de seguidores, e o tipo de conteúdo que mais agrada são calculadas e armazenadas em DataFrames do Pandas.
   - A análise dos dados inclui:
     - **Engajamento**: Taxa de interações (curtidas, comentários) por seguidor.
     - **Crescimento de Seguidores**: Análise da variação de seguidores ao longo do tempo.
     - **Análise de Conteúdo**: Frequência e popularidade de diferentes tipos de postagens.

3. **Exportação dos Dados para o Google Sheets:**
   - As métricas essenciais são exportadas para uma planilha do Google Sheets, facilitando a integração com o Looker Studio.
   <!-- - O script utiliza a API do Google Sheets para escrever os dados processados diretamente na planilha, criando uma base de dados acessível para visualizações e relatórios. -->

4. **Dashboard no Looker Studio:**
   - Os dados processados no Google Sheets são conectados ao Looker Studio, permitindo a criação de um dashboard interativo.
   - O dashboard permite a exploração das métricas de engajamento, crescimento de seguidores, e tipos de conteúdo. Filtros e gráficos interativos foram adicionados para facilitar a análise.
   - Com o dashboard, a equipe de marketing da SUNO RESEARCH pode visualizar as métricas de desempenho de maneira clara e rápida, auxiliando na tomada de decisões para futuras campanhas.

### Como Usar
1. **Obtenha os Dados via API:**
   - Certifique-se de ter as bibliotecas `requests`, `pyspark` e `pandas` instaladas (`pip install requests pyspark pandas`).
   - Configure as credenciais da API do Instagram usando sua `x-rapidapi-key`.
   - Execute o script que coleta os dados dos perfis patrocinados e processa as métricas essenciais.

2. **Conecte ao Google Sheets:**
   - Exporte os dados processados para uma planilha do Google Sheets usando a API do Google. Certifique-se de ter as credenciais de acesso à API configuradas.

3. **Crie o Dashboard no Looker Studio:**
   - No Looker Studio, crie uma nova fonte de dados e conecte-a à planilha do Google Sheets com as métricas dos influenciadores.
   - Construa o dashboard utilizando gráficos, tabelas e filtros para explorar as métricas coletadas.

### Link para o Dashboard
[Dashboard](https://lookerstudio.google.com/reporting/baf3b3fa-4f98-4f68-a3c5-a127cbcdb043)

### Link para a Apresentação em PowerPoint
[Apresentação](https://docs.google.com/presentation/d/1jHBHwFxXfGOJIr0TqNzPxWwMVKORj3jlO3MyTRyzATc/edit?usp=sharing)

#### Capa do Dashboard:
<p align="center">
<img alt="capa_dashboard" src="https://github.com/LLR798/formacao_engenheira_de_dados_growdev/blob/main/projetos/projeto_1/preview/preview_capa.png?raw=true" width="100%">
</p>


### Considerações Finais
- Este projeto demonstra como combinar dados de influenciadores do Instagram com ferramentas de visualização para monitorar e otimizar campanhas de marketing. Ele oferece uma solução prática e escalável para o time de Marketing da SUNO RESEARCH, permitindo a análise detalhada de métricas essenciais de performance dos influenciadores, o que resulta em uma tomada de decisão mais informada e eficiente.

