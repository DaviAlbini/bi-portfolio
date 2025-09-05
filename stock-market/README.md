# Stock Market – Análise Global de Índices e Commodities

## Preview
<img width="5760" height="4096" alt="Frame 28" src="https://github.com/user-attachments/assets/3446b56d-f784-4d81-8ebd-cf236d60d3ac" />


## Acesse o Dashboard Online
[Visualizar no Power BI](https://app.powerbi.com/view?r=eyJrIjoiMGI1YzFhMDQtYmViZC00ZjJkLTgxMzMtNzExNDZhYTEzMzhmIiwidCI6IjFhNTAwM2YxLTAyOWItNGQ5MC05NjExLWJmNmNiZDcxMmNiOCJ9)

## Objetivos
Este dashboard acompanha o desempenho de **índices acionários globais** e **commodities** ao longo do tempo, permitindo:
- Comparar **retornos acumulados** e **volatilidade** entre regiões (Américas, Europa, Ásia) e classes (Índices vs. Commodities).
- Medir **CAGR (taxa composta anual)**, **Hit Rate (taxa de acertos)**, **Drawdown** e outros KPIs essenciais.
- Investigar impactos de **moedas** (USD, EUR, GBP, JPY, INR, CNY) na leitura de performance e risco.
- Visualizar tendências históricas e comportamentos por **região**, **país**, **índice/commodity** e **moeda**.

## Escopo e Desafios
- **Integração de múltiplas fontes** (repositórios públicos no GitHub e APIs como Yahoo Finance) com diferentes calendários de negociação.
- **Modelagem analítica** para comparações consistentes entre regiões, moedas e classes de ativos.
- **Cálculo de métricas financeiras** (retorno diário, acumulado, CAGR, drawdowns, hit rate) de forma eficiente em DAX.
- **Normalização e indexação** (General Index) para tornar comparáveis séries com magnitudes distintas.
- **Desempenho** do modelo: relações enxutas, minimização de colunas calculadas e priorização de medidas.

## Páginas do Dashboard (Mapa de Navegação)
1. **Visão Global (Overview)**  
   KPIs de topo: **CAGR**, **Retorno Diário**, **Índice Geral (base-100)**, **Hit Rate** e **Drawdown**. Destaques por **Região** e **Classe**.
2. **Índices por Região**  
   Linhas e barras para Américas, Europa, Ásia e Commodities, com filtros por país e ticker.
3. **Comparação Temporal**  
   Séries históricas para principais benchmarks (Nasdaq, S&P 500, Dow Jones, NYSE, FTSE 100, Euronext 100, Nikkei 225, Nifty 50, Sensex, Shanghai Composite) e commodities (Ouro, Petróleo).
4. **Moedas & Normalização**  
   Retorno acumulado por **moeda** (USD, EUR, GBP, JPY, INR, CNY) para evidenciar efeito cambial e equivalência base-100.
5. **Tabela Detalhada (Data Grid)**  
   Consulta de **Ticker, Índice, Região, Tipo, País, Moeda, Data, Open, High, Low, Close, Adj Close, Volume** e campos auxiliares (**Variação**, **Índice Geral**, **Movement**).

## KPIs e Definições (PT-BR | EN)
- **Retorno Diário | Daily Return (%)**: variação percentual do **Close** vs. dia anterior.  
- **Retorno Acumulado | Cumulative Return (%)**: retorno total do período (baseado na evolução do preço).  
- **CAGR | Compound Annual Growth Rate (%)**: taxa composta anual entre o primeiro e o último ponto do período.  
- **Índice Geral (base-100) | General Index**: série normalizada para 100 no início do recorte.  
- **Hit Rate (%)**: proporção de dias com retorno diário positivo.  
- **Drawdown (%)**: queda percentual do nível atual em relação ao **máximo mais recente**; **Max Drawdown** é o pior drawdown observado.

## Amostra dos Ativos Cobertos
**Índices:** Nasdaq Composite, S&P 500, Dow Jones Industrial Average, NYSE Composite, FTSE 100, Euronext 100, Nikkei 225, Nifty 50, BSE Sensex, Shanghai Composite.  
**Commodities:** Ouro (Gold), Petróleo (Oil).

## Tecnologias 
- Power BI
- DAX
- SQL/ETL
- Dados públicos de Finanças

## Contato
- [LinkedIn – Davi Albini](https://www.linkedin.com/in/davialbini/)  
- davialbini@gmail.com

