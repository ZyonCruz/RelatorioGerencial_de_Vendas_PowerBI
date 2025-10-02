# RelatorioGerencial_de_Vendas_PowerBI
Desafio de Projeto: Relatório de Análise Financeira - Power BI Analyst (DIO)
Este repositório contém o projeto final do desafio de Power BI da Formação Power BI Analyst da DIO, utilizando a base de dados "Sample Financials" da Microsoft. O objetivo foi construir um relatório analítico e interativo, focado em boas práticas de design e navegabilidade, conforme as instruções fornecidas.

Visão Geral do Relatório
O relatório foi desenvolvido com duas páginas principais, cada uma focada em uma dimensão de análise (Vendas e Lucro), e incorpora recursos avançados como segmentadores (Slicers), botões de navegação e indicadores visuais (Cards).

1. Página Principal: Sales Report (Relatório de Vendas)
Esta página serve como um painel de controle executivo focado na performance de vendas da empresa.
Características e Requisitos Atendidos:
Estrutura Definida: Layout limpo e moderno, com indicadores (cards) no topo para fácil visualização das métricas chave.
Métricas Chave (Cards): Exibição de Total de Vendas, Unidades Vendidas, Soma de Descontos e Soma de COGS (Custo dos Produtos Vendidos).
Segmentador de Dados: Segmentador de data no topo ("Selecione a data") que permite a análise temporal dos dados.

Visuais Detalhados:
Gráfico de Área mostrando a Soma de Vendas por Mês.
Gráfico de Rosca (Sales x Segmento) para distribuição percentual das vendas.
Gráfico de Barras horizontal (Sales x Produto) para performance individual dos produtos.
Treemap e Map Chart combinados (Sales x Country) para análise geográfica das vendas.
Botões e Indicadores: Utilização de botões/ícones (como o ícone de lápis para edição de data) e a navegação implícita entre as páginas.

2. Segunda Página: Report de Lucro Detalhado (Profit Report)
Esta página oferece uma análise mais profunda sobre o lucro, explorando a performance por ano, país, produto e trimestre.

Características e Requisitos Atendidos:
Criação de Segunda Página: O requisito de criar uma segunda página foi cumprido com o "Report de Lucro Detalhado".
Navegabilidade (Botões de Página): A estrutura de abas na parte inferior do Power BI Desktop (Página 1 e Página 2) foi configurada para a transição entre os relatórios.
Segmentadores Interativos: Segmentadores de Ano e Country na parte central, permitindo filtrar todos os visuais da página.

Visuais de Lucro:
Gráfico de Dispersão (ou visual personalizado como o Radar Chart) mostrando o Soma de Profit por Produto.
Gráfico de Colunas Empilhadas/Agrupadas para Soma de Profit por Segmento.
Gráfico em Cascata/Colunas (Soma de Profit por Trimestre) que ilustra a evolução e o impacto de cada trimestre no lucro total.
Gráfico de Árvore (Árvore de Decomposição) detalhando a "Soma de Profit" por Ano e por País.

Estrutura de Navegação
Os botões de navegação entre as páginas (implícitos nas abas de navegação do próprio Power BI) garantem que o usuário possa facilmente alternar entre as visões de Vendas e Lucro para uma análise completa.
