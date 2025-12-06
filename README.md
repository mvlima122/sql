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

<h4>INSERT INTO</h4>
 ~~~ sql
  INSERT INTO aluno (nome, telefone, curso, turma, unidade)
  VALUES ('Vitoria', '(85) 99123455', 'Fullstack', 26, 'Sul');
 ~~~

 - `INSERT INTO`: comando para inserir dados na tabela
 - `aluno` : nome da tabela
 - `(nome, telefone, curso, turma, unidade)`: colunas da tabela que serão inseridos dados
 - `VALUES`: define valores a serem inseridos
 - `('Vitoria', '(85) 99123455', 'Fullstack', 26, 'Sul')` : valores para cada coluna da tabela referente a ordem especificada

 <h4> Selecionar Tabela</h4>

 ~~~ sql
 SELECT * FROM aluno;
 ~~~

 - `SELECT` : comando para selecionar a coluna da tabela
 - `*`: indica todas as colunas da tabela
 - `FROM`: indica qual tabela será selecionada
 - `aluno`: nome da tabela 



