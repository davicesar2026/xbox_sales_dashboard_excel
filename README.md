# 🎮 Xbox Game Pass Subscriptions Sales — Dashboard Excel

Projeto desenvolvido como parte do desafio da DIO no módulo de Análise de Dados com Excel e Copilot. O objetivo é desenvolver um dashboard analítico de vendas do Xbox Game Pass, aplicando conceitos de organização de dados, Tabelas Dinâmicas, gráficos e segmentações no Microsoft Excel, com apoio do **Microsoft Copilot** como ferramenta de IA.

---

## 📋 Descrição do Projeto

O arquivo `xbox_sales_dashboard.xlsx` representa um painel analítico de vendas de assinaturas do **Xbox Game Pass**, desenvolvido com identidade visual baseada na paleta oficial do Xbox.

O dashboard permite acompanhar o desempenho comercial das assinaturas, analisando faturamento por tipo de plano, periodicidade, comportamento de renovação e impacto dos add-ons contratados — oferecendo uma visão gerencial clara e objetiva sobre a base de assinantes.

---

## 📊 O Dashboard

O painel **Xbox Game Pass Subscriptions Sales** consome dados tratados por Tabelas Dinâmicas na aba `Cálculos`, derivados da base estruturada na aba `Bases`.

Ele consolida informações de **295 assinantes** e apresenta análises como:

- Faturamento por tipo de plano — **Core**, **Standard** e **Ultimate**
- Distribuição por periodicidade — **Mensal**, **Trimestral** e **Anual**
- Comparativo entre renovações **automáticas** e **manuais**
- Impacto dos add-ons **EA Play Season Pass** e **Minecraft Season Pass** na receita
- Análise de descontos aplicados via cupom

A identidade visual segue a paleta oficial do Xbox, com tons de verde sobre fundo escuro.

---

## 🗂️ Estrutura do Arquivo

| Aba | Descrição |
|---|---|
| `Assets` | Paleta de cores oficial do Xbox utilizada no dashboard |
| `Bases` | Base de dados com 295 assinantes e suas informações de plano |
| `Cálculos` | Tabelas Dinâmicas com as respostas às perguntas do projeto |
| `Dashboard` | Painel visual final com gráficos, KPIs e segmentações |

---

## ⚙️ Como Visualizar

### Pré-requisitos

- Microsoft Excel 2016 ou superior (Desktop recomendado)

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/davicesar2026/xbox_sales_dashboard_excel.git

# 2. Abra o arquivo
xbox_sales_dashboard.xlsx

# 3. Acesse a aba Dashboard para visualizar o painel completo
```

> Ou abra diretamente pelo Excel em **Arquivo > Abrir**.

> ⚠️ Algumas funcionalidades visuais podem não ser exibidas corretamente no Excel Online.

---

## 🔍 Análises Implementadas

As visualizações foram construídas para responder perguntas de negócio reais sobre a base de assinantes:

| # | Pergunta | Recurso utilizado |
|---|---|---|
| 1 | Qual o faturamento de planos anuais por tipo de renovação? | Tabela Dinâmica, segmentação |
| 2 | Qual o plano mais vendido? | Agregação, gráfico de barras |
| 3 | Como se distribuem as assinaturas por periodicidade? | Gráfico de pizza |
| 4 | Qual o impacto dos add-ons no faturamento total? | Campo calculado, agregação |
| 5 | Qual a proporção entre renovação automática e manual? | Tabela Dinâmica, segmentação |

---

## 📦 Dados da Base

A base de dados contempla um cenário realista de assinaturas:

- **295 assinantes** com dados individuais de plano e contrato
- **3 tipos de plano** — Core, Standard e Ultimate
- **3 periodicidades** — Mensal (139), Trimestral (85) e Anual (71)
- **Add-ons opcionais** — EA Play Season Pass e Minecraft Season Pass
- **Cupons de desconto** aplicados por assinante

---

## 🛠️ Tecnologias Utilizadas

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)
![Copilot](https://img.shields.io/badge/Microsoft%20Copilot-0078D4?logo=microsoft&logoColor=white)

---

## 👨‍💻 Autor

Davi César Campos de Oliveira

[![GitHub](https://img.shields.io/badge/GitHub-davicesar2026-181717?logo=github)](https://github.com/davicesar2026)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-davicesar--ti-0A66C2?logo=linkedin)](https://www.linkedin.com/in/davicesar-ti)
