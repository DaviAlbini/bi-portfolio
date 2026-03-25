# DRE Analítico – Embraer (B3)

## Preview
<img src="https://raw.githubusercontent.com/DaviAlbini/bi-portfolio/main/dre-b3/img/Frame%2030.png" width="100%" />

## Apresentação do Projeto
🎥 Vídeo do projeto:  
https://github.com/DaviAlbini/bi-portfolio/blob/main/dre-b3/DRE%20-%20Embraer.mp4

📄 Documentação detalhada:  
[DRE Dashboard - EMBRAER](./DRE%20Dashboard%20-%20EMBRAER%20-%20Parte1.pdf)

## Acesse o Dashboard Online
[Visualizar no Power BI](https://app.powerbi.com/view?r=eyJrIjoiNzcyZmM0YjItNjcyMC00NDNlLWI0NzUtNjc0ODZlMGU5Mjc2IiwidCI6Ijg2ODkzNGQ2LTZlMDctNGEwYi04Y2M4LTE4NWNjN2EwYzEwOCJ9)

## Objetivos
Este projeto tem como objetivo construir um dashboard analítico da Demonstração do Resultado do Exercício (DRE) da Embraer, permitindo uma leitura dinâmica, estratégica e orientada à tomada de decisão.

A proposta vai além da análise contábil tradicional, buscando responder perguntas-chave de negócio como origem de receita, formação de margens, impacto do mix de produtos e influência de fatores externos como câmbio e estrutura financeira.

O projeto demonstra como estruturar uma solução de analytics capaz de transformar dados financeiros complexos em insights acionáveis, reduzindo o tempo entre análise e decisão.

## Escopo e Desafios
- Extração automatizada de dados financeiros da CVM (DFP) via Python, garantindo atualização e rastreabilidade.  
- Tratamento de múltiplas versões de demonstrativos contábeis, selecionando sempre a última versão válida por exercício.  
- Reconstrução da estrutura hierárquica da DRE a partir de códigos contábeis brutos.  
- Modelagem de dados orientada à análise financeira, suportando navegação por níveis e análise temporal.  
- Criação de métricas financeiras complexas (EBIT, margens, análises vertical e horizontal).  
- Tratamento de inconsistências e padronização de dados contábeis.  
- Desenvolvimento de um dashboard com foco em storytelling analítico e suporte à decisão.  

## Metodologia e Técnicas Utilizadas
- **ETL automatizado em Python** para coleta, filtragem e preparação dos dados da CVM.  
- **Modelagem de dados em Power BI** utilizando arquitetura em estrela (Star Schema), separando fatos e dimensões.  
- **Power Query (M)** para transformação, limpeza e estruturação dos dados.  
- **Medidas DAX avançadas** para cálculo de indicadores financeiros, margens e análises comparativas (YoY).  
- **Time Intelligence** para análise de séries históricas e evolução dos indicadores.  
- **Modelagem semântica** com hierarquia de contas contábeis para navegação analítica.  
- **Design de dashboard orientado a negócio**, aplicando conceitos de data storytelling e usabilidade.  

## Valor do Projeto
- Criação de uma visão analítica completa da DRE, permitindo entendimento profundo dos drivers de resultado.  
- Redução do tempo de análise financeira e aumento da capacidade de tomada de decisão.  
- Identificação de padrões de receita, margem e impacto do mix de produtos.  
- Estrutura replicável para análise de qualquer empresa listada na B3.  
- Aplicação prática de conceitos de governança e modelagem analítica, alinhados a um contexto de Analytics COE.  
- Demonstração de como dados financeiros complexos podem ser transformados em inteligência estratégica.  

## Tecnologias
- Python  
- Power BI  
- DAX  
- Power Query (M)  
- SQL  
- Dados públicos da CVM  

## Contato
- [LinkedIn – Davi Albini](https://www.linkedin.com/in/davialbini/)  
- davialbini@gmail.com  
