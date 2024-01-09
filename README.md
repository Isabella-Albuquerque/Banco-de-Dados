# Banco-de-Dados

Este repositório contém scripts SQL relacionados a um sistema de banco de dados para uma Farmácia, Boteco ou Pizzaria, dependendo do contexto. Os scripts incluem a criação de tabelas, inserção de dados e consultas básicas.

## Estrutura do Banco de Dados

O banco de dados é projetado para conter informações sobre produtos comercializados, categorias específicas e outros detalhes relevantes para o negócio.

### Tabelas

1. **tb_categorias:** Armazena informações sobre as categorias de produtos.
   - `id_categoria` (Chave Primária)
   - `tamanho` (Nome da categoria, por exemplo: broto, média, grande)

2. **tb_produtos:** Contém detalhes sobre os produtos comercializados.
   - `id_produto` (Chave Primária)
   - `nome_produto` (Nome do produto)
   - `preco_produto` (Preço do produto)
   - `estoque_produto` (Quantidade em estoque)
   - `id_categoria` (Chave Estrangeira referenciando tb_categorias)

## Scripts SQL

1. **create_database.sql:** Script para criar o banco de dados.
2. **create_tables.sql:** Criação das tabelas `tb_categorias` e `tb_produtos`.
3. **insert_data.sql:** Inserção de dados de exemplo nas tabelas.
4. **select_pizzas.sql:** Exemplos de consultas SQL, incluindo a utilização de INNER JOIN.

## Executando os Scripts

1. Execute `create_database.sql` para criar o banco de dados.
2. Execute `create_tables.sql` para criar as tabelas.
3. Execute `insert_data.sql` para inserir dados de exemplo.
4. Explore e execute `select_pizzas.sql` para realizar consultas específicas.

Sinta-se à vontade para contribuir, sugerir melhorias nos scripts ou utilizar/adaptar conforme necessário para o seu projeto!

**Nota:** Certifique-se de realizar backups adequados antes de executar scripts que envolvam a criação ou modificação de bancos de dados existentes.
