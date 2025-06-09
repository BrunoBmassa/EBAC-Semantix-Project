Contexto:Add commentMore actions
Análise de Arboviroses Urbanas em Recife (2024)

As arboviroses urbanas, especialmente dengue, chikungunya e zika, constituem um sério desafio para a saúde pública no Brasil, com elevados níveis de ocorrência, episódios recorrentes e efeitos relevantes na população e nos serviços de saúde.
Essas doenças são transmitidas principalmente pelo mosquito Aedes aegypti, tendo as suas condições de proliferação favorecidas por fatores ambientais, como o acúmulo de água parada e a falta de saneamento básico.
Contexto

Objetivos:
As arboviroses urbanas — especialmente dengue, chikungunya e zika — representam um sério desafio para a saúde pública no Brasil, com altos níveis de ocorrência, episódios recorrentes e impactos relevantes tanto para a população quanto para os serviços de saúde.

Este projeto visa utilizar análise de dados exploratória (EDA) para identificar padrões, tendências e áreas críticas relacionadas a essas doenças, com foco em Recife (2024). A análise pretende:
Essas doenças são transmitidas principalmente pelo mosquito *Aedes aegypti*, cuja proliferação é favorecida por fatores como o acúmulo de água parada, infraestrutura precária e a falta de saneamento básico.

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
Objetivos

Método de acesso: Download direto
Este projeto tem como finalidade realizar uma Análise Exploratória de Dados (EDA) sobre os casos registrados de arboviroses no município de Recife, em 2024 com os seguintes objetivos:

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
Traçar o perfil das populações mais afetadas.
Analisar a sazonalidade e distribuição geográfica.
Avaliar a mortalidade e os impactos demográficos.
Facilitar a visualização e comunicação dos dados por meio de gráficos e tabelas interativas.

Remoção de registros nulos ou inconsistentes.
Fonte de Dados

Padronização de formatos de datas e nomes.
Os dados utilizados neste projeto são públicos, estruturados e disponibilizados pela [Prefeitura do Recife](http://dados.recife.pe.gov.br/ro/dataset/casos-de-dengue-zika-e-chikungunya):

Conversão e normalização de categorias textuais.
Datasets

Ajuste de codificações, delimitadores e colunas divergentes entre datasets.
- **Dengue**  
  [Download CSV](http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/ae10db21-511e-4295-a027-05af48adf13a/download/dengon-2024.csv)  
  [Espelho (Google Sheets)](https://docs.google.com/spreadsheets/d/11HHFG05XzBKzrzrHoC1PgJciDUQuCXzsH29v82K3uL8/edit?usp=sharing)

Análise Descritiva
- **Zika**  
  [Download CSV](http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/5597d197-b6c8-46af-bad5-473c9f6b3755/download/zika-2024.csv)  
  [Espelho (Google Sheets)](https://docs.google.com/spreadsheets/d/1QzunflQAZK0rI-kN4F9zXLLZKWREuJ1T3GlXWVQ6M3A/edit?usp=sharing)

Análise de distribuição de casos por:
- **Chikungunya**  
  [Download CSV](http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/f6e2e17d-63cd-4998-8bc0-9c19df5b996e/download/chikon-2024.csv)  
  [Espelho (Google Sheets)](https://docs.google.com/spreadsheets/d/1FoQn4MFsUAZlSN33Vf8N71TkTxAkLP8df4THfOCIdnU/edit?usp=sharing)

Gênero
Tecnologias Utilizadas

Faixa etária
- **Linguagem:** Python 3  
- **Ambiente:** Google Colab

Tipo de arbovirose
Bibliotecas Principais

Bairro ou distrito sanitário
- pandas, numpy — Manipulação e análise de dados
- rapidfuzz — Fuzzy matching para padronização de nomes
- unidecode — Normalização de textos acentuados

Mês de notificação
Metodologia

Contagem de casos confirmados, descartados, ignorados.
-Limpeza e Pré-processamento

Visualização de sazonalidade ao longo dos meses.
- Remoção de registros nulos ou inconsistentes
- Padronização de datas e nomes
- Normalização de categorias textuais
- Ajustes em codificações, delimitadores e colunas divergentes

Identificação de Variáveis Importantes e Correlações
-Análise Descritiva

Verificação de relações entre variáveis demográficas e desfecho da doença.
- Distribuição dos casos por:
  - Gênero
  - Faixa etária
  - Tipo de arbovirose
  - Bairro ou distrito sanitário
  - Mês de notificação
  - Contagem de casos confirmados, descartados e ignorados
  - Sazonalidade mês a mês

Comparações entre arboviroses quanto a idade, sexo e localização.
-Correlação e Padrões

Cálculo de correlações (quando aplicável) para identificar fatores relevantes.
- Relação entre perfil demográfico e tipo de doença
- Comparações entre arboviroses quanto a idade, sexo e localização
- Cálculo de correlações estatísticas de idade
- Identificação de padrões espaciais e temporais

Exploração de possíveis padrões geográficos e temporais.
