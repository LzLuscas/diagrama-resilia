# diagrama-resilia


A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.
Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo: 

## ⇨ Existem outras entidades além dessas três?
Sim, existe o login.

## ⇨ Quais são os principais campos e tipos?
Os principais são Id, Nome, Matrícula e Curso.

## ⇨ Como essas entidades estão relacionadas?
São relacionadas 1:N e 1:1, assim como Login está associado a Aluno, Aluno está associado a Turma e Curso, e Turma está associada a Curso.


![Sistema de acompanhamento](https://user-images.githubusercontent.com/115434062/222433624-3843d4c9-faba-4a1f-ba2c-918942ec5783.png)
