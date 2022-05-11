
# Git e Github

Entregável do conteúdo da semana. 

## Funcionalidades

### Instalando e configurando o git

**Define o nome**

git config --global user.name "Nome"

**Define o e-mail**

git config --global user.email email@example.com 

### Criando o projeto ###

**Inicializando um Repositório em um Diretório Existente**

git init

**Clonando um repositório existente**

git clone [url] 

### Básico ###

**Monitorando Novos Arquivos**

git add .

**Verificando o status**

git status

**Armazena o conteúdo atual do índice em um novo commit**

git commit -m "Mensagem"

**Remove o arquivo do git**

git rm --cached "nomearquivo"

### Branch e Merge ###

**Lista todas as branch's**

git branch

**Cria uma branch**

git branch "nome"

**Acessa uma branch**

git checkout "nome"

**Cria uma branch e acessa**

git checkout -b "nome"

**Exclui uma branch**

git branch -d "nome"

**Faz um merge**

git checkout main 

git merge "nome-da-branch"

**Histórico de commits**

git log

**Salva alterações sem commit**

git stash

**Ver stashes guardadas**

git stash list

**Restaura alterações salvas**

git stash pop

**Aplica stash especifico**

git stash pop stash@{1}

**Compartilhar e Atualizar Projetos**

**Atualizando local**

git pull

**Transfere commits a partir de um repositório local para um remoto**

git push








## Autor

- [@eduardohor](https://github.com/eduardohor) (Eduardo Henrique)

