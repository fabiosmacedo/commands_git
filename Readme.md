
# 1. Comandos do Git

## 1.1. Configuração

 - usuario
 - senha

## 1.2. Comandos

 - $git init Inicalizar um repositorio
 - $git status vericas status do repositorio
 - - $git status -s verificar status resumido
 - $git add para adicionar os arquivos que tiveram atualização ao repositorio
 - - $git add <nome do arquivo> 
 - - $git add * Para add todos
 - - $git add -A Tbm para add todos





… Ou crie um novo repositório na linha de comando
echo "# command_git" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M master 
git remote add origin https://github.com/fabiosmacedo/commands_git.git
 git push - seu mestre de origem
… Ou envie um repositório existente a partir da linha de comando
git remote add origin https://github.com/fabiosmacedo/commands_git.git
 git branch -M master 
git push -u origin master
… Ou importe o código de outro repositório
Você pode inicializar este repositório com o código de um projeto Subversion, Mercurial ou TFS.