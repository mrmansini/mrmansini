# Olá, eu sou o Felipe 👋

Construo o caminho que o dado percorre até virar decisão — **da API até o dashboard.**

Sou Analista de Dados formado em Economia. Não paro na query: entendo o número, o processo que gerou ele e o impacto dele no negócio.

## O que eu faço

- 🔌 **Ingestão** — integrações via API REST (CRM, plataformas web, planilhas), tratando token, paginação, falha e reprocessamento.
- 🗄️ **Armazenamento** — modelagem e manutenção de bases PostgreSQL como fonte única da verdade.
- ⚙️ **Automação** — pipelines em n8n e Python que substituem processo manual.
- 📊 **Visualização** — dashboards em Power BI com KPIs definidos junto às áreas de negócio.

## Alguns números

*Como Analista de Dados, desde jan/2025:*

- ⏱️ **30+ processos manuais automatizados** com n8n e Python — cerca de 80h/mês devolvidas ao time
- 📈 **10+ dashboards estratégicos** em Power BI (operações, SLA de suporte, funil comercial)

*Formação:*

- 🥇 1º lugar da turma de Ciências Econômicas na UEL (Honra ao Mérito)

## Stack

`Python` `SQL` `PostgreSQL` `Power BI (DAX / Power Query)` `n8n` `APIs REST` `Azure (AZ-900)` `Excel avançado`

## Projetos em destaque

### 📊 [pipeline-indicadores-bcb](https://github.com/mrmansini/pipeline-indicadores-bcb)

Pipeline que coleta indicadores econômicos do Banco Central (Selic, IPCA, câmbio, IBC-Br) e entrega em dashboard, rodando sozinho todo dia.

Carga incremental idempotente em PostgreSQL, seis validações de qualidade que reprovam a execução quando o dado não confere, e execução diária automatizada via GitHub Actions. A camada analítica alimenta Power BI e Looker Studio sem transformação intermediária.

O README documenta o que a API do SGS não conta na documentação — inclusive o fato de ela responder HTTP 200 com página de erro em HTML.

**[Ver dashboard ao vivo →](https://lookerstudio.google.com/reporting/387b4bf3-1c9c-4a06-9dc5-3f596da96aae)**

`Python` `PostgreSQL` `GitHub Actions` `Power BI` `Looker Studio`

---

**Em construção:**

- 🔜 `automacao-n8n-...` — automação replicável exportada em JSON
- 🔜 `sql-modelagem-...` — schema PostgreSQL + queries analíticas
- 🔜 `dashboard-powerbi-...` — relatório publicado na web

## Um pouco de contexto

Antes de dados, passei por perícia judicial econômico-financeira, contabilidade e tesouraria — é de onde vem meu incômodo com número que não bate. Isso entrou no jeito como construo pipeline: audito o cálculo antes de confiar nele.

## Contato

📧 felipemansini@hotmail.com · 💼 [LinkedIn](https://linkedin.com/in/felipemansini) · 📍 Rolândia, PR
