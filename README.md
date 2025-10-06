
# Dashboard de Vendas com Python e SQLite

Este projeto é um exemplo completo de pipeline de análise de vendas utilizando Python, SQLite e visualizações gráficas.

---

## Estrutura do Projeto

- `dados/vendas.csv` → arquivo CSV gerado com dados fictícios de vendas
- `database/vendas.db` → banco de dados SQLite contendo os dados de vendas
- `main.py` → script principal que gera dados, salva no banco e cria gráficos

---

## Funcionalidades

1. Geração de dados de vendas fictícios
2. Armazenamento dos dados em SQLite
3. Consulta de vendas por região
4. Visualizações:
   - Vendas por produto (gráfico de barras horizontal)
   - Faturamento mensal (gráfico de linha)

---

## Requisitos

- Python 3.10+
- Bibliotecas:
  ```bash
  pip install pandas numpy matplotlib
