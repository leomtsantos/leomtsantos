# Olá, eu sou o Léo 👋

Profissional de Dados com mais de 2 anos de experiência em **Business Intelligence, análise, transformação e automação de dados**, atualmente direcionando minha carreira para **Engenharia de Dados**.

Minha experiência profissional envolve tratamento e validação de dados, modelagem, construção de indicadores e automação de processos. Hoje, venho aprofundando essa base com projetos de Engenharia de Dados envolvendo **Python, SQL, PostgreSQL, dbt, Apache Airflow, Docker, PySpark e AWS**.

Gosto de entender não apenas como uma ferramenta funciona, mas por que ela está sendo utilizada e qual problema o dado precisa resolver.

🎓 Tecnólogo em **Segurança da Informação pelo Senac São Paulo**.

## 🚀 Projetos em destaque

### Retail Execution Analytics

Projeto em Power BI inspirado na minha experiência profissional com BI e dados em uma operação de Trade Marketing da NIVEA/Beiersdorf.

Como os dados e materiais utilizados profissionalmente são confidenciais, desenvolvi uma nova solução do zero utilizando **dados 100% sintéticos**. O projeto simula o acompanhamento da execução de materiais promocionais e pontos extras no varejo, comparando o planejado com o executado e permitindo investigar gaps, causas e pontos de maior criticidade.

**Fluxo analítico:**  
`Planejado → Executado → Gap → Causa → Localização do problema`

**Destaques:**

- modelagem dimensional com tabelas fato e dimensão;
- preparação e tratamento dos dados com Power Query;
- construção de indicadores e regras de negócio em DAX;
- análise de execução, gaps, causas, tarefas, regionais, canais e ambientes de varejo;
- medidas dinâmicas para rankings, comparação temporal e formatação condicional;
- projeto disponibilizado em PBIX e PBIP/PBIR;
- dados sintéticos criados exclusivamente para o portfólio.

**Stack:** Power BI • Power Query • DAX • Modelagem Dimensional • PBIP/PBIR

[Ver projeto](https://github.com/leomtsantos/retail-execution-analytics)

---

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
Power BI • Power Query • Power Pivot • DAX • Excel

## 💡 Experiência e trajetória

Atuei profissionalmente com BI e análise de dados em uma operação de Trade Marketing para a NIVEA (Beiersdorf), trabalhando com dados operacionais, transformação, modelagem, qualidade, automação e construção de indicadores.

Essa experiência me deu uma visão prática das necessidades do negócio e da importância de disponibilizar dados confiáveis para análise e tomada de decisão.

O projeto **Retail Execution Analytics** nasceu justamente dessa vivência: utilizei o conhecimento de domínio adquirido no trabalho para construir um novo case de portfólio, sem utilizar dados ou materiais confidenciais da empresa.

Atualmente, estou ampliando essa experiência para **Engenharia de Dados**, com foco em ingestão, validação, transformação, armazenamento e disponibilização de dados.

Os projetos acima mostram essa evolução, passando por pipelines com PostgreSQL e dbt, orquestração com Airflow, processamento com PySpark, arquitetura de Data Lake na AWS e a camada analítica em Power BI.

## 📫 Contato

[LinkedIn](https://www.linkedin.com/in/leonardo-moutinho-santos-9363aa430/)
