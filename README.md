# 1 - Aula Banco de dados
 <div align="center">
   <a href="https://github.com/gladsonsimoes/AulaBancoDeDadosSenai/blob/main/imagensReferencias/imagens.md"> imagens para referencia </a> | 
   <a href=""> SriptComAnotação </a>
 </div>
 
<br>
<h1 align="center"> MYSQL </h1>


![image](https://user-images.githubusercontent.com/99969693/198150144-2fb6d715-9c97-43a3-afea-d7604a05224a.png)

~~~mysql
-- comentário 1
# comentário 2
/* comentário 3 */
~~~


### Sem Comentários: 

~~~mysql
create database senai;
use senai; 
CREATE TABLE pessoas (pessoaid int, pessoaNome varchar(255), pessoaSobrenome varchar(255));
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (1,"Ramon","Nascimento"); 
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (2,"Gladson","Simões"); 
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (3,"Juan","Novais");
SELECT * FROM pessoas;
SELECT * FROM pessoas WHERE pessoaid = 1;
~~~


### Com Comentários: 



## relação entre tabelas







