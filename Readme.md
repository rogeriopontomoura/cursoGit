# Curso de Git

Repositório para testes do curso de Git e GitHub

[Git e GitHub para inicantes](https://www.udemy.com/git-e-github-para-iniciantes/)

**Iniciar repositório**

> git init

**Clonar Repositório**

> git clone "url"

**Adicionar arquivos a um commit**

> git add "file"

> git add .

**Commit**

> git commit -m "descrição"

**Atualizar repositório**

> git pull origin master

**Criar um branch**

> git checkout -b "nomeDoBranch"

**Alternar entre branchs**

> git checkout "nomeDoBranch"

**Deletar branch**

> git branch -D "nomeDoBranch"

**Deletar branch do resositório remoto** 

> git push branch :"nomeDoBranch"

**Merge**

Cria um novo commit fazendo a junção entre branchs

> git merge "nomeDoBranch" master

Mostra a forma gráfica dos commits

> git log --graph

**Rebase**

Coloca o commmit do branch como ultimo commit do principal

> git rebase "nomeDoBranch"

**Revert**

Reverte um commit para o anterior mantendo o commit para posterior recuperação

> git revert "id do commit"