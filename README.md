🏡 Análise de Dados de Hospedagens
Este projeto realiza a leitura, limpeza e preparação de um conjunto de dados sobre hospedagens (em formato JSON), com o objetivo de organizar e transformar as informações para análise exploratória ou futura modelagem.

📦 Estrutura do Projeto
O código faz o seguinte:

1. Leitura dos Dados
Carrega o arquivo JSON com informações detalhadas sobre imóveis/hospedagens:

2. Normalização dos Dados


3. Explosão das Listas
Algumas colunas com listas são "explodidas", ou seja, transformadas em múltiplas linhas para facilitar a análise:

4. Conversão de Tipos
Os tipos de dados são ajustados:


5. Limpeza de Texto
A coluna descricao_local é convertida para letras minúsculas
Caracteres especiais são removidos usando expressões regulares
A string é transformada em uma lista de palavras
___

📊 Precificação Inteligente — Manipulação e Transformação de Dados com Pandas
Este módulo teve como foco o aprimoramento de habilidades fundamentais para a análise e transformação de dados voltados à precificação de produtos e serviços. 
___

✅ Conteúdos Aprendidos

🧾 Manipulação de Dados em Listas e Conversão de Tipos
Identificar e transformar elementos dentro de listas em novas linhas de um DataFrame com o método explode;

Converter dados textuais em valores numéricos utilizando o método astype;

Utilizar a função apply para tratar textos com dados numéricos e prepará-los para conversão;

Aplicar applymap para tratar múltiplas colunas elemento a elemento de forma eficiente.
___

📝 Processamento de Texto
Manipular elementos textuais em um DataFrame;

Utilizar expressões regulares (regex) para tratar e extrair padrões de texto;

Transformar textos em listas;

Realizar a tokenização de strings, separando os textos em unidades menores (tokens) para análises mais granulares.
___

📅 Manipulação de Datas e Horários
Identificar colunas com dados do tipo datetime;

Converter colunas textuais para o tipo datetime com métodos apropriados;

Realizar transformações e extrações em colunas do tipo datetime (como ano, mês, dia, hora) utilizando métodos do Pandas.
___

🛠 Ferramentas Utilizadas
Python

Pandas

Expressões Regulares (Regex)
___

🎯 Objetivo Final
Capacitar o(a) analista a tratar e transformar dados brutos em informações estruturadas e limpas, essenciais para alimentar modelos de precificação e gerar insights de negócio.


