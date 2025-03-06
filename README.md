# Relatório de Vendas e Perfil do Cliente

> **Dashboard Interativo para Análise de Vendas e Clientes**  
> Este repositório apresenta um **dashboard em Power BI** dividido em duas partes: **Relatório de Vendas** e **Perfil do Cliente**.  
> Ele foi construído para fornecer insights sobre o desempenho de vendas e o comportamento dos clientes, utilizando **Excel** como fonte de dados.
![Captura de tela 2025-03-06 131054](https://github.com/user-attachments/assets/94285a4d-847b-42e4-8f09-067c84bd4d88)
![Captura de tela 2025-03-06 131113](https://github.com/user-attachments/assets/08b1aba1-b21b-4d94-a0b2-87c3ceae5e85)

---

## 1. Por que (Why)

O principal objetivo deste projeto é **facilitar a compreensão dos dados de vendas e do perfil dos clientes**, convertendo dados brutos em informações valiosas. Assim, é possível:

- **Identificar oportunidades de crescimento** e otimizar o processo de vendas.  
- **Acompanhar métricas** relevantes (quantidade de vendas, valor total, canais de venda etc.).  
- **Compreender o perfil** dos clientes (idade, renda, localização) para orientar estratégias de marketing e vendas.

---

## 2. Como (How)

### 2.1. Fonte de Dados
- **Excel**: a base de dados está em formato `.xlsx`, contendo informações de vendas e clientes.  
- Para uso em produção, recomenda-se integrar com um sistema de ERP/CRM ou outro banco de dados.

### 2.2. Transformação e Limpeza
- **Power Query (no Power BI)** foi utilizado para limpeza de dados (remoção de duplicados, tratamento de valores nulos etc.).  
- As etapas de transformação foram documentadas no próprio **Power BI**.

### 2.3. Modelagem e Análise
- **Métricas de Vendas**: quantidade, valor total, ticket médio, canais de venda, sazonalidade etc.  
- **Perfil do Cliente**: idade, renda, distribuição geográfica.  
- **Dashboards Interativos** com filtros (estado, faixa de idade, faixa de renda, canal de venda etc.).

### 2.4. Visualização (Power BI)
- **Gráficos de Linha**: evolução mensal das vendas.  
- **Gráficos de Barras**: comparação de vendas por categoria/canal.  
- **Mapas**: distribuição geográfica das vendas.  
- **Cartões de Métrica**: total de vendas, total de clientes, média de idade, entre outros.

---

## 3. O que (What)

### 3.1. Relatório de Vendas
1. **Quantidade de Vendas Mês**  
   - Evolução das vendas ao longo do tempo (tendência mensal).  
2. **Valor Total em Vendas**  
   - Faturamento total em determinado período.  
3. **Quantidade de Vendas por Categoria**  
   - Comparação entre canais de venda (aplicativo, internet, móvel).  
4. **Mapa Geográfico**  
   - Identifica as regiões/estados com maior número de vendas.

### 3.2. Perfil do Cliente
1. **Quantidade de Clientes**  
   - Total de clientes ativos.  
2. **Média de Idade dos Clientes**  
   - Faixa etária predominante para estratégias de marketing.  
3. **Distribuição de Renda**  
   - Segmentação de clientes por renda, útil para ações de upsell e cross-sell.  
4. **Distribuição de Idade**  
   - Histograma para entender a concentração de clientes por faixa etária.

---

