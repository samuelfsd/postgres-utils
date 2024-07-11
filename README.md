# postgres-utils

Aqui irei fazer as anotações sobre conhecimentos do Postgres e SQL;

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

