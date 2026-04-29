# 📊 Tech Challenge – Análise de Dados em E-commerce

## 📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma análise completa de um e-commerce, explorando diferentes dimensões do negócio como **faturamento, comportamento de clientes, logística e satisfação**.

A análise foi desenvolvida a partir do dataset público da Olist, passando por etapas de **tratamento de dados, modelagem analítica e construção de dashboards interativos** no Power BI.

---

## 🎯 Objetivos do Projeto

* Analisar o desempenho geral do e-commerce
* Identificar padrões de receita e crescimento ao longo do tempo
* Avaliar o impacto da logística na experiência do cliente
* Entender o comportamento de compra por categoria, região e forma de pagamento
* Gerar insights acionáveis para melhoria do negócio

---

## 🛠️ Tecnologias Utilizadas

* **Python (Pandas)** → Tratamento e transformação de dados
* **Power BI** → Construção do dashboard e visualização
* **Excel** → Apoio na validação de métricas e estrutura analítica

---

## 🧹 Tratamento e Preparação dos Dados

A base de dados original apresentava inconsistências, valores nulos e necessidade de padronização.

As principais etapas realizadas foram:

* Tratamento de valores nulos em colunas críticas
* Conversão de datas para formato `datetime`
* Criação da métrica `delivery_days` (tempo de entrega)
* Criação da variável `is_late` para identificação de atrasos
* Construção de tabelas analíticas para otimizar a análise:

### Tabelas criadas:

* `Order_Level` → Base detalhada por pedido
* `Monthly_KPIs` → Indicadores mensais
* `State_KPIs` → Indicadores por estado
* `Category_KPIs` → Indicadores por categoria
* `Payment_KPIs` → Análise por forma de pagamento

Essas estruturas permitiram melhorar a performance do dashboard e facilitar a leitura dos dados.

---

## 📊 Dashboard

O dashboard foi construído no Power BI com foco em **análise exploratória e storytelling de negócio**.

### Principais indicadores:

* 📦 **Total de pedidos:** ~96.478
* 💰 **GMV (Receita total):** ~R$ 15,42 milhões
* 💳 **Ticket médio:** ~R$ 159,86
* ⭐ **Nota média dos clientes:** ~4,1
* 🚚 **Prazo médio de entrega:** ~12 dias
* ⚠️ **Taxa de atraso:** ~6,8%

---

## 📈 Principais Análises Realizadas

### 📅 Crescimento do Negócio

* Evolução da receita ao longo do tempo
* Volume de pedidos por mês
* Variação do ticket médio

---

### 🌎 Análise Geográfica

* Distribuição de receita por estado
* Diferenças regionais de desempenho
* Identificação de regiões com maior atraso logístico

---

### 🛒 Análise por Categoria

* Categorias com maior faturamento
* Categorias com melhor e pior avaliação
* Relação entre tipo de produto e experiência do cliente

---

### 💳 Análise de Pagamentos

* Distribuição de receita por tipo de pagamento
* Número de parcelas médias
* Participação de cada método no faturamento

---

### ⭐ Satisfação do Cliente

* Distribuição das avaliações (review score)
* Impacto do prazo de entrega na satisfação
* Diferença de avaliação entre pedidos no prazo e atrasados

---

## 🧠 Principais Insights

* A **logística é um dos principais fatores que impactam a satisfação do cliente**
* Pedidos com maior tempo de entrega tendem a receber avaliações mais baixas
* Mesmo com uma taxa de atraso relativamente baixa (**6,8%**), o impacto na experiência é significativo
* Existe variação relevante de desempenho entre estados e categorias
* O crescimento do faturamento acompanha o aumento no volume de pedidos

---

## 🚀 Recomendações de Negócio

* Reduzir o prazo médio de entrega
* Diminuir a taxa de atrasos
* Otimizar operações logísticas em regiões críticas
* Monitorar categorias com menor satisfação
* Incentivar métodos de pagamento mais eficientes

---

## 📂 Estrutura do Projeto

```
📁 tech-challenge
│
├── 📄 data/raw
        ├── processed
├── 📄 tech_challenge_olist_dashboard.xlsx
├── 📊 tech_challenge_final.pbix
├── 📊 tech_challenge_olist.ipynb
└── 📄 README.md
```

---

## 📌 Conclusão

Este projeto demonstra como a análise de dados pode gerar valor estratégico para o negócio, permitindo identificar problemas operacionais, entender o comportamento do cliente e orientar decisões baseadas em dados.

A combinação de tratamento de dados com visualização permitiu transformar dados brutos em insights relevantes para melhoria contínua do e-commerce.

---
