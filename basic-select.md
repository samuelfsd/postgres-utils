
### Comandos de Seleção

- SELECT

```sql
SELECT * FROM categories;
```

O comando de seleção SELECT é comumente utilizado para visualização dos dados de uma determinada tabela.

No exemplo acima é requerido para selecionar tudo da tabela categorias.

Também podendo ser utilizado em campos específicos.

```sql
SELECT product_id, product_name, unit_price FROM products;
```

### Comentários

Para realizar comentários no SQL / Postgres é utilizando o --

Comentando apenas uma linha:

```sql
-- deixe aqui seu comentário
```

Para um comentário com múltiplas linhas:

```sql
/*
----- deixe aqui seu comentário -----
*/
```

### ALIAS: AS

ALIAS: O Comando AS tem o intuito de renomear as colunas e tabela

```sql
SELECT
  product_id AS produto,
  product_name AS nome,
  unit_price AS preço
FROM products;
```

### LIMIT: Limitando a quantidade de linhas da query

O comando LIMIT que deve ser utilizado para um reconhecimento de tabelas ou colunas que podem ter muitos dados mas querendo passar um filtro melhor

```sql
SELECT * FROM orders LIMIT 10;
```

### DISTINCT: Selecionar os valores distintos de uma coluna

```sql
SELECT DISTINCT contact_title FROM customers;
```
Selecionando os valores distintos da tabela customers. Assim mostrando apenas os valores que não se repetem.

aula #F559
