# Projeto Telecom X - Análise de Churn (Evasão de Clientes)

## Descrição

Este projeto tem como objetivo analisar o índice de evasão de clientes (churn) da empresa Telecom X, uma operadora de telecomunicações. Utilizando técnicas de ciência de dados e o processo de ETL (Extração, Transformação e Carga), a análise busca identificar padrões e fatores que influenciam a saída dos clientes, auxiliando na criação de modelos preditivos para redução da evasão.

---

## Estrutura do Projeto

- `TelecomX_Data.json` : Arquivo JSON com os dados brutos extraídos da API.
- `notebook.ipynb` : Notebook Jupyter com todo o processo de ETL, análise exploratória e visualização dos dados.
- `README.md` : Documentação do projeto explicando o propósito, estrutura e como executar a análise.
- `requirements.txt` : Lista de dependências Python necessárias para rodar o notebook.

---

## Exemplos de Gráficos e Insights

- **Churn por Tipo de Contrato:** Identificação dos tipos de contrato que possuem maior taxa de evasão.
- **Correlação entre Variáveis Numéricas:** Avaliação das relações entre custos mensais, tempo de contrato e churn.
- **Análise Exploratória por Serviços Contratados:** Verificação dos serviços que impactam na retenção dos clientes.

![Exemplo de Gráfico](exemplo_grafico.png)  <!-- se você gerar e salvar uma imagem, pode linkar aqui -->

---

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/telecom-x.git
   cd telecom-x
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
jupyter notebook notebook.ipynb
