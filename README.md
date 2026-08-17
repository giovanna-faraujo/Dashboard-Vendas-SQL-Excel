# Análise de Performance de Vendas e Marketing

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/pt-br/microsoft-365/excel)
[![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=database&logoColor=white)](https://www.microsoft.com/pt-br/sql-server)

## Visão Geral

Este projeto demonstra a capacidade de realizar a **extração, transformação e análise de dados (ETL/E) de ponta a ponta**, com foco em Business Intelligence (BI) para as áreas de Vendas e Marketing. Os dados foram extraídos via consultas SQL e analisados em um dashboard de resultados no Microsoft Excel.

<img width="1491" height="779" alt="image" src="https://github.com/user-attachments/assets/82f8b820-abc0-4c54-a539-9bd807e1c7e5" />

---
## Resultados

<img width="1491" height="243" alt="image" src="https://github.com/user-attachments/assets/ff403d8d-4b8f-48c1-a533-d13473550c61" />

---
## Queries

<img width="1668" height="264" alt="image" src="https://github.com/user-attachments/assets/79e82f08-10d9-40e9-8415-5956476ca036" />

---

### O que foi avaliado?

A análise é uma visão multifacetada da performance do funil de vendas, focada em:

1.  **Funil de Vendas e Conversão:** Acompanhamento mensal de `Leads`, `Vendas` e o cálculo da `Taxa de Conversão`.
2.  **Performance Financeira:** Evolução da `Receita` e do `Ticket Médio` mês a mês.
3.  **Performance Geográfica e Operacional:** Vendas segmentadas pelos `Estados que mais venderam`, `Marcas que mais venderam` e performance individual de `Lojas`.
4.  **Comportamento do Usuário:** Mapeamento dos `Dias da semana com maior número de visitas ao site` para otimizar campanhas de marketing.

### Problema de Negócio Identificado

O principal problema resolvido é a **fragmentação de dados e a falta de *insights* operacionais**.

O dashboard permite a gestão a **correlacionar as métricas do topo do funil** (Leads/Visitas) **com as métricas do fundo** (Receita/Ticket Médio). Por exemplo, é possível identificar se os estados com alta receita também possuem alta conversão, ou se o baixo desempenho em um mês específico foi causado por queda no volume de leads ou na taxa de conversão.

### Métricas (KPIs) Importantes

| Métrica | Relevância |
| :--- | :--- |
| **Conversão (%)** | Indica a eficiência do processo de vendas (quantos leads viram clientes). |
| **Ticket Médio (R$)** | Métrica crucial de rentabilidade, que segmentada por mês/loja, revela tendências de preço e mix de produtos. |
| **Receita (R$) Mês a Mês** | Acompanhamento do crescimento e das metas de faturamento. |
| **Vendas por Estado/Marca/Loja** | Permite o foco de recursos e a replicação de estratégias de sucesso nas lojas de melhor desempenho. |

---

### Detalhes Técnicos

* **Ferramentas:** Microsoft Excel (Análise e Visualização) e SQL (Extração de Dados).
* **Base de Dados:** Dados tabulares de Vendas e Leads.
* **Habilidade SQL Destacada:** O projeto envolveu a extração da base de dados (que gerou o arquivo `Dashboard de vendas.xlsx - Resultados.csv`), demonstrando proficiência na criação de consultas complexas (JOINs, GROUP BY, Funções Agregadas) para consolidar KPIs para a análise final.

---

### Nota de Autoria

Os conhecimentos de extração de dados aplicados neste projeto foram adquiridos no curso **SQL para Análise de Dados: Do básico ao avançado (Udemy)**. O dashboard foi desenvolvido como prática e material de portfólio para demonstrar as habilidades de Data Analytics.
