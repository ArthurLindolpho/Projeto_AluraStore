# Análise Comparativa de Lojas para Decisão de Venda

## Visão Geral do Projeto

Este projeto visa realizar uma análise comparativa aprofundada de dados de vendas de quatro lojas distintas. O objetivo principal é identificar qual das lojas possui o desempenho mais fraco, levando a uma decisão informada sobre qual unidade deve ser vendida.

## Objetivos da Análise

Para embasar a decisão de venda, a análise focou nos seguintes pontos chave:

1.  **Faturamento Total**: Comparar a receita gerada por cada loja.
2.  **Vendas por Categoria de Produto**: Entender a distribuição de vendas entre diferentes categorias em cada loja.
3.  **Média de Avaliação dos Clientes**: Avaliar a satisfação geral dos clientes por loja.
4.  **Produtos Mais e Menos Vendidos**: Identificar os itens de maior e menor sucesso de vendas em cada unidade.
5.  **Frete Médio**: Analisar o custo médio de frete por loja.

## Fonte dos Dados

Os dados utilizados neste projeto foram carregados a partir de arquivos CSV disponíveis no GitHub, um para cada loja:

*   **Loja 1**: [loja_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
*   **Loja 2**: [loja_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
*   **Loja 3**: [loja_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
*   **Loja 4**: [loja_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

## Etapas da Análise

1.  **Importação dos Dados**: Carregamento dos arquivos CSV para DataFrames do Pandas.
2.  **Análise do Faturamento**: Cálculo e visualização do faturamento total de cada loja por meio de um gráfico de barras.
3.  **Vendas por Categoria**: Cálculo das contagens de vendas por categoria de produto para cada loja e visualização em gráficos de pizza, mostrando a distribuição percentual.
4.  **Média de Avaliação das Lojas**: Cálculo da média das avaliações de compra para cada loja e apresentação em um gráfico de barras.
5.  **Produtos Mais e Menos Vendidos**: Identificação dos 5 produtos mais e 5 menos vendidos em cada loja e visualização em gráficos de contagem.
6.  **Frete Médio por Loja**: Cálculo e visualização do frete médio de cada loja em um gráfico de barras.

## Principais Descobertas

*   **Faturamento**: A Loja 1 apresentou o maior faturamento, enquanto a Loja 4 teve o menor faturamento, com uma diferença significativa de aproximadamente R$ 150.000,00 em relação à Loja 1.
*   **Vendas por Categoria**: Todas as lojas mostraram um comportamento semelhante, com 'eletrônicos' sendo a categoria mais vendida. As categorias menos vendidas variaram, mas a proximidade percentual entre as categorias foi considerável em todas as unidades.
*   **Avaliações de Clientes**: As médias de avaliação dos clientes foram muito parecidas em todas as lojas, indicando um nível de satisfação consistentemente similar.
*   **Frete Médio**: O frete médio foi bastante similar entre as lojas, com a Loja 4 apresentando um valor ligeiramente mais baixo.
*   **Produtos Vendidos**: Os produtos mais e menos vendidos variam consideravelmente entre as lojas, o que pode ser influenciado por fatores como localização ou público-alvo específico de cada unidade.

## Conclusão

Com base na análise do faturamento, que revelou uma diferença substancial entre as lojas, e considerando que os outros indicadores (avaliações, categorias de produtos e frete) apresentaram comportamentos muito semelhantes entre si, a **Loja 4** é a candidata ideal para ser vendida. Seu faturamento significativamente menor a torna a opção com o menor impacto na receita geral, especialmente porque os demais indicadores não justificam sua manutenção em detrimento das outras unidades.
