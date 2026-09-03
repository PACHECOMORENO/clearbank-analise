# Análise Financeira com Python (ClearBank)

**Autor:** Ignacio Sebastian Pacheco Moreno

Projeto final do módulo de fundamentos em Python. O objetivo foi ler um CSV de transações bancárias, tratar os dados com problemas (campos vazios, valores e datas inválidas) e gerar um relatório financeiro mensal.

## O que o notebook faz

- Lê o `transacoes.csv` e descarta as linhas inválidas sem parar a execução.
- Converte as datas com `datetime` e calcula o período coberto pelos dados.
- Agrupa as transações por mês e calcula total de crédito, débito, saldo, média, maior e menor valor.
- Marca como suspeitas as transações acima de R$ 10.000,00.
- Salva o resultado em `relatorio.json` e gera um gráfico com `matplotlib`.

## Como executar

1. Baixe este repositório.
2. Abra o `desafio-final.ipynb` no Google Colab ou no Jupyter local.
3. Rode as células em ordem, de cima para baixo.
4. A primeira célula já cria o `transacoes.csv` de teste automaticamente.

## Saídas geradas

- `relatorio.json`: resumo financeiro mensal.
- `grafico.png`: gráfico de barras empilhadas com crédito e débito por mês (feito com Pandas).
