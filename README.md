Pipeline de ETL: Mensagens de Marketing Personalizadas 🚀
Este projeto foi desenvolvido como parte do desafio do Santander Dev Week, focado em demonstrar o fluxo de ETL (Extração, Transformação e Carregamento) utilizando a linguagem Python e a biblioteca Pandas.

📋 Objetivo
O sistema automatiza a leitura de dados de clientes, processa uma lógica de personalização e gera um novo arquivo com mensagens direcionadas para campanhas de marketing bancário. O projeto foca na resiliência do pipeline, utilizando uma fonte de dados local (CSV) para garantir o funcionamento independente de APIs externas.

🛠️ O Fluxo ETL
O processo foi dividido em três etapas fundamentais:

Extração (Extract): Leitura dos dados brutos (Nome, Conta e Tipo de Cartão) a partir de um arquivo dados_origem.csv.

Transformação (Transform): Aplicação de uma lógica em Python para gerar mensagens de boas-vindas e ofertas personalizadas com base nos nomes dos clientes.

Carregamento (Load): Exportação dos dados enriquecidos para um novo arquivo CSV (relatorio_final_marketing.csv), pronto para ser utilizado pela equipa de marketing.

💻 Tecnologias Utilizadas
Python 3: Linguagem base para o script.

Pandas: Biblioteca essencial para a manipulação e análise de dados.

📁 Estrutura de Arquivos
dados_origem.csv: Arquivo de entrada com os dados dos clientes.

desafio_etl.py: Script Python contendo toda a lógica do pipeline.

relatorio_final_marketing.csv: Arquivo final gerado após a execução do processo.
