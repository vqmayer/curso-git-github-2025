# Curso TMW Git & GitHub 2025 #


Um curso para iniciantes aprenderem a trabalhar com versionamento de codigo e repositories remotos com GitHub.

Alem disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Confira tudo o que temos no nosso Youtube. E gratis!

## Fluxo de trabalho Git local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
04. git add .
05. git status
06. git commit -m "minha mensagem"
07. git checkout main
08. git merge nova branch

### Fluxo de trabalho GitHub <> Local (projeto proprio ou da sua empresa)

01. git clone <endereco do projeto>
02. git checkout -b <nova_branch>
03. alteracoes de arquivos
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

#### Fluxo de trabalho GitHub <> Local (projetos open-source)

01. Fork do projeto para seu proprio GitHub
02. git clone <endereco do projeto fork>
03. git checkout -b <nova branch>
04. alteracoes de arquivos
05. git status
06. git add *arquivos*
07. git status
08. git commit -m "nova mensagem"
09. git push origin <nova_branch>
10. abri Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

------

Pessoas participantes:

- Teo Calvo
- Vini Mayer
