# Previsão de Resultados de um E-commerce com Power BI

Desenvolvi um painel gerencial para um e-commerce utilizando minhas habilidades em **Excel** e **Power BI**, criando um **modelo de regressão linear** para prever os resultados de faturamento. Além disso, estabeleci recomendações para melhorar os resultados da empresa.

## Contexto

O objetivo foi criar um painel gerencial que permitisse ao e-commerce analisar suas vendas e traçar estratégias para alavancar os resultados. Recebi duas bases de dados: uma com as informações de **vendas** e outra com os dados dos **clientes**. A partir dessas informações, desenvolvi duas páginas no painel para que os analistas possam visualizar as principais métricas.

## Métricas Criadas

- **Quantidade total e valor total de vendas**
- **Contagem e valor total de vendas por data**
- **Quantidade e valor total por categoria**

Além disso, configurei **filtros** para facilitar a interação dos usuários, garantindo uma experiência intuitiva e agradável. O **storytelling** e o **layout** do painel foram planejados para serem atrativos e focados em insights.

## Detalhamento das Tabelas

| Coluna              | Descrição                                        | Base            |
|---------------------|--------------------------------------------------|-----------------|
| `idcompra`          | Número de identificação da compra                | Base de Compras |
| `idcanalvenda`      | Canal de venda                                   | Base de Compras |
| `bandeira`          | Bandeira da compra                               | Base de Compras |
| `data`              | Data da compra                                   | Base de Compras |
| `preço`             | Preço da compra                                  | Base de Compras |
| `preço_com_frete`   | Preço da compra + frete                          | Base de Compras |
| `nome_departamento` | Departamento do produto                          | Base de Compras |
| `estado`            | Estado da compra                                 | Base de Compras |
| `cliente_log`       | Identificação do cliente                         | Base de Compras e Base de Clientes |
| `idade`             | Idade do cliente                                 | Base de Clientes |
| `uf_nascimento`     | Cidade de nascimento do cliente                  | Base de Clientes |
| `renda`             | Renda do cliente                                 | Base de Clientes |

## Etapas de Desenvolvimento

Para a criação do painel, segui as seguintes etapas:

### 1. Análise Inicial
   - Analisei as tabelas no Excel, compreendendo as colunas e suas relevâncias para o negócio.

### 2. Cartões (Cards)
   - **Quantidade de vendas**
   - **Valor total de vendas sem frete (R$)**
   - **Valor total de vendas com frete (R$)**
   - **Quantidade de clientes**
   - **Média de renda dos clientes**

### 3. Gráficos de Linhas
   - **Contagem de vendas por mês**
   - **Valor total de vendas por mês**

### 4. Gráficos de Barras
   - **Quantidade de vendas por categoria**
   - **Valor total de vendas por categoria**
   - **Distribuição das idades dos clientes**
   - **Distribuição da renda dos clientes**

### 5. Filtros Criados
   - **Bandeira**
   - **Estado**
   - **Canal de venda**
   - **Departamento**
   - **Idade**
   - **Faixa de renda**
   - **Estado de nascimento**
