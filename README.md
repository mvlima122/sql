<h1>SQL</h1>

<h2>SQL com SQLite</h2>

<h3>Queries</h3>

<h4> CREATE TABLE</h4>

~~~ SQL
CREATE TABLE aluno (
    id INTEGER NOT NULL PRIMARY KEY AUTOINCREMENT,
    nome TEXT NOT NULL, 
    telefone TEXT NOT NULL,
    curso TEXT NOT NULL,
    turma INTEGER NOT NULL,
    unidade TEXT NOT NULL,
    pcd BOOLEAN NOT NULL DEFAULT false
 );
~~~

- `CREATE TABLE ` : comando para criar uma tabela
- `aluno`: nome da tabela
- `id`, `nome`, `telefone`, `curso`, `turma`, `unidade`, `pcd`: colunas da tabela
- `INTEGER`, `TEXT`, `BOOLEAN`: tipos de dados da coluna
- `NOT NULL`: não permite ausência de valor na coluna



