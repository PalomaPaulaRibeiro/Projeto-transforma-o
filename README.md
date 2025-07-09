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


🧹 Pré-processamento Final
Ao fim do processo, temos um DataFrame com colunas devidamente tipadas e limpas, com 3.818 registros prontos para análise.


✅ Requisitos
Python 3.x

Pandas

NumPy

