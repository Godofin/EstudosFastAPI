# SQL Alchemy

# Introdução

- SQLAlchemy é uma biblioteca de banco de dados Python que fornece uma interface de alto nível para trabalhar com bancos de dados relacionais. Ele fornece uma camada de abstração para o banco de dados, permitindo que você _trabalhe com diferentes bancos de dados sem alterar o código_.

- Fazendo uso do SQLAlchemy, mudando uma simples linha de código, chamada de string de conexão, nós podemos mudar completamente o banco de dados utilizado sem que seja preciso alterar nada mais nada na nossa aplicação.

- Bancos de dados permitidos:
    - SQLite.
    - PostgreSQL.
    - MySQL/MariaDB.
    - Oracle.
    - MS-SQL.
    - Firebird.
    - Sybase.
    - Outros.
    
## Cases de Sucesso

- Algumas empresas que utilizam o SQLAlchemy:
    - DropBox.
    - Yelp.
    - Reddit.
    - OpenStack.
    - SurveyMonkey.
    - Uber.
    - Mozilla.
    - Guru.

## Arquitetura do SQLAlchemy

- O SQLAlchemy é composto por 3 partes principais:
    - DBAPI.
    - Core.
    - ORM.

- O DBAPI é a interface de acesso ao banco de dados. É a camada mais baixa do SQLAlchemy. Ela é responsável por fazer a conexão com o banco de dados e executar as queries.

- O Core é a camada de abstração do banco de dados. É a camada que faz a comunicação entre o DBAPI e o ORM. É a camada que faz a tradução das queries do ORM para o DBAPI.

- O ORM é a camada de mapeamento objeto-relacional. É a camada que faz a tradução das queries do ORM para o DBAPI.

