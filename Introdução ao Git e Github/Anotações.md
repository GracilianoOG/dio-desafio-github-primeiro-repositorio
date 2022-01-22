

# Comandos do GIT

## git init

Inicia o repositório na pasta selecionada.

`git init`



## git add

Adiciona todos os arquivos no diretório atual para a área de "stage".

`git add .`



## git status

Mostra o status atual dos arquivos, se algo foi modificado, removido, etc.

`git status`



## git commit

Realiza um versionamento, salva as mudanças do repositório local.

`git commit -m "Commit inicial"`



## git remote

Define o local para que o projeto possa ser enviado para o GitHub. Apenas define o link, mas não realiza o envio em si. O "origin" serve apenas como um apelido (alias).

`git remote add origin https://github.com/nome-repo`



## git push

Envia o projeto para a nuvem na branch especificada.

`git push -u origin main`

Envia a atualização das modificações.

`git push`



## git pull

Puxa o projeto da nuvem para o repositório local.

`git pull`