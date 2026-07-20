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
  <img width="1441" height="800" alt="image" src="https://github.com/user-attachments/assets/e8b9ec53-6745-486f-8a88-a3969415b9e5" />
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
<img width="1448" height="799" alt="image" src="https://github.com/user-attachments/assets/613fc540-aa91-4885-adb3-19244ca6a68d" />
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
<img width="1433" height="795" alt="image" src="https://github.com/user-attachments/assets/42ea7248-4265-489e-a5c8-d04cb3f8857d" />
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
<img width="1439" height="799" alt="image" src="https://github.com/user-attachments/assets/d9e31794-d042-4373-a976-7c950c10f536" />
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
<img width="1439" height="804" alt="image" src="https://github.com/user-attachments/assets/12a13257-3f83-4fef-b25a-ae640f6dfd0f" />
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
