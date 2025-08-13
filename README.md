# projeto-python-blenersilva
📊 Dashboard de Salários na Área de Dados
Este projeto é um dashboard interativo criado com Streamlit para análise de salários na área de dados, com base em um dataset público hospedado no GitHub. Ele permite filtrar dados por ano, senioridade, tipo de contrato e tamanho da empresa, além de gerar métricas e gráficos dinâmicos.

🚀 Funcionalidades
Filtros interativos na barra lateral:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

Métricas gerais:

Salário médio

Salário máximo

Total de registros

Cargo mais frequente

Visualizações:

Top 10 cargos por salário médio (gráfico de barras)

Distribuição de salários (histograma)

Proporção dos tipos de trabalho (gráfico de pizza)

Mapa mundial com salários médios de Data Scientists por país

Tabela detalhada com os dados filtrados

📂 Estrutura do Projeto
arduino
Copiar
Editar
app.py           # Código principal do dashboard
📦 Requisitos
Antes de rodar o projeto, instale as dependências:

bash
Copiar
Editar
pip install streamlit pandas plotly
▶️ Como executar
Clone ou baixe o repositório contendo o app.py.

No terminal, navegue até a pasta do projeto.

Execute:

bash
Copiar
Editar
streamlit run app.py
O navegador abrirá o dashboard interativo.

📊 Fonte dos Dados
O dashboard utiliza um CSV hospedado no GitHub:

arduino
Copiar
Editar
https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
O dataset contém informações sobre:

Ano

Cargo

Salário em USD

Tipo de contrato

Senioridade

Tamanho da empresa

Modalidade de trabalho (remoto/presencial/híbrido)

País de residência

🖼️ Exemplo de Uso
Filtre por ano e tipo de contrato para comparar tendências salariais.

Analise diferenças entre tamanhos de empresas.

Veja quais cargos pagam mais na média.

Explore a distribuição de salários para entender a dispersão dos valores.

📌 Observações
O dashboard é totalmente interativo: os gráficos e métricas se atualizam automaticamente conforme os filtros são aplicados.

Caso os filtros resultem em nenhum dado, mensagens de aviso são exibidas.

