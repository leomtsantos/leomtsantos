# Olá, eu sou o Léo 👋

Profissional de Dados com mais de 2 anos de experiência em **Business Intelligence, análise, transformação e automação de dados**, atualmente direcionando minha carreira para **Engenharia de Dados**.

Minha experiência profissional envolve tratamento e validação de dados, modelagem, construção de indicadores e automação de processos. Hoje, aplico essa base no desenvolvimento de pipelines e arquiteturas de dados, trabalhando com **Python, SQL, PostgreSQL, dbt, Apache Airflow, Docker, PySpark e AWS**.

Busco entender não apenas como uma ferramenta funciona, mas por que ela está sendo utilizada e qual problema o dado precisa resolver.

🎓 Tecnólogo em **Segurança da Informação pelo Senac São Paulo**.

## 🚀 Projetos em destaque

### Simple AWS Data Lake

Data Lake desenvolvido na AWS com arquitetura em camadas para armazenamento, processamento e análise de dados de viagens.

**Arquitetura:**  
`CSV → Amazon S3 Bronze → PySpark → Parquet → Amazon S3 Silver → AWS Glue → Amazon Athena`

**Destaques:**

- organização do Data Lake em camadas Bronze e Silver no Amazon S3;
- transformação e limpeza dos dados com PySpark;
- remoção de duplicidades e registros inválidos;
- conversão e validação dos tipos de dados;
- armazenamento dos dados processados em Apache Parquet;
- catalogação dos dados com AWS Glue Data Catalog;
- consultas SQL serverless com Amazon Athena;
- validação ponta a ponta do pipeline.

**Stack:** Python • PySpark • Amazon S3 • AWS Glue • Amazon Athena • Apache Parquet • SQL

[Ver projeto](https://github.com/leomtsantos/simple-aws-data-lake)

---

### Weather Airflow Pipeline

Pipeline meteorológico que consulta a API Open-Meteo, valida os dados recebidos e armazena os registros no PostgreSQL por meio de uma DAG do Apache Airflow.

**Arquitetura:**  
`Open-Meteo API → Airflow → Extract → Validate → Load → PostgreSQL`

**Destaques:**

- orquestração do pipeline com Apache Airflow;
- validação dos dados antes da carga;
- retries automáticos e tratamento de falhas;
- bloqueio das tarefas seguintes quando uma etapa falha;
- cargas idempotentes no PostgreSQL;
- ambiente local com Docker Compose;
- documentação de testes, falhas e troubleshooting.

**Stack:** Python • Apache Airflow • PostgreSQL • Docker • SQL • Open-Meteo API

[Ver projeto](https://github.com/leomtsantos/weather-airflow-pipeline)

---

### Sales Data Pipeline

Pipeline de vendas que transforma dados de clientes, produtos e pedidos em uma tabela analítica preparada para consultas de negócio.

**Arquitetura:**  
`CSV → Python → PostgreSQL → dbt → Analytics`

**Destaques:**

- ingestão de arquivos CSV com Python e pandas;
- armazenamento dos dados no PostgreSQL;
- modelagem em camadas Raw, Staging e Mart;
- transformações e testes de qualidade com dbt;
- criação da tabela analítica `fact_sales`;
- cargas idempotentes para evitar duplicações;
- execução local com Docker.

**Stack:** Python • pandas • PostgreSQL • dbt • Docker • SQL

[Ver projeto](https://github.com/leomtsantos/sales-data-pipeline)

## 🛠️ Tecnologias

**Engenharia e processamento de dados**  
Python • SQL • pandas • PySpark • ETL/ELT • Apache Airflow

**Cloud e Data Lake**  
AWS • Amazon S3 • AWS Glue • Amazon Athena • Apache Parquet

**Banco de dados e transformação**  
PostgreSQL • dbt • Modelagem de Dados • Qualidade de Dados

**Infraestrutura e ferramentas**  
Docker • Docker Compose • Git • GitHub • Linux

**BI e Analytics**  
Power BI • Power Query • Power Pivot • Excel

## 💡 Experiência e trajetória

Atuei profissionalmente com BI e análise de dados em uma operação de Trade Marketing para a NIVEA (Beiersdorf), trabalhando com dados operacionais, transformação, modelagem, qualidade, automação e construção de indicadores.

Essa experiência me deu uma visão prática sobre as necessidades do negócio e a importância de disponibilizar dados confiáveis para análise e tomada de decisão.

Atualmente, estou ampliando essa experiência para **Engenharia de Dados**, com foco em ingestão, validação, transformação, armazenamento e disponibilização de dados, além do desenvolvimento de projetos envolvendo **orquestração de pipelines, processamento com PySpark e arquiteturas de dados na AWS**.

## 📫 Contato

[LinkedIn](https://www.linkedin.com/in/leonardo-moutinho-santos-9363aa430/)
