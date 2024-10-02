# Teste para Engenheiro de Dados Pleno

## Objetivo
Avaliar as habilidades do candidato em processar, manipular e preparar dados usando Python e criar visualizações interativas e informativas no Power BI.

O teste é dividido em duas partes:
1. **Python**: Extração, limpeza e tratamento dos dados.
2. **Power BI**: Criação de visualizações e relatórios interativos.

---

## Parte 1: Python - Extração e Tratamento de Dados

### Descrição
Você recebeu dois datasets no formato CSV:
- `Vendas.csv`: Contém informações sobre transações de vendas, como ID da venda, ID do produto, valor da venda, data e localização do cliente.
- `Clientes.csv`: Contém dados dos clientes, como ID do cliente, nome, idade, localização e preferências de produto.

### Tarefas
1. **Extração dos Dados**
   - Carregue os arquivos CSV utilizando a biblioteca **Pandas**.

2. **Limpeza e Tratamento dos Dados**
   - **Limpeza dos Dados**:
     - Remova linhas duplicadas.
     - Trate os valores ausentes, se houver, preenchendo-os com uma abordagem adequada (média, mediana ou categorização "indefinida", conforme o campo).
   - **Conversão de Tipos**:
     - Verifique e converta, se necessário, os tipos de dados para garantir que estejam no formato correto (e.g., datas como datetime, valores numéricos como float).
   - **Enriquecimento dos Dados**:
     - Faça um *merge* (união) dos dois datasets utilizando a chave `ID do Cliente`, de modo a enriquecer o dataset de vendas com as informações dos clientes.

3. **Análise dos Dados Tratados**
   - Calcule a receita total dos últimos 6 meses.
   - Identifique os 5 produtos mais vendidos e a receita total gerada por eles.
   - Crie uma tabela agregada que mostre a receita por localização dos clientes (e.g., estado ou cidade).

4. **Exportação dos Dados Tratados**
   - Exporte os dados tratados e enriquecidos para um novo arquivo CSV chamado `Vendas_Tratadas.csv`.

### Entregáveis
- Um **notebook Jupyter (.ipynb)** ou **vsCode Python (.py)** contendo o código para extração, limpeza e tratamento dos dados.
- O arquivo CSV gerado (`Vendas_Tratadas.csv`).
- Arquivo Readme.md descrevendo os principais processos realizados para atingir a solução final.

### Avaliação
- Capacidade de limpeza e transformação dos dados.
- Qualidade e clareza do código.
- Aderência às boas práticas de manipulação e tratamento de dados.

---

## Parte 2: Power BI - Visualização e Análise

### Descrição
Com o arquivo `Vendas_Tratadas.csv` gerado na Parte 1, você deve criar um relatório dinâmico em Power BI que permita ao gestor visualizar informações de desempenho da loja de forma intuitiva.

### Tarefas
1. **Conectar e Limpar Dados**
   - Importe o dataset `Vendas_Tratadas.csv` para o Power BI.
   - Verifique se há alguma necessidade de tratamento adicional no Power BI (e.g., transformação de colunas, criação de novas colunas calculadas).

2. **Criar Relatório**
   - Crie as seguintes visualizações:
     - **Receita Mensal**: Um gráfico de linha mostrando a evolução da receita ao longo dos últimos 6 meses.
     - **Produtos Mais Vendidos**: Gráfico de barras com os 5 produtos mais vendidos.
     - **Receita por Localização**: Mapa ou gráfico de barras mostrando a receita total por localização dos clientes.
     - **Análise de Clientes**: Gráfico que mostra a distribuição dos clientes por faixa etária e seu impacto na receita.
     - **Receita por Preferência de Produto**: Gráfico de rosca que demonstre qual preferência de produto dos clientes tem mais impacto na receita.

3. **Filtros e Interatividade**
   - O relatório deve incluir filtros que permitam ao gestor visualizar a performance por período (ano/mês), produto e localização do cliente.

### Entregáveis
- Um **arquivo Power BI (.pbix)** contendo o relatório pronto para apresentação.
- Arquivo Readme.md descrevendo os principais processos realizados para atingir a solução final.

### Avaliação
- Qualidade e clareza das visualizações.
- Capacidade de relacionar dados e criar insights significativos.
- Uso adequado dos filtros e criação de um dashboard intuitivo.

---

## Critérios de Avaliação Geral

1. **Capacidade Analítica**: Habilidade de extrair insights significativos dos dados tratados.
2. **Habilidades Técnicas**: Proeficiência no uso de Python para manipulação de dados e no uso de Power BI para visualização.
3. **Qualidade das Visualizações**: Criação de gráficos claros, objetivos e que forneçam informações úteis para a tomada de decisões.
4. **Organização e Clareza**: Clareza do código Python e da estrutura do relatório no Power BI.

---

Boa sorte e sinta-se à vontade para entrar em contato se tiver qualquer dúvida durante a realização do teste!
