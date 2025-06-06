# Automação de Extração e Envio de Dados do ServiceNow para Databricks

## Sobre o Projeto

Script em Python que automatiza:
- Login no portal ServiceNow
- Exportação de dados em CSV
- Limpeza e tratamento dos dados
- Upload do arquivo para o DBFS do Databricks
- Remoção do arquivo local

### Principais Tecnologias
- Python (Selenium, Pandas, dotenv)
- ServiceNow
- Databricks

## Como Usar

1. Clone este repositório
2. Instale as dependências (`pip install -r requirements.txt`)
3. Crie um arquivo `.env` com suas credenciais (ver `.env.example`)
4. Execute o script `python automacao_servicenow.py`

## Observações

> Este código é um exemplo e **NÃO** contém informações sensíveis.  
Para uso corporativo, configure as variáveis de ambiente conforme o modelo.
