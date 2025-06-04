# Previsão de Compra Repetida

Este projeto simula um cenário de e-commerce com o objetivo de prever se um cliente realizará uma nova compra nos próximos **30 dias** com base em dados históricos de comportamento de compra.

## Objetivo

Classificar os clientes como:
- `Sim`: se é provável que comprem novamente nos próximos 30 dias.
- `Não`: caso contrário.

## Estrutura do Projeto

1. **Geração de Dados Sintéticos (CSV)**
2. **Análise e Visualização com Pandas + Seaborn**
3. *(Opcional)* Leitura com PySpark
4. **Pronto para ser usado em modelos de machine learning (não incluídos neste notebook)**

## Features Utilizadas

- Frequência de compras
- Valor total gasto
- Categoria mais comprada
- Dias desde a última compra
- Compra repetida em 30 dias (target)

## Visualizações

Gráficos incluídos no notebook:
- Distribuição da frequência de compras
- Comparação do valor gasto entre clientes que voltam ou não
- Dias desde a última compra

## Tecnologias

- Python
- Pandas
- Seaborn
- Matplotlib
- *(Opcional)* PySpark

## Como Executar

1. Clone este repositório ou envie os arquivos para seu próprio repositório:
   ```bash
   git clone https://github.com/seu-usuario/previsao-compra-repetida.git
