<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Projeto de Backtesting com Bandas de Bollinger

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GeorgeTelles/backtest_bollinger_bands/blob/main/Backtesting_Bandas_de_Bollinger.ipynb)

## Descrição

Este projeto tem como objetivo desenvolver um algoritmo em Python para realizar backtesting de ativos financeiros utilizando as Bandas de Bollinger. O backtesting é uma técnica essencial para avaliar a eficácia de estratégias de investimento, permitindo que os investidores testem suas abordagens com dados históricos antes de aplicá-las em tempo real.

## O que são Bandas de Bollinger?

As Bandas de Bollinger são uma ferramenta de análise técnica criada por John Bollinger. Elas consistem em uma banda superior, uma banda inferior e uma média móvel simples (SMA) que forma a banda central. As bandas são ajustadas com base na volatilidade do preço do ativo, e a sua distância da média móvel é calculada usando o desvio padrão. As Bandas de Bollinger ajudam a identificar períodos de alta ou baixa volatilidade e possíveis sinais de compra ou venda.

## Funcionalidades do Projeto

- **Coleta de Dados**: Importar dados históricos de preços de ativos financeiros (ações, moedas, etc.) a partir de fontes como APIs financeiras ou arquivos CSV.
- **Cálculo das Bandas de Bollinger**: Implementar o cálculo das bandas superior, inferior e da média móvel.
- **Simulação de Estratégias**: Testar diferentes estratégias de negociação baseadas nas Bandas de Bollinger, como a estratégia de rompimento ou reversão à média.
- **Avaliação de Desempenho**: Medir o desempenho das estratégias usando métricas como retorno total, drawdown, e outras métricas financeiras relevantes.
- **Visualização**: Gerar gráficos para visualizar os preços dos ativos, as Bandas de Bollinger e os sinais de compra/venda.

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**:
  - `pandas` para manipulação de dados
  - `numpy` para cálculos numéricos
  - `matplotlib` e `seaborn` para visualização
  - `requests` ou `yfinance` para coleta de dados financeiros
- **Ambiente de Desenvolvimento**: Jupyter Notebook ou IDE de sua escolha

## Estrutura do Projeto

1. **Data Collection**: Scripts para importar e limpar dados financeiros.
2. **Bollinger Bands Calculation**: Implementação dos cálculos das bandas superior e inferior.
3. **Backtesting Engine**: Lógica para simulação de estratégias de negociação e avaliação de desempenho.
4. **Visualization**: Ferramentas para criar gráficos e relatórios.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/projeto-bollinger-backtesting.git
