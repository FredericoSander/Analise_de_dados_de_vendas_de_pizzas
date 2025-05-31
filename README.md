# Análise de dados de vendas de pizzas

## Índice 

* [Índice](#índice)
* [Descrição do projeto](#descrição-do-projeto)
* [Tecnologia utilizadas](#tecnologias-utilizadas)
* [Estrutura do projeto](#estrutura-do-projeto)
* [Modelagem de dados](#modelagem-de-dados)
* [Base de dados](#base-de-dados)
* [Funcionalidades principais](#funcionalidades-principais)
* [Insights e Descobertas Analíticas](#insights-e-descobertas-analíticas)
* [Como utilizar e atualizar os dados](#como-utilizar-e-atualizar-os-dados)
* [Licença](#licença)
* [Acesse o projeto](#acesse-o-projeto)
* [Autor](#autor)

## Descrição do projeto

O projeto consiste no desenvolvimento completo de um dashboard analítico completo para análise de vendas de uma pizzaria, demostrando competências em Business Intelligence, visualização de dados e análise de performance comercial.

## Tecnologias utilizadas

- Power Bi Desktop - Desenvolimento do Dashboard.
- Power Query - Tratamento e transformação dos dados.
- DAX (Data Analysis Expressions) - Criação de medidas e cáculos.
- Dataset Público - kaggle Pizza Sales Dataset.
- Power Bi App - Publicação do Dashboard.

## Estrutura do projeto

### Processo de ETL (Extract, Transform, Load)

1. **Extração**: Importação do arquivo xlsx para o Power BI
2. **Transformação**: Limpeza e padronização dos dados usando Power Query.
3. **Carregamento**: Modelagem dos dados no ambiente Power Bi.

## Modelagem dos dados

- A modelagem consistiu na criação das tabelas de fato e dimensão, estabelecimento de relacionamento entre as entidades e na otimização da estrutura para performance.

## Base de dados 
A base de dados utilizada contém as seguintes colunas:

| Coluna | Descrição |
|--------|-----------|
| pizza_id:| Um identificador exclusivo atribuído a cada variante de pizza distinta disponível para pedido.|
| order_id | Um identificador exclusivo para cada pedido feito, que vincula a várias pizzas.|
| pizza_name_id | Um identificador que vincula a um nome específico da pizza.|
| quantity | O número de unidades de uma variante específica de pizza pedida em um pedido.|
| order_date | A data em que o pedido foi feito.|
| order_time | A hora em que o pedido foi feito.|
| unit_price | O custo de uma única unidade da variante específica de pizza.|
| total_price | O custo agregado de todas as unidades de uma variante específica de pizza em um pedido.|
| pizza_size | Representa o tamanho da pizza (por exemplo, pequena, média, grande).|
| pizza_category | Indica a categoria da pizza, como vegetariana, não vegetariana, etc.|
| pizza_ingredients | Fornece uma lista ou descrição dos ingredientes usados ​​na pizza.|
| pizza_name | Especifica o nome da variante específica de pizza pedida.|

## Funcionalidades principais

O relatório foi desenvolvido para apresentar as seguintes métricas:

### Métricas principais

- Faturamento total do período
- Total de pizzas vendidas
- Total de pedidos recebidos
- Variedades de produtos oferecidos

### Funcionalidades interativas

- Filtros dinâmicos de mês e categorias
- Análise granular do período selecionado
- Métricas especificas de período

### Análises implementadas

- Evolução diária das vendas com linha de tendência
- Média de vendas por hora do dia
- Ranking dos produtos mais vendidos
- Análise de sazonalidade

### Visualizações e insights

- Cartão com KPIs: Faturamento, Total de pizzas, Total de pedidos e N° de produtos
- Gráfico de barras: Vendas por categória (Classic, Supreme, Veggie, Chicken)
- Gráfico de linhas: Evolução mensal do faturamento
- Tabela detalhada: Breakdown por categoria e tamanho
- Gráfico de área: Evolução de pedidos e vendas mensais

## Insights e Descobertas Analíticas

### Performance por Categoria

- Classic: Categoria líder com 14.579 unidades vendidas (R$ 220.053,10)
- Supreme: Segunda posição com 11.777 unidades (R$ 208.197,00)
- Chicken: Terceira colocação com 10.815 unidades (R$ 195.919,50)
- Veggie: Menor volume com 11.449 unidades (R$ 193.690,45)

### Padrões Temporais Identificados

- Sazonalidade mensal de pedidos: Os meses de Janeiro, março, maio, julho e agosto apresentaram mais de 1800 pedidos.
- Sazonalidade mensal de unidades vendidas: Já os meses de fevereiro, setembro, outubro, e dezembro, foram os meses em que o numero de unidades vendidas foi inferior a 4000 unidades.
- Comportamento diário: Variações significativas durante o mês, onde a média diária de vendas varia em torno de 135 unidades, sendo que o mês de outubro apresentou a maior média diária de endas com 140 unidade e o mês de dezembro apresentou a menor média diária com apenas 129 unidades.
- Padrão horário: Concentração de vendas ocorre em horários específicos próximo das 12 horas e entre 16h e 18 horas.

### Produtos de Destaque

- The Pepperoni Pizza: Produto com mais unidades vendidas em um único mês sendo 238 unidade vendidas no mês de maio.
- The Classic Deluxe Pizza: Produto com mais unidades vendidas no ano sendo 2416 unidade vendidas.
- Forte performance de pizzas com frango na composição.

## Como utilizar e atualizar os dados

- Baixe o repositório contendo os arquivos de dados, imagens e do projeto.
- Instale o Power Bi Desktop. 
- Abra o arquivo pbix com o Power BI Desktop.
- Configure no Power BI Desktop o caminho do o arquivo Data Model - Pizza Sales.xlsx e Nº de pessoas xlsx.
- O arquivo Data Model - Pizza Sales.xlsx poderá se atualizado com a inserção de novos dados para extender o periodo de análise ou a cada nova atulização realizada pelo autores.

## Licença

Este projeto está licenciado sob a licença MIT:

Para visualizar a licença clique [aqui](https://github.com/FredericoSander/Analise_de_dados_de_vendas_de_pizzas/blob/main/LICENSE) ou acesse: https://github.com/FredericoSander/Analise_de_dados_de_vendas_de_pizzas/blob/main/LICENSE

## Acesso ao projeto

Você pode acessar e baixar este projeto através do seguinte link:
GitHub - [Análise de dados de vendas de pizzas](https://app.powerbi.com/view?r=eyJrIjoiM2Y5ZTUyMDEtZTI1YS00YjYwLWIyYjItNjhhODc1MjljMWM5IiwidCI6IjMxMTU3MGI0LTFhYmMtNGRmZS05NjgzLTFlNGQ4ZDZmOGExNiJ9&pageName=931fa159aa003886c901)

Ou clone o repositório usando o comando:
git clone https://github.com/FredericoSander/Analise_de_dados_de_vendas_de_pizzas.git

- Requisitos para execução: Microsoft Power BI Desktop
- Recomendado: 4GB de RAM para melhor desempenho com grandes volumes de dados.

## Autor
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/136928502?s=96&v=4" width=115><br><sub>Frederico Sander</sub>](https://github.com/FredericoSander)
| :---: | 
