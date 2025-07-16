# 📧 Automação de Relatório por E-mail

Projeto de automação em Python para **geração e envio de relatórios de vendas via Outlook**. O script processa dados de vendas, cria um relatório formatado e envia automaticamente por e-mail com o anexo, ideal para rotinas corporativas.

---

## ⚙️ Funcionalidades

- 📊 Leitura de dados a partir de arquivos Excel (.xlsx)
- 📑 Criação automática de relatório de vendas em anexo
- ✉️ Envio automático por e-mail usando integração com Outlook (via `win32com`)
- 🔁 Automatização completa de tarefas operacionais repetitivas

---

## 🧰 Tecnologias Utilizadas

- Python 3.x
- `pandas`
- `openpyxl`
- `win32com.client` (integração com Outlook)

---

## 📂 Estrutura do Projeto

```bash
📁 relatorio-email/
├── Relatorio de Vendas.xlsx         # Base de dados de vendas
├── relatorio_email.py               # Script principal de automação
└── README.md                        # Documentação do projeto
