# Análise de Dados do E-commerce Brasileiro com Databricks

## 🌟 Visão Geral
Este repositório contém um projeto completo de **análise de dados de e-commerce brasileiro** utilizando **Databricks, Azure Data Lake e Apache Spark**. O objetivo é explorar e transformar os dados de vendas online, fornecendo insights valiosos sobre **clientes, pedidos, pagamentos, produtos e vendedores**.

Os dados utilizados neste projeto foram obtidos do conjunto de dados do Olist, disponível no **Kaggle**:
[Dataset: Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 🎩 Tecnologias Utilizadas
- **Databricks** – Plataforma para processamento de Big Data
- **Apache Spark** – Processamento distribuído
- **Azure Data Lake** – Armazenamento escalável
- **Python / PySpark** – Manipulação de dados e análise
- **Jupyter Notebooks** – Documentação e execução do código
- **Pandas & Matplotlib** – Análise e visualização de dados

## 📊 Análises e Etapas do Projeto
### 1. **Ingestão de Dados**
- Leitura dos arquivos do dataset e armazenamento no **Azure Data Lake**
- Montagem dos diretórios no Databricks via **dbutils.fs.mount**
- Conversão dos dados para formato otimizado (**Parquet**)

### 2. **Exploração e Limpeza de Dados**
- Tratamento de valores nulos e duplicados
- Padronização dos nomes das colunas
- Criação de novas colunas para facilitar análises futuras

### 3. **Análise de Vendas e Pagamentos**
- Volume total de vendas
- Médias de valores de pedidos
- Forma de pagamento mais utilizada
- Tempo médio de aprovação do pagamento

### 4. **Análise de Clientes e Localização**
- Distribuição geográfica dos clientes
- Estados com maior número de pedidos
- Fidelidade dos clientes (quantidade de pedidos por cliente)

### 5. **Análise de Produtos e Categorias**
- Produtos mais vendidos
- Categorias com maior volume de vendas
- Tempo médio de entrega por categoria

### 6. **Análise de Vendedores**
- Vendedores com maior volume de vendas
- Tempo médio de despacho dos pedidos
- Distribuição geográfica dos vendedores

### 7. **Análise de Avaliações dos Pedidos**
- Média das avaliações
- Principais reclamações dos clientes
- Correlação entre tempo de entrega e avaliação

## 🔧 Como Rodar o Projeto
### 1. **Configurar o Ambiente**
- Criar uma conta no **Databricks**
- Criar um **Azure Data Lake Storage** para armazenar os dados

### 2. **Clonar o Repositório**
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 3. **Fazer Upload dos Dados para o Data Lake**
1. Baixe os arquivos do [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
2. Envie os arquivos para um **Azure Data Lake**
3. Atualize as credenciais e caminhos no notebook

### 4. **Executar os Notebooks no Databricks**
- Importe os notebooks para o **Databricks**
- Atualize as credenciais do Data Lake
- Execute as células para processar e visualizar os dados

## 🚀 Próximos Passos
- Criar dashboards interativos usando **Power BI ou Tableau**
- Implementar um modelo preditivo para **previsão de vendas**
- Melhorar a performance do pipeline com **Delta Lake**

## 📈 Contribuição
Se quiser contribuir, sinta-se à vontade para abrir um **Pull Request** ou sugerir melhorias via **Issues**. Qualquer sugestão é bem-vinda! 🚀

## Agradecimentos
Este projeto foi inspirado em diversas análises de dados já realizadas sobre o dataset. Agradeço à comunidade de **Data Science** e **Big Data** pelo compartilhamento de conhecimentos.

## 🌐 Redes do Autor

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/137515142?v=4" width=115><br><sub>Rafael Alves Silva Rezende</sub>](https://github.com/rafa-rez) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/rafaelrezende2004) |
| :---: | :---: |
