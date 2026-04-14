# Sales Analytics Dashboard

Projeto desenvolvido para a disciplina **Software Product: Analysis, Specification, Project & Implementation**.

Este projeto apresenta um dashboard analítico desenvolvido em **Power BI**, com foco em análise exploratória e análise temporal de dados de vendas.

---

## Objetivo

Desenvolver um dashboard interativo capaz de:

- Identificar padrões de vendas  
- Analisar desempenho comercial  
- Avaliar crescimento ao longo do tempo  
- Apoiar a tomada de decisão baseada em dados  

---

## Tecnologias Utilizadas

- Power BI  
- Power Query  
- DAX  
- Modelagem de Dados (Modelo Estrela)  
- Tabela Calendário (Time Intelligence)  

---

## Dashboards

### 🔹 Página 1 – Visão Geral (AC1)

![Dashboard](docs/dashboard.png)

Permite uma análise geral do desempenho comercial.

---

### 🔹 Página 2 – Análise Temporal (AC2)

![Dashboard Temporal](docs/dashboard_temporal.png)

Nova página com foco em evolução temporal das vendas.

---

## Principais Métricas

- Receita Total  
- Total de Produtos Vendidos  
- Ticket Médio  
- Percentual de Devoluções  
- Crescimento Mensal (%)  
- Crescimento Anual (%)  

---

## Análises Desenvolvidas

### 📊 AC1 – Análise Exploratória

- Top 10 produtos por faturamento  
- Participação das categorias  
- Quantidade vendida por produto  
- Ranking de marcas  

---

### 📈 AC2 – Análise Temporal

- Receita ao longo do tempo  
- Volume de vendas ao longo do tempo  
- Comparação Ano a Ano (YoY)  
- Crescimento mensal (%)  
- Crescimento anual (%)  

---

## Interatividade

O dashboard permite análises dinâmicas através de:

- Filtros por Categoria  
- Filtros por Marca  
- Navegação entre páginas (botões)  
- Interação entre visuais  

---

## Modelagem de Dados

- Modelo estrela (Star Schema)  
- Criação de Tabela Calendário  
- Relacionamento 1:N entre calendário e vendas  
- Padronização da coluna de data para garantir integridade no relacionamento  
- Uso de funções DAX de Time Intelligence:
  - SAMEPERIODLASTYEAR  
  - DATEADD  
  - CALCULATE  

---

## Estrutura do Projeto
Sales-Analytics-Dashboard
│
├── dashboard
│ └── Sales_Analytics_Dashboard.pbix
│
├── dataset
│ ├── Base Vendas - 2022.xlsx
│ ├── Base Vendas - 2023.xlsx
│ ├── Base Vendas - 2024.xlsx
│ ├── Cadastro Clientes.xlsx
│ ├── Cadastro Lojas.xlsx
│ └── Cadastro Produto.xlsx
│
└── docs
├── dashboard.png
├── dashboard_temporal.png
├── AC1_Relatorio.pdf
└── AC2_Relatorio.pdf


---

## Download do Dashboard

[Download do arquivo .PBIX](dashboard/Sales_Analytics_Dashboard.pbix)

---

## Documentação

- [AC1 - Relatório](docs/AC1_Relatorio.pdf)  
- [AC2 - Relatório](docs/AC2_Relatorio.pdf)  

---

## Autor

**Thales de Sousa Sampaio**

Projeto acadêmico desenvolvido para a disciplina **Software Product: Analysis, Specification, Project & Implementation**.
