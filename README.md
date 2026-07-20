# 📊 Análise de Vendas com Power BI

## Sobre o projeto

Este projeto consiste em um dashboard desenvolvido no **Power BI** com o objetivo de analisar o desempenho comercial de uma empresa através de indicadores de **vendas, clientes, produtos e avaliações (reviews)**.

O dashboard foi construído seguindo uma abordagem de **Business Intelligence**, transformando dados brutos em informações estratégicas para apoiar a tomada de decisão.

---

# 🎯 Objetivos do projeto

O dashboard busca responder perguntas de negócio como:

* Qual é o faturamento total e sua evolução ao longo do tempo?
* Quais produtos e categorias geram maior receita?
* Quem são os clientes mais valiosos para o negócio?
* Quais regiões apresentam melhor desempenho comercial?
* Como os clientes avaliam os produtos vendidos?
* Quais fornecedores possuem melhor performance?

---

# 🛠️ Tecnologias utilizadas

* **Power BI Desktop**
* **Power Query (ETL e transformação de dados)**
* **DAX (Data Analysis Expressions)**
* **Modelagem dimensional**
* **GitHub para versionamento**

---

# 📂 Fonte dos dados

Os dados utilizados no projeto estão disponíveis neste arquivo:

Dataset utilizado: https://github.com/BPAULILL/analise-vendas-pbi/tree/main/Dados

Dicionário (Colunas): https://github.com/BPAULILL/analise-vendas-pbi/blob/main/Colunas.xlsx

O conjunto de dados contém informações relacionadas a:

* Pedidos
* Clientes
* Produtos
* Categorias
* Fornecedores
* Localização
* Reviews dos produtos

---

# 🏗️ Modelagem de dados

Foi criada uma estrutura de dados organizada para facilitar análises e criação de métricas no Power BI.

Modelo utilizado:

<p align="center">
<img width="791" height="602" alt="image" src="https://github.com/user-attachments/assets/57168e72-3109-4b20-a1c1-3da008ad66b7" />
</p>

A modelagem permite análises por diferentes perspectivas:

* Tempo
* Cliente
* Produto
* Categoria
* Fornecedor
* Localização

---

# 📈 Dashboard

## Página 1 — Visão Geral (Executivo)

### Objetivo:

Apresentar uma visão rápida da saúde do negócio.

Principais indicadores:

* 💰 Faturamento total
* 🛒 Número de pedidos
* 🎫 Ticket médio
* 👥 Clientes ativos
* 📈 Evolução das vendas por mês
* 🏆 Top 5 produtos por receita
* 📦 Faturamento por categoria
* 🌎 Top 5 estados por faturamento

<p align="center">
<img width="662" height="364" alt="Visão Geral" src="https://github.com/user-attachments/assets/f3b56f8c-153e-417f-af3c-76e957691bcc" />
</p>

---

# 👥 Página 2 — Clientes (People)

### Objetivo:

Entender o comportamento, perfil e valor dos clientes.

Análises realizadas:

* Total de clientes
* Idade média
* LTV médio (Lifetime Value)
* Recência média de compra
* Distribuição por faixa etária
* Clientes por estado
* Origem dos clientes (Source)
* Top 10 clientes por LTV

<p align="center">
<img width="665" height="372" alt="Clientes" src="https://github.com/user-attachments/assets/b1fbb294-bdf0-401c-83a5-4ca6d1881880" />
</p>

---

# 🛒 Página 3 — Vendas (Pedidos)

### Objetivo:

Avaliar a performance comercial e identificar padrões de venda.

Análises realizadas:

* Total de pedidos
* Quantidade total de itens vendidos
* Desconto médio aplicado
* Impostos médios
* Evolução das vendas por período
* Vendas por categoria
* Vendas por fornecedor
* Ticket médio por estado

<p align="center">
<img width="668" height="365" alt="Vendas" src="https://github.com/user-attachments/assets/014215d6-b5ec-426d-a7df-18a8cba7b560" />
</p>

---

# 📦 Página 4 — Produtos (Products)

### Objetivo:

Analisar o desempenho do portfólio de produtos.

Análises realizadas:

* Quantidade total de produtos
* Preço médio
* Nota média dos produtos
* Produtos por categoria
* Produtos por fornecedor
* Relação entre preço e quantidade vendida
* Cadastro de produtos ao longo do tempo

<p align="center">
<img width="668" height="360" alt="Produtos" src="https://github.com/user-attachments/assets/f86137e1-8d7d-4b8c-b23c-82cf0fc6c99c" />
</p>

---

# ⭐ Página 5 — Reviews

### Objetivo:

Avaliar a percepção dos clientes sobre os produtos.

Análises realizadas:

* Total de avaliações
* Nota média geral
* Distribuição das notas (1 a 5)
* Evolução dos reviews ao longo do tempo
* Nota média por categoria
* Nota média por fornecedor

<p align="center">
<img width="664" height="368" alt="Reviews" src="https://github.com/user-attachments/assets/6b3cbb78-6c42-4f6b-bcee-c8d480fc8492" />
</p>

---

# 🔎 Principais análises possíveis

Com este dashboard é possível identificar:

* Produtos responsáveis pela maior geração de receita
* Categorias com melhor desempenho
* Clientes com maior valor financeiro
* Estados com maior participação nas vendas
* Relação entre preço, volume vendido e avaliação
* Oportunidades de melhoria através dos reviews

---

# 🚀 Aprendizados aplicados

Durante o desenvolvimento do projeto foram aplicados conceitos de:

* Tratamento e transformação de dados
* Construção de modelo analítico
* Criação de indicadores de negócio
* Desenvolvimento de medidas DAX
* Storytelling com dados
* Construção de dashboards executivos

---

## Autor

**BPAULILL**

Projeto desenvolvido para prática e demonstração de habilidades em **Power BI, Dados e Business Intelligence**.
