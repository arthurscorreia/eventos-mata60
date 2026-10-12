# Banco de Dados de Eventos (EventOS / SBTC)

Repositório contendo o esquema relacional, script de geração de dados sintéticos e queries de inserção para o banco de dados de eventos (MATA60 - Banco de Dados / UFBA).

## Estrutura do Repositório

- `ddl.sql`: Script DDL em PostgreSQL com a criação de tabelas, tipos de dados, chaves primárias, estrangeiras e restrições de integridade.
- `gerar_dados.py`: Script Python que utiliza a biblioteca `Faker` para gerar dados sintéticos consistentes e com integridade referencial.
- `inserts_banco_de_dados.sql`: Script SQL gerado contendo todos os comandos `INSERT INTO` prontos para execução em lote no PostgreSQL.

## Pré-requisitos

- Python 3.10+
- Biblioteca `faker`:
  ```bash
  pip install faker
  ```


