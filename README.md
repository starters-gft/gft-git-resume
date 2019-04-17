# Project Git

 -------------
### | André Rama |
------------- 

### Entendimento Geral

Git -- uma Ferramenta de Controle e distribuiçao de software e codigos, onde tambem pode ser um container de registro das ediçoes do seu software.

### Lista de Comandos Git
-- Comandos que estudei e desenvolvi a pratica.
 
 --git para Config de User
 1. git config --global user.name "user Name"
 2. git config --global user.email "user@email.com"

 --git de Adicionar Files ao Repositorio

 git add .
 --comando de adicionar todos arquivos

 git add ./Nome_do_File.html
 --Comando de Adicionar um arquivo especifico para o Repositorio

 git checkout -b master
 --Comando de verificaçao e criaçao do branch (master)

 git checkout -b FEATURE/Name_step
--Comando de verificaçao e criaçao do Branch (parcial, onde voce edita partes do codigo)

git commit -m "First Commit"
--Comando gera seu primeiro pacote git do software

git remote add origin "caminho_url"
--Comando de conexao com o caminho

git push -u origin master
--comando para subir os Files no git

git pull origin master
--comand para puxar os dados do git

git reset --hard
--comando de reset onde ele volta ao ultimo commit gerado