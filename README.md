# Análise de Dados de Clientes

Este projeto realiza uma análise exploratória de um conjunto de dados sobre clientes, utilizando Python e bibliotecas como `pandas` e `plotly.express`. O objetivo principal é analisar características dos clientes, como idade, salário, profissão, experiência de trabalho e tamanho da família, a fim de extrair insights úteis.

## Estrutura do Projeto

O projeto está estruturado em um Jupyter Notebook e segue as etapas descritas abaixo:

1. **Carregamento de Dados**: 
   O dataset utilizado contém informações sobre 2000 clientes, incluindo:
   - `ClienteID`: Identificação única do cliente.
   - `Origem`: Origem do cliente (categoria).
   - `Idade`: Idade do cliente.
   - `Salário Anual (R$)`: Salário anual informado.
   - `Nota (1-100)`: Nota do cliente com base em algum critério.
   - `Profissão`: Profissão do cliente.
   - `Experiência Trabalho`: Anos de experiência no trabalho.
   - `Tamanho Família`: Quantidade de pessoas na família do cliente.

2. **Limpeza de Dados**:
   - Exclusão de colunas desnecessárias.
   - Tratamento de valores ausentes.
   - Conversão de tipos de dados.

3. **Análise Exploratória**:
   - Visualizações interativas e análise estatística dos dados.
   - Gráficos gerados com a biblioteca `plotly.express` para entender a distribuição de variáveis.

## Bibliotecas Utilizadas

- [Pandas](https://pandas.pydata.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)


## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/VieiraNando96/perfil_clientes.git

2. Instale as dependências:
    ```bash
    pip install pandas plotly

3. Abra o Jupyter Notebook: jupyter notebook Analise.ipynb
