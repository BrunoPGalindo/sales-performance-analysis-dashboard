### **[EN]**

# Sales Data Analysis
This project's goal is to perform a comprehensive analysis of a Sales dataset based on a Star Schema structure. The primary goal is to evaluate sales performance, customer demographics, and product profitability across various territories over time. 
The analysis process involves gathering data from multiple relational tables (Fact and Dimensions), data modeling (creating relationships between tables), feature engineering (calculating profit margins, total costs), and visualization. The information obtained 
from this project aims to support strategic decision-making by identifying top-selling products, high-value customer segments, and regional sales trends.

# Data
The data source consists of a database structure on Excel. The data is organized into a Star Schema as follows:

**FactInternetSales**: The central transactional table containing sales metrics (Order Date, Product Key, Sales Amount, Quantity, Costs).

**DimProduct**: Descriptive attributes for products (Product Name, Color, Size, Subcategory).

**DimCustomer**: Customer demographic details (Name, Marital Status, Gender, Yearly Income, Education).

**DimGeography**: Location data (linking customers to specific cities, states, and countries).

**DimSalesTerritory**: Sales region classifications (North America, Europe, Pacific).

**DimDate**: A comprehensive date table for time analysis (Year, Quarter, Month, Day).

## **Key Engineered Features:**

`Total Revenue`: Calculated as `SalesAmount`

`Total Cost`: Calculated as `TotalProductCost`

`Gross Profit`: Calculated as `SalesAmount - TotalProductCost`

`Profit Margin`: Calculated as `Gross Profit / SalesAmount` to determine profitability percentages.

`Average Ticket`: Average sales amount per order.

# Personal Contact Details
* **Bruno P. Galindo** [brunopgalindo@hotmail.com](mailto:brunopgalindo@hotmail.com) -- Contact for inquiries regarding data.

# Getting Started
For this analysis project, the main dashboard and data model are contained within an Excel Macro-Enabled Workbook (.xlsm). To replicate or view the analysis:

1) Ensure all CSV source files are in the same directory if refreshing the data connection is required.
2) Open the `sales_analysis.xlsm` file.
3) Enable Macros/Content if prompted to allow interactive features to run.
4) Navigate through the spreadsheet tabs to view the dashboard and pivot tables.

# Requirements
To run this project, you will need the following software:

**Step 1**: Open Microsoft Excel Ensure you have a version that supports Power Pivot or Data Models (the most up-to-date one, preferably).

**Step 2**: Load the file Open `sales_analysis.xlsm`

**Step 3**: Use the dashboard interactivity and filters within the Excel file to explore the data dynamically.

# Authors
* Bruno P. Galindo - Personal Project - https://www.linkedin.com/in/brunopgalindo/

# Project Motivation
* The intention of the project is to challenge me and develop critical thinking skills regarding data modeling and Star Schema concepts, and to generate positive insights through business intelligence.
* This is a public dataset structure (similar to AdventureWorks) and the only purpose of it is to be used for study. None of the data is sensitive in any way.
* Inspiration: Corporate sales reporting and financial performance analysis.
---

# **[PT/BR]**

# Análise de Dados de Vendas
O objetivo deste projeto é realizar uma análise abrangente de um conjunto de dados de Vendas com base em uma estrutura Star Schema (Esquema Estrela). O objetivo principal é avaliar o desempenho de vendas, a demografia dos clientes e a lucratividade dos 
produtos em vários territórios ao longo do tempo. O processo de análise envolve a coleta de dados de várias tabelas relacionais (Fato e Dimensões), modelagem de dados (criação de relacionamentos entre tabelas), engenharia de recursos (cálculo de margens de lucro, 
custos totais) e visualização. As informações obtidas neste projeto visam apoiar a tomada de decisões estratégicas, identificando os produtos mais vendidos, segmentos de clientes de alto valor e tendências de vendas regionais.

# Dados
A fonte de dados consiste em uma estrutura de banco de dados no Excel. Os dados estão organizados em um Star Schema da seguinte forma:

**FactInternetSales**: A tabela transacional central contendo métricas de vendas (Data do Pedido, Chave do Produto, Valor de Vendas, Quantidade, Custos).

**DimProduct**: Atributos descritivos para produtos (Nome do Produto, Cor, Tamanho, Subcategoria).

**DimCustomer**: Detalhes demográficos do cliente (Nome, Estado Civil, Gênero, Renda Anual, Escolaridade).

**DimGeography**: Dados de localização (vinculando clientes a cidades, estados e países específicos).

**DimSalesTerritory**: Classificações de região de vendas (América do Norte, Europa, Pacífico).

**DimDate**: Uma tabela de data abrangente para análise temporal (Ano, Trimestre, Mês, Dia).

## **Variáveis Chaves Calculadas:**
`Total Revenue`: Calculado como `SalesAmount`

`Total Cost`: Calculado como `TotalProductCost`

`Gross Profit`: Calculado como `SalesAmount - TotalProductCost`

`Profit Margin`: Calculado como `Gross Profit / SalesAmount` para determinar porcentagens de lucratividade.

`Average Ticket`: Valor médio de vendas por pedido.

# Dados Pessoais para Contato
* **Bruno P. Galindo** [brunopgalindo@hotmail.com](mailto:brunopgalindo@hotmail.com) -- Contato para perguntas relacionadas aos dados.

# Começando
Para este projeto de análise, o painel principal e o modelo de dados estão contidos em uma pasta de trabalho habilitada para macro do Excel (.xlsm). Para replicar ou visualizar a análise:

1) Garanta que todos os arquivos de origem CSV estejam no mesmo diretório, caso seja necessário atualizar a conexão de dados.
2) Abra o arquivo `sales_analysis.xlsm`.
3) Habilite Macros/Conteúdo se solicitado para permitir a execução de recursos interativos.
4) Navegue pelas abas da planilha para visualizar o dashboard e as tabelas dinâmicas.

# Requisitos
Para executar este projeto, você precisará do seguinte software:

**Passo 1**:Abra o Microsoft Excel. Certifique-se de ter uma versão que suporte Power Pivot ou Modelos de Dados (a mais atualizada, de preferência).

**Passo 2**: Carregue o arquivo. Abra `sales_analysis.xlsm`

**Passo 3**: Use a interatividade do painel e os filtros dentro do arquivo Excel para explorar os dados dinamicamente.

# Autores
* Bruno P. Galindo - Personal Project - https://www.linkedin.com/in/brunopgalindo/

# Project Motivation
* A intenção do projeto é me desafiar e desenvolver habilidades de pensamento crítico em relação à modelagem de dados e conceitos de Star Schema, e gerar insights positivos por meio de inteligência de negócios.
* Esta é uma estrutura de conjunto de dados pública (semelhante ao AdventureWorks) e o único objetivo é ser usada para estudo. Nenhum dado é sensível de forma alguma.
* Inspiração: Relatórios de vendas corporativas e análise de desempenho financeiro.




































