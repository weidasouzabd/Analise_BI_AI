# Análise de Dados de Vendas Meganium

## Visão Geral do Projeto

Este projeto tem como objetivo principal realizar uma análise aprofundada dos dados de vendas dos produtos "Meganium". Os dados foram coletados de diversas plataformas de e-commerce, incluindo Etsy, Shopee e AliExpress. Através desta análise, busca-se obter insights valiosos sobre o desempenho dos produtos, identificar tendências de mercado, compreender o comportamento do consumidor e, por fim, otimizar estratégias comerciais e de marketing.

## Fonte de Dados

Os dados utilizados para esta análise foram fornecidos e correspondem a um registro detalhado de transações de vendas dos produtos Meganium. O conjunto de dados original é composto por 60 registros e 14 colunas, contendo informações cruciais sobre cada venda.

## Estrutura dos Dados

A tabela de vendas utilizada neste projeto possui as seguintes colunas:

-   `sku`: Código de identificação único para cada produto.
-   `product_sold`: Nome comercial do produto que foi vendido.
-   `date`: Data e hora exata em que a venda foi realizada.
-   `quantity`: Número de unidades do produto vendidas em uma transação específica.
-   `unit_price`: Preço de uma única unidade do produto.
-   `total_price`: Valor total da transação (calculado como `quantity` * `unit_price`).
-   `currency`: Moeda na qual a transação foi efetuada (e.g., EUR, USD, GBP).
-   `site`: Plataforma de e-commerce onde a venda ocorreu (Etsy, Shopee, AliExpress).
-   `discount_coupon`: Identificador do cupom de desconto aplicado na compra, se houver.
-   `discount_value`: O valor financeiro total do desconto concedido na transação.
-   `buyer_birth_date`: Data de nascimento do comprador.
-   `buyer_name`: Nome completo do comprador.
-   `delivery_country`: País para onde o produto foi enviado.
-   `invoice_id`: Identificador único para cada fatura ou transação de venda.

## Objetivos da Análise

As análises que podem ser realizadas com este conjunto de dados são diversas e visam responder a questões estratégicas, incluindo:

1.  **Desempenho de Vendas por Produto:**
    *   Determinar quais produtos geram a maior receita e possuem o maior volume de vendas.
    *   Comparar a popularidade de cada produto em diferentes plataformas de venda.
    *   Monitorar a evolução do desempenho de vendas de cada produto ao longo do tempo.

2.  **Análise por Plataformas de Venda:**
    *   Comparar a performance (receita e quantidade) entre as plataformas Etsy, Shopee e AliExpress.
    *   Identificar qual plataforma é mais eficiente ou rentável para cada tipo de produto.

3.  **Análise Geográfica das Vendas:**
    *   Identificar os países que são os maiores mercados em termos de receita e volume de vendas.
    *   Detectar padrões e tendências de vendas específicas por região.

4. **Tendências de Vendas ao Longo do Tempo:**
    *   Identificar períodos de alta e baixa nas vendas (sazonalidades).
    *   Acompanhar o crescimento ou declínio das vendas gerais e por categoria de produto.

5.  **Demografia dos Compradores:**
    *   Analisar o perfil etário dos compradores a partir da data de nascimento.
    *   Correlacionar a faixa etária com as preferências de produtos ou o valor gasto.

6.  **Valor Médio do Pedido:**
    *   Calcular o valor médio de cada transação e a quantidade média de itens por pedido.

7.  **Distribuição de Vendas por Moeda:**
    *   Analisar a proporção das vendas realizadas em EUR, USD e GBP.

## Como Contribuir

Este projeto é um ponto de partida para análises mais aprofundadas. Contribuições são sempre bem-vindas! Se você tiver ideias para novas análises, melhorias na visualização dos dados, otimizações de código (caso haja) ou qualquer outra sugestão, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

---
