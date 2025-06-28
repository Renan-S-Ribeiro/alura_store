# alura_store
Referente ao Challenge Alura Store na formação de Python para ciência de dados.

Este projeto tem como objetivo analisar e comparar os dados de vendas de quatro lojas diferentes, utilizando Python nativo e a biblioteca Matplotlib para visualizações. A análise explora o faturamento, categorias de produtos, avaliações dos clientes e custos de frete, além de identificar padrões relevantes entre as lojas.

## Dados

Os dados utilizados foram obtidos a partir de arquivos CSV públicos contendo registros de vendas das lojas. Cada arquivo inclui informações como:

- Produto
- Categoria do Produto
- Preço
- Frete
- Data da Compra
- Avaliação da Compra
- Coordenadas geográficas (latitude e longitude)
- Entre outros campos

## Análises realizadas

1. **Comparativo de Faturamento Total:**  
   Cálculo do faturamento total de cada loja considerando o preço dos produtos vendidos.

2. **Top 3 Categorias por Loja:**  
   Identificação das três categorias de produtos com maior faturamento em cada loja.

3. **Média de Avaliações dos Clientes:**  
   Cálculo da média das avaliações para cada loja para medir a satisfação dos clientes.

4. **Custo Médio de Frete:**  
   Análise do custo médio gasto em frete para cada loja.

5. **Produtos mais e menos vendidos:**  
   Identificação dos produtos com maior e menor número de vendas em cada loja.

6. **Visualizações:**  
   Foram gerados gráficos variados para facilitar a interpretação dos dados, incluindo:  
   - Gráfico combinado de barras e linha para faturamento e média de avaliação.  
   - Gráfico de pizza para custo médio de frete.  
   - Gráfico de barras horizontais para top 3 categorias por faturamento em cada loja.  

## Estrutura do projeto

- `AluraStoreBr_Renan.ipynb` : Arquivo do tipo Notebook para Google Colab.  
- `README.md` : este arquivo.

- ## Possíveis melhorias

- Incluir análise geográfica interativa utilizando bibliotecas como Folium.  
- Automatizar a leitura dos dados para suportar novas lojas ou arquivos.  


**Autor:** Renan da Silva Ribeiro Barbosa
**Data:** 2025
