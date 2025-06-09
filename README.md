Análise de Arboviroses Urbanas em Recife (2024)

Contexto

As arboviroses urbanas — especialmente dengue, chikungunya e zika — representam um sério desafio para a saúde pública no Brasil, com altos níveis de ocorrência, episódios recorrentes e impactos relevantes tanto para a população quanto para os serviços de saúde.

Essas doenças são transmitidas principalmente pelo mosquito *Aedes aegypti*, cuja proliferação é favorecida por fatores como o acúmulo de água parada, infraestrutura precária e a falta de saneamento básico.

Objetivos

Este projeto tem como finalidade realizar uma Análise Exploratória de Dados (EDA) sobre os casos registrados de arboviroses no município de Recife, em 2024 com os seguintes objetivos:

Traçar o perfil das populações mais afetadas.
Analisar a sazonalidade e distribuição geográfica.
Avaliar a mortalidade e os impactos demográficos.
Facilitar a visualização e comunicação dos dados por meio de gráficos e tabelas interativas.

Fonte de Dados

Os dados utilizados neste projeto são públicos, estruturados e disponibilizados pela [Prefeitura do Recife](http://dados.recife.pe.gov.br/ro/dataset/casos-de-dengue-zika-e-chikungunya):

Datasets

- **Dengue**  
  [Download CSV](http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/ae10db21-511e-4295-a027-05af48adf13a/download/dengon-2024.csv)  
  [Espelho (Google Sheets)](https://docs.google.com/spreadsheets/d/11HHFG05XzBKzrzrHoC1PgJciDUQuCXzsH29v82K3uL8/edit?usp=sharing)

- **Zika**  
  [Download CSV](http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/5597d197-b6c8-46af-bad5-473c9f6b3755/download/zika-2024.csv)  
  [Espelho (Google Sheets)](https://docs.google.com/spreadsheets/d/1QzunflQAZK0rI-kN4F9zXLLZKWREuJ1T3GlXWVQ6M3A/edit?usp=sharing)

- **Chikungunya**  
  [Download CSV](http://dados.recife.pe.gov.br/dataset/2a9b1c39-0700-4ddf-9a10-b3c8d5d9396c/resource/f6e2e17d-63cd-4998-8bc0-9c19df5b996e/download/chikon-2024.csv)  
  [Espelho (Google Sheets)](https://docs.google.com/spreadsheets/d/1FoQn4MFsUAZlSN33Vf8N71TkTxAkLP8df4THfOCIdnU/edit?usp=sharing)

Tecnologias Utilizadas

- **Linguagem:** Python 3  
- **Ambiente:** Google Colab

Bibliotecas Principais

- pandas, numpy — Manipulação e análise de dados
- rapidfuzz — Fuzzy matching para padronização de nomes
- unidecode — Normalização de textos acentuados

Metodologia

-Limpeza e Pré-processamento

- Remoção de registros nulos ou inconsistentes
- Padronização de datas e nomes
- Normalização de categorias textuais
- Ajustes em codificações, delimitadores e colunas divergentes

-Análise Descritiva

- Distribuição dos casos por:
  - Gênero
  - Faixa etária
  - Tipo de arbovirose
  - Bairro ou distrito sanitário
  - Mês de notificação
  - Contagem de casos confirmados, descartados e ignorados
  - Sazonalidade mês a mês

-Correlação e Padrões

- Relação entre perfil demográfico e tipo de doença
- Comparações entre arboviroses quanto a idade, sexo e localização
- Cálculo de correlações estatísticas de idade
- Identificação de padrões espaciais e temporais

