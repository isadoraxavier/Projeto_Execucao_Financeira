# Projeto_Execucao_Financeira
Análise de Dados de Execução Financeira do Governo do Estado do Ceará

#Sobre
O banco de dados "execucao_financeira" contém informações sobre as despesas de execução financeira. Ele armazena os detalhes de cada despesa, como ano, código do órgão, credor, fonte de recursos, função, item, modalidade de licitação, programa, subfunção, valores empenhados, liquidados, pagos e restos a pagar, entre outros dados.

# Objetivo 
O projeto "Execução Financeira" busca explorar os dados do Governo do Ceará, utilizando SQL no banco Postgres e responder algumas perguntas:
  1) Qual mês teve maior custo? Totais Gerais de Valor por ano e mês; 
  2) Qual função e subfunção teve maior orçamento? Totais Gerais de Função e/ou Subfunção por ano e mês;
  3) Qual fonte mais solicitou recursos? Totais Gerais de Fonte e/ou Programa por ano e mês;
  4) Qual credor mais solicitou licitações? Totais Gerais de Item Elemento e/ou Credor por ano e mês.

# Base de Dados e Banco de Dados 
Base: Execução Financeira V4
Tuplas: 2.025.116
Colunas:
id: Identificador único da despesa (integer)
num_ano: Ano da despesa (character varying)
cod_ne: Código da despesa (character varying)
codigo_orgao: Código do órgão (character varying)
dsc_orgao: Descrição do órgão (character varying)
cod_credor: Código do credor (character varying)
dsc_nome_credor: Nome do credor (character varying)
cod_fonte: Código da fonte de recursos (character varying)
dsc_fonte: Descrição da fonte de recursos (character varying)
cod_funcao: Código da função (character varying)
dsc_funcao: Descrição da função (character varying)
cod_item: Código do item (character varying)
dsc_item: Descrição do item (character varying)
cod_item_elemento: Código do elemento do item (character varying)
dsc_item_elemento: Descrição do elemento do item (character varying)
cod_item_categoria: Código da categoria do item (character varying)
dsc_item_categoria: Descrição da categoria do item (character varying)
cod_item_grupo: Código do grupo do item (character varying)
dsc_item_grupo: Descrição do grupo do item (character varying)
dsc_modalidade_licitacao: Descrição da modalidade de licitação (character varying)
cod_item_modalidade: Código da modalidade de licitação (character varying)
dsc_item_modalidade: Descrição da modalidade de licitação do item (character varying)
cod_programa: Código do programa (character varying)
dsc_programa: Descrição do programa (character varying)
cod_subfuncao: Código da subfunção (character varying)
dsc_subfuncao: Descrição da subfunção (character varying)
num_sic: Número do SIC (character varying)
cod_np: Código NP (character varying) - valor padrão: 0
vlr_empenho: Valor empenhado (numeric)
vlr_liquidado: Valor liquidado (numeric)
valor_pago: Valor pago (numeric)
vlr_resto_pagar: Valor a pagar (numeric)
dth_empenho: Data do empenho (date)
dth_pagamento: Data do pagamento (date)
dth_liquidacao: Data da liquidação (date)
dth_processamento: Data de processamento (date)
num_ano_np: Ano do NP (character varying)
Chave Primária: id

#Link Final (Dashboard) 
https://app.powerbi.com/view?r=eyJrIjoiMTQzNDQ0YTEtZmQ2ZC00NzYwLTg0OWMtOGQ3ZGJlOTEwODcxIiwidCI6ImIxNTZhNTQxLWUyMzYtNGVkYi05MWJmLWZjYTI1YzcwMDRmOSJ9
