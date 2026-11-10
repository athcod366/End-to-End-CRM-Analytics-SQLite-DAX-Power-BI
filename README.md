# 📊 CRM Sales & Marketing Analytics (End-to-End)

Pipeline completo de análise comercial e marketing B2B, integrando automação de captura de leads em tempo real, modelagem de dados relacional e um dashboard executivo interativo.

---

## Tecnologias Utilizadas

* **Automação:** n8n (Webhook & Google Sheets API)
* **Base de Dados:** SQLite (Modelagem relacional e VIEWs analíticas)
* **Business Intelligence:** Power BI (Medidas DAX & Tema Escuro)
* **Versionamento:** Git & GitHub

---

## Estrutura do Repositório

```text
Dashboard_crm_comercial/
├── automacoes/       # Fluxo de captura exportado (.json)
├── Dashboard/        # Relatório executivo do Power BI (.pbix)
├── images/           # Prints da arquitetura e visões do painel
├── Sql/              # Scripts de criação e população da base (.db / .sql)
└── README.md         # Documentação principal
```
## Visão Geral do Projeto
1. Visão Executiva / Diretoria
2. Visão de Marketing & Funil de Leads
3. Modelagem de Dados Relacional
4. Fluxo de Automação no n8n

⚡ Como Replicar o Projeto

    Automação: Importe o ficheiro JSON da pasta automacoes/ para o seu n8n.

    Base de Dados: Execute os scripts da pasta Sql/ para gerar o banco SQLite.

    Dashboard: Abra o ficheiro .pbix na pasta Dashboard/ utilizando o Power BI Desktop.
  
