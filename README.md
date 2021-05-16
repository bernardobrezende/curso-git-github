# Curso de Git e Github

## Comandos Git

### log
``git log``

### checkout
``git checkout``

### reset
``git reset --hard origin/main``

### branch
Visualizar lista de branch
``git branch``

Criar nova branche
``git branch nome_da_nova_branch``

Alternar branch
``git checkout nome_da_branch``

Cria nova branch e já alterna para ela
``git checkout -b "nome_nova_branch"``

Deletar branch
``git branch -d nome_da_branch ``


### merge
``git merge nome_da_branch``


### stash
Cria nova stash
``git stash``

Lista stash
``git stash list``

Alterna para stash
``git stash applay 0``

Mostra conteúdo da stash
``git stash show -p 2``


### tags
Criar uma nova tag
``git tag -a v1.0 -m "Mensagem..."``