# Git Quick Reference Guide for Beginners

---

## Configuração Inicial

Definir nome de usuário e email global:
`git config --global user.name "Seu Nome"`
`git config --global user.email "seuemail@example.com"`

## Criar e Clonar Repositórios

Clonar um repositório existente:
`git clone URL_DO_REPOSITÓRIO`

Criar um novo repositório local:
`git init`

## Trabalhando com Commits

Adicionar arquivos à área de preparação:
`git add <nome_do_arquivo>`

Adicionar todos os arquivos alterados à área de preparação:
`git add .`

Criar um commit com as alterações na área de preparação:
`git commit -m "Mensagem do commit"`

Verificar o status do repositório:
`git status`

## Trabalhando com Branches

Criar um novo branch:
`git branch <nome_do_branch>`

Mudar para um branch existente:
`git checkout <nome_do_branch>`

Criar um novo branch e mudar para ele:
`git checkout -b <nome_do_branch>`

Listar todos os branches no repositório:
`git branch`

## Integração de Branches

Mesclar alterações de um branch no branch atual:
`git merge <nome_do_branch>`

Rebase - Reaplicar alterações de um branch no branch atual:
`git rebase <nome_do_branch>`

## Trabalhando com Repositórios Remotos

Adicionar um repositório remoto:
`git remote add <nome_do_repositório_remoto> URL_DO_REPOSITÓRIO`

Enviar alterações para o repositório remoto:
`git push <nome_do_repositório_remoto> <nome_do_branch>`

Obter alterações do repositório remoto:
`git pull <nome_do_repositório_remoto> <nome_do_branch>`

## Visualizar Histórico de Commits

Visualizar o histórico de commits:
`git log`

Visualizar o histórico de commits simplificado:
`git log --oneline`

Visualizar o histórico de commits com um gráfico:
`git log --oneline --graph`

## Desfazer Alterações

Descartar alterações em um arquivo específico:
`git checkout -- <nome_do_arquivo>`

Descartar todas as alterações em todos os arquivos:
`git checkout -- .`

Desfazer o último commit e manter as alterações no diretório de trabalho:
`git reset HEAD~1`

Desfazer o último commit e descartar todas as alterações:
`git reset --hard HEAD~1`

## Ignorando Arquivos

Criar um arquivo .gitignore para ignorar arquivos específicos.

## Comandos Git por Área

### Configuração Inicial

- Definir nome de usuário e email global: `git config --global user.name "Seu Nome"` `git config --global user.email "seuemail@example.com"`

### Criar e Clonar Repositórios

- Clonar um repositório existente: `git clone URL_DO_REPOSITÓRIO`
- Criar um novo repositório local: `git init`

### Trabalhando com Commits

- Adicionar arquivos à área de preparação: `git add <nome_do_arquivo>`
- Adicionar todos os arquivos alterados à área de preparação: `git add .`
- Criar um commit com as alterações na área de preparação: `git commit -m "Mensagem do commit"`
- Verificar o status do repositório: `git status`

### Trabalhando com Branches

- Criar um novo branch: `git branch <nome_do_branch>`
- Mudar para um branch existente: `git checkout <nome_do_branch>`
- Criar um novo branch e mudar para ele: `git checkout -b <nome_do_branch>`
- Listar todos os branches no repositório: `git branch`

### Integração de Branches

- Mesclar alterações de um branch no branch atual: