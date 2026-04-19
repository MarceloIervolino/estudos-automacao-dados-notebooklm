# 📑 Masterguide: Gestão de Automação e Análise de Dados de Alta Performance

## 🎯 Contexto e Objetivos
Este repositório foi desenvolvido como o projeto final para o desafio da **DIO**, explorando o uso da Inteligência Artificial como ferramenta de aprendizagem ativa através do **NotebookLM** da Google.

O objetivo central é consolidar um guia técnico que une dois pilares fundamentais da tecnologia moderna:
1.  **Gestão de Automação (Orquestração):** Integração de sistemas e pipelines de dados com **Power Automate, N8N e Make (Integromat)**.
2.  **Análise de Dados (Business Intelligence):** Otimização e governança de modelos no **Power BI** utilizando ferramentas avançadas como **Tabular Editor** e **Measure Killer**.

---

## 📚 Curadoria de Fontes
Para alimentar a base de conhecimento do NotebookLM, utilizei as seguintes fontes técnicas oficiais:

* **Automação:** Documentações do Make (manipulação de JSON), N8N (Function Nodes) e conectores do Power Automate.
* **BI & Performance:** Manuais do Tabular Editor (DAX Scripting), Measure Killer (limpeza de modelos) e Best Practice Analyzer (BPA).
* **Metodologia:** Documentação sobre automação Low-Code e Engenharia de Prompts aplicada.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Documentação do processo de refinamento das consultas para extrair o máximo de maturidade técnica da IA.

| Fase | Estratégia de Prompt | Resultado Obtido | "Cicatriz" (Dificuldade/Ajuste) |
| :--- | :--- | :--- | :--- |
| **Básica** | "Como automatizar o Power BI?" | Respostas genéricas sobre agendamento simples. | A IA não sugeriu ferramentas externas sem ser provocada. |
| **Técnica** | "Como usar o N8N para disparar Webhooks que atualizam o Power BI?" | Instruções sobre métodos POST e autenticação API. | Necessidade de detalhar o tratamento de erros em JSON complexos. |
| **Sênior** | "Atue como Arquiteto de Dados. Crie um script C# para Tabular Editor que valide regras de performance." | Código funcional para automação de medidas DAX. | Ajuste manual na sintaxe que a IA por vezes confundia entre versões. |

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **Pipeline End-to-End:** A automação (N8N/Make) é a "cola" que conecta sistemas. A análise (Power BI) é a vitrine. Sem uma gestão de automação eficiente, os dados chegam sujos ou atrasados.
* **Governança:** Ferramentas como o **Measure Killer** são vitais para manter a saúde do modelo, removendo o que a automação trouxe mas a análise não utilizou.

### 2. Glossário de Conceitos Chave
* **Webhooks:** Gatilhos em tempo real para automações instantâneas.
* **DAX Scripting:** Automação da criação de cálculos em massa no Power BI.
* **Nodes & Iterators:** Estruturas de lógica fundamentais no N8N e Make para processar listas de dados.
* **BPA (Best Practice Analyzer):** Auditoria automática de performance em modelos de dados.

### 3. Prompts Reutilizáveis (Toolbox)
* *"Analise este log de erro do N8N e sugira uma rota de contingência para falha de API."*
* *"Com base no manual do Tabular Editor, gere um script para criar medidas de Year-to-Date (YTD) automaticamente."*
* *"Compare o custo de execução de um fluxo entre Power Automate e Make para 10.000 requisições."*

---

## 🛠️ Tecnologias Utilizadas
* [NotebookLM](https://notebooklm.google.com/) (Curadoria e Sintetização)
* Power BI, Tabular Editor, Measure Killer
* Power Automate, N8N, Make.com

---
✨ *Projeto desenvolvido para o portfólio da Digital Innovation One (DIO)*
