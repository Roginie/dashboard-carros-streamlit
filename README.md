# Dashboard de Carros (Streamlit)

Dashboard interativo de análise de vendas de carros construído com **Streamlit** e **Plotly**, consumindo dados de um banco **MySQL**. Permite filtrar por marca, modelo, ano, valor, cor e número de vendas, exibindo métricas e diversos gráficos.

## Tecnologias
- Python 3
- Streamlit • Plotly • Pandas
- MySQL (via `mysql-connector-python`)

## Estrutura
| Arquivo | Descrição |
|---------|-----------|
| `dash.py` | Aplicação Streamlit (filtros, métricas e gráficos) |
| `query.py` | Conexão e consulta ao banco de dados MySQL |

## Recursos
- Filtros laterais dinâmicos
- Métricas (total, média e mediana de vendas)
- Gráficos de barras, linhas, pizza, dispersão, barras horizontais e área
- Barra de progresso de meta de vendas

## Como executar
```bash
pip install -r requirements.txt
streamlit run dash.py
```
> Ajuste as credenciais do banco em `query.py` (host, usuário, senha e database) antes de executar.
