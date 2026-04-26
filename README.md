# db-oficina-logical-schema

🔧 Projeto Lógico de Banco de Dados — Oficina Mecânica
Desafio prático da trilha Full-Stack Avançado na DIO — modelagem lógica de um banco de dados relacional para um cenário de oficina mecânica, utilizando MySQL.

📋 Descrição:
A partir do esquema conceitual criado com o modelo ER, este projeto desenvolve o esquema lógico relacional para o contexto de uma oficina mecânica, traduzindo os requisitos do negócio em uma estrutura de banco de dados coerente e normalizada.

🗂️ Estrutura do Repositório:
📦 db-oficina-logical-schema
 ┣ 📄 README.md
 ┣ 📄 oficina_schema.sql         # Script de criação do banco de dados
 ┣ 📄 oficina_queries.sql        # Queries de consulta e persistência
 ┗ 📊 diagrama_logico.png        # Diagrama do esquema lógico (opcional)
 ⚠️ Projeto em desenvolvimento. Os arquivos acima serão adicionados em breve.

 🧩 Escopo do Esquema:
O banco de dados modela as seguintes entidades principais:
Cliente — dados cadastrais dos proprietários de veículos
Veículo — informações do veículo vinculado ao cliente
Ordem de Serviço (OS) — registro de serviços solicitados, status e datas
Serviço — catálogo de serviços com mão de obra tabelada
Peça — estoque de peças utilizadas nos serviços
Mecânico — equipe responsável pela execução das ordens
Equipe — agrupamento de mecânicos por especialidade

🔍 Queries Planejadas:
As queries seguirão os requisitos do desafio, cobrindo:
SELECT simples para recuperação de dados
Filtros com WHERE
Atributos derivados com expressões
Ordenação com ORDER BY
Agrupamentos com HAVING
Junções entre tabelas (JOIN) para perspectivas mais complexas

🛠️ Tecnologias:
MySQL(SGBD principal),
DBeaver(Modelagem e execução de queries)

📚 Contexto:
Este projeto faz parte do módulo "Construindo seu Primeiro Projeto Lógico de Banco de Dados" da DIO, com orientação da especialista Juliana Mascarenhas, Data Scientist.
