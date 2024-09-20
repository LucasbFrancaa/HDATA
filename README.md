# HDATA

Armazenamento no GCS:

Os arquivos financeiros são enviados para o Google Cloud Storage.
Processamento Automático com Cloud Functions:

Uma Cloud Function é acionada quando os arquivos são carregados no GCS, realizando o mapeamento de aderência e o enriquecimento dos dados.
Exportação dos Dados Enriquecidos:

Os dados processados são salvos de volta no GCS ou enviados diretamente ao BigQuery.
Carregamento para o BigQuery:

O arquivo enriquecido é carregado para o BigQuery para armazenamento e análises.
Data Warehouse (DW) Estruturado no BigQuery:

Utilizamos um Esquema Estrela no BigQuery, separando os dados em tabelas de fato e dimensão, otimizando a consulta e a análise de dados financeiros.
Benefícios da Solução no GCP
Automatização: Todo o processo de ingestão, enriquecimento, e armazenamento dos dados é automatizado usando Cloud Functions e BigQuery.
Escalabilidade: O GCP oferece escalabilidade para lidar com grandes volumes de dados financeiros.
Otimização: A estrutura em Esquema Estrela no BigQuery garante consultas rápidas e eficazes.
