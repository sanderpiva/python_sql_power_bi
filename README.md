# 📊 Pipeline de Dados: Da Extração ao Insight (SQL + Python + Power BI)

## 📌 Visão Geral
Este projeto consiste em um pipeline completo de dados para análise de performance de vendas globais. O objetivo foi extrair dados de um banco SQLite, processá-los via Python para garantir a integridade das métricas e criar um dashboard interativo no Power BI para suporte à decisão gerencial.

## 🛠 Tecnologias Utilizadas
- **Banco de Dados:** SQLite (Extração de dados transacionais).
- **Linguagem:** Python (Pandas) para processamento e exportação.
- **SQL:** Joins complexos, agregações e filtros de regras de negócio.
- **BI:** Power BI (Data Visualization e modelagem de métricas agregadas).

## 📊 Arquitetura do Projeto
1. **Extração:** Query SQL performante unindo tabelas de Clientes, Vendas, Pedidos e Produtos.
2. **Processamento:** Tratamento via Pandas para arredondamento de valores financeiros e organização de prioridades.
3. **Visualização:** Dashboard focado em 3 pilares: Faturamento, Volume de Pedidos e Custos de Envio.

## 🚀 Como Executar
1. Clone o repositório.
2. Abra o arquivo `.ipynb` no Jupyter Notebook ou Google Colab para ver o processamento.
3. O arquivo `relatorio_vendas_final.csv` é a saída gerada para alimentar o dashboard.
4. Abra o arquivo `.pbix` no Power BI Desktop para interagir com os visuais.

## 📈 Insights do Dashboard
- **Evolução Temporal:** Identificação de crescimento constante no faturamento entre 2011 e 2014.
- **Mix de Categorias:** Análise da dominância da categoria "Material de Escritório" no volume de pedidos.
- **Mix de Tecnologia:** Análise da dominância da categoria "Tecnologia" no volume de faturamento.
- **Mix de Produto:** Embora "Material de Escritório" gere o maior volume de pedidos, a categoria de Tecnologia é a principal responsável pelo faturamento (Geração de Valor), sugerindo diferentes estratégias de marketing para cada segmento.
- **Logística:** Comparativo de custos de envio por prioridade de entrega, auxiliando na otimização de fretes.

## ⚖️ Conformidade e Ética
O projeto foi desenvolvido seguindo boas práticas de manipulação de dados, garantindo que as métricas de faturamento e custos reflitam a realidade transacional do banco de dados de origem.
O **banco de dados** é **ficticio**, obtido do curso **Data Science Academy** - Microsoft Power BI Para Business Intelligence e Data Science.

---
## 📸 Foto do dashboard: Relatório Vendas

<img width="887" height="493" alt="relatorio_vendas" src="https://github.com/user-attachments/assets/af209091-a985-452e-afeb-3eae95991f4f" />

---
Desenvolvido por **Sander Gustavo Piva**
