# CRUD-Java com MySQL

<h2>Descrição</h2>

<p>Aplicação básica em Java integrado com MySQL ultilizando a plataforma NetBeans, contém um CRUD usando JTables e outros componentes graficos do Swing toolkit, no qual é feito pesquisa, inserção, atualização ao clicar em algum item da linha do JTable, e remover item.</p> 
<p>Desenvolvido no SENAI Londrina Paraná. </p>

<h2>Linguagens e Ferramentas Usadas</h2>

<ul>
  <li>Java</li> 
  <li>MySQL</li>
  <li>NetBeans</li>
</ul>

<h2>Database</h2>

```sql
create database db_usuario;

use db_usuario;

CREATE TABLE usuario (
id BIGINT(10) AUTO_INCREMENT,
nome VARCHAR(255),
cpf VARCHAR(255),
email VARCHAR(255),
telefone VARCHAR(255),
PRIMARY KEY (id)
);
```
