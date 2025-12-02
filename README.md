# Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX - 

# Desafio: Modelagem e Transformação de Dados com DAX no Power BI

## Descrição do Desafio

O objetivo deste desafio é utilizar a tabela única de **Financial Sample** para criar um modelo baseado em **star schema**, que inclui tabelas de dimensão e fato. O processo envolve a criação de novas tabelas a partir da tabela original, selecionando colunas específicas para compor a visão das novas tabelas. Assim, a tabela principal (fato) será utilizada para gerar as tabelas de dimensão.

## Estrutura das Tabelas

- **Financials_origem** (modo oculto - backup)
- **F_Vendas** (fato)
- **D_Produtos** (dimensão)
- **D_Produtos_Detalhes** (dimensão)
- **D_Detalhes** (dimensão)
- **D_Calendário** (dimensão)

## Descrição dos Passos Utilizados

1. **Importação de Dados**  
   Importar os dados da planilha **Financial Sample** para o **Power BI Desktop**.

2. **Duplicação da Tabela**  
   Duplicar a tabela **Financials** e criar a tabela **Financials_origem** (backup).

3. **Criação da Tabela Fato**  
   Na Modelagem, criar a tabela **F_Vendas** (fato).

4. **Criação das Tabelas de Dimensão**  
   Criar as seguintes tabelas de dimensão:
   - **D_Produtos**
   - **D_Produtos_Detalhes**
   - **D_Detalhes**
   - **D_Descontos**
   - **D_Calendário**  
   *(construída conforme orientações de "Os Primeiros Passos com DAX")*

5. **Transformação e Definição de Colunas**  
   Realizar a transformação, composição e definição das colunas para as tabelas de dimensão: **D_Produtos**, **D_Produtos_Detalhes**, **D_Descontos**, e **D_Detalhes**.
   ![](1.jpg)
6. **Organização e Relacionamentos**  
   Organizar, estabelecer links e definir os relacionamentos entre as tabelas conforme o Star Schema.

