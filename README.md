Contexto:

As arboviroses urbanas, especialmente dengue, chikungunya e zika, constituem um sério desafio para a saúde pública no Brasil, com elevados níveis de ocorrência, episódios recorrentes e efeitos relevantes na população e nos serviços de saúde.
Essas doenças são transmitidas principalmente pelo mosquito Aedes aegypti, tendo as suas condições de proliferação favorecidas por fatores ambientais, como o acúmulo de água parada e a falta de saneamento básico.

Objetivos:

Este projeto visa utilizar análise de dados exploratória (EDA) para identificar padrões, tendências e áreas críticas relacionadas a essas doenças, com foco em Recife (2024). A análise pretende:

Traçar o perfil das populações mais afetadas.

Analisar sazonalidade e distribuição geográfica.

Avaliar mortalidade e impactos demográficos.

Auxiliar na visualização e comunicação dos dados via gráficos e tabelas.

Fonte de dados:

Site com as fontes de dados escolhidas:

As fontes de dados escolhidas são dados públicos estruturados através de datasets alimentados e compartilhados referente 
aos casos de Dengue, Zika Virus e Chikungunya no ano de 2024 disponíveis no site da prefeitura de Recife (http://dados.recife.pe.gov.br/ro/dataset/casos-de-dengue-zika-e-chikungunya)

Datasets:

Dengue

Link: http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/ae10db21-511e-4295-a027-05af48adf13a/download/dengon-2024.csv

Tipo de dados:  Estruturados (CSV) 

Método de acesso: Download direto

Opcional (caso a url não esteja funcionando): https://docs.google.com/spreadsheets/d/11HHFG05XzBKzrzrHoC1PgJciDUQuCXzsH29v82K3uL8/edit?usp=sharing

Zika

Link: http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/5597d197-b6c8-46af-bad5-473c9f6b3755/download/zika-2024.csv

Tipo de dados:  Estruturados (CSV) 

Método de acesso: Download direto

Opcional (caso a url não esteja funcionando): https://docs.google.com/spreadsheets/d/1QzunflQAZK0rI-kN4F9zXLLZKWREuJ1T3GlXWVQ6M3A/edit?usp=sharing

Chikungunya

Link: http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/f6e2e17d-63cd-4998-8bc0-9c19df5b996e/download/chikon-2024.csv

Tipo de dados:  Estruturados (CSV) 

Método de acesso: Download direto

Opcional (caso a url não esteja funcionando): https://docs.google.com/spreadsheets/d/1FoQn4MFsUAZlSN33Vf8N71TkTxAkLP8df4THfOCIdnU/edit?usp=sharing

Tecnologias escolhidas

Linguagem: Python 3

Ambiente: Google Colab

Bibliotecas:

pandas, numpy: manipulação de dados

rapidfuzz: tratamento de nomes via fuzzy matching

unidecode: normalização de texto

Metodologia:

Limpeza e Pré-processamento dos Dados

Remoção de registros nulos ou inconsistentes.

Padronização de formatos de datas e nomes.

Conversão e normalização de categorias textuais.

Ajuste de codificações, delimitadores e colunas divergentes entre datasets.

Análise Descritiva

Análise de distribuição de casos por:

Gênero

Faixa etária

Tipo de arbovirose

Bairro ou distrito sanitário

Mês de notificação

Contagem de casos confirmados, descartados, ignorados.

Visualização de sazonalidade ao longo dos meses.

Identificação de Variáveis Importantes e Correlações

Verificação de relações entre variáveis demográficas e desfecho da doença.

Comparações entre arboviroses quanto a idade, sexo e localização.

Cálculo de correlações (quando aplicável) para identificar fatores relevantes.

Exploração de possíveis padrões geográficos e temporais.
