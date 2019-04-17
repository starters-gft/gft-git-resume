

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

# Paulo - Comandos Utilizados / Aprendidos



|    Comandos    |Descrição                          |
|----------------|-------------------------------|
|git config -- 'global'  user.name|`'Configuração do Username do github'`            |
|git config --global user.email          |`"Configuração do Email do github"`            |
|git init          |`Cria pasta. git para repositorio`|
|git add. |`'Adiciona todos os arquivos ao Index'`|
|git commit -m "comentario das alterações"|`"Envia os arquios para o HEAD, mas nao para o repositorio"`|
|git remote add origin [insere o URL]|`Envia os arquivos para github `|
|git push -u origin master|`'Envia os arquivos para o nivel master'`            |
|git status          |`"Mostra os arquivos do branch para enviar"`            |
|git diff           |`Exibe todas as diferenças entre sua cópia local e o índice sincronizado`|
|git log|`'Exibe todo o Log das ultimas commit feita'`            |
|git pull origin master          |`Envia o projeto para o Branch ( repositorio ) Master"`            |
|git checkout -b FEATURE          |`Verifica se existe local FEATURE, com o -b se nao existe ele é criado`|
|git checkout [branch]|`Muda de branck`            |
|git branch          |`"Mostra todos os branch"`            |
|git reset --hard          |`volta para o commit anterior ou até o comit indicado`|





## Ariel -> COMANDOS APRENDIDOS



|       COMMAND         |USE                                                   |
|----------------|-------------------------------
|`git init`|initializes git repo in the directory
|`git config (--global) user.name "[insert username]"  `     |sets the username   
|`git config (--global) user.email "[insert email]"`|set the email
|`git add` 	|stages a file
|`git commit -m "commit message"`|commits staged files with message
|`git remote add origin [insert repo URL] `|set the origin of the repo
| `git push -u origin master`|pushes commit to the master branch in the origin for the first time
|`git checkout -b feature/nome`|create branch and changes to it
|`git checkout master`|change to branch
| `git pull`| gets any new commits and applies to the project


### Comandos utilizados

    git init
    git config user.name "aiml150"
    git config user.email "ariel.molina@gft.com"
    echo "bem bestinha" >> bemBestinha.txt
    git add .\bemBestinha.txt
    git commit -m "commit bestinha"
    git status
    git remote add origin https://github.com/starters-gft/aimlGit.git
    git push -u origin master
    rm *
    git clone https://github.com/starters-gft/aimlGit.git
    git checkout -b FEATURE/mudar-texto
    git add .
    git commit -m "Texto alterado"
    git push origin FEATURE/mudar-texto

## README do projeto start

# Vinicius - COMANDOS APRENDIDOS

| Comandos GIT                                              | Descrição                                                                   |
| --------------------------------------------------------- |:--------------------------------------------------------------------------: | 
| git config --global user.name "Nome do usuário"           | Configura o nome do usuario do Git para todas as pastas                     | 
| git config --global user.email "Email"                    | Configura o email do usuario do Git para todas as pastas                    | 
| git init                                                  | Vai criar a pasta .git que vai ter as configurações do repositório          | 
| git add .                                                 | Muda o status de changes para staged changes ("Deixa pronto para commitar") | 
| git commit -m "first commit"                              | Faz o primeiro commit dos arquivos                                          | 
| git remote add origin "URL do Repositorio"                | Configura a URL do repositório do projeto                                   | 
| git push -u origin master                                 | Envia para o repositório                                                    | 
| git clone "URL"                                           | Clona o projeto                                                             |
| git status                                                | Vê os arquivos que foram alterados                                          | 
| git log                                                   | Histórico de commits                                                        | 
| git pull                                                  | Puxa as informações que estão no repositório                                | 
| git checkout -b "Nome da Branch"                          | Muda a branch e cria a branch se ela não existir                            | 
| git checkout -a                                           | Mostra quais branchs foram criadas                                          | 
| git reset --hard                                          | Discarta as alterações                                                      |

# Leonardo -> COMANDOS APRENDIDOS

| Comando | Descrição |
|:----:| :----: |
| git git config --global user.name '//nome' | Initial config - define nome |
| git config --global user.email '//email' | Initial config - define email |
| git init | Cria a pasta inicial .git |
| git add //archive |  O arquivo torna-se pronto para commitar |
| git commit -m "//mensagem" | Commita os arquivos, sendo a mensagem seu rótulo |
| git remote add //endPointName //url do github | Determinar o acesso remoto da pasta .git para url do github |
| git push -u //endPointName //branch | sobe os arquivos para o github alocando na branch |
| git clone //url | Clona o projeto da url do github |
| git status | retorna o status da branch atual |
| git dif //archive | Mostra as alterações do arquivo |
| git log | historico de commits |
| git pull //EndPointName // branch | Baixa os arquivos do github |
| git checkout -b //TipoDaBranch/nomeDaTask | Mudar de branch. -b cria a branch,caso não exista |
| git reset --hard | reseta até o último commit |
| git branch | Lista a branchs locais, ou seja, nas quais trabalhou |
| git branch -a | Lista todas a branchs disponíveis no github |
| git log --graph | Mostra a árvore de alterações |

## Branch:

| Tipo | Descrição |
| :---: | :---: |
| master  | código está em produção |
| develop | código que está em desenvolvimento |
| uat | código está em homologação |
| feature | código de funcionalidades |

## Gilberto -> Comandos aprendidos

| Comando | Descrição |
| :-----: | :-------: |
|**git config -- global user.name username**|Adiciona um usuário para todos os repositórios|
|**git config -- global user.email email**|Adiciona um email de autor para todos os repositórios|
|**git init**|Cria um repositório git|
|**git add**|Adiciona um arquivo ou diretório na área de staging para realizar um commit|
|**git add .**|Adiciona todos os arquivos alterados para a área de staging|
|**git commit -m "Mensagem"**|Cria um commit com uma mensagem|
|**git remote add origin url**|Configura para qual endereço remoto o repositório local deve apontar|
|**git push -u origin master**|Envia o commit para o repositório remoto (-u é usado somente no primeiro commit)|
|**git clone url**|Faz uma cópia do repositório remoto para o local|
|**git status**|Mostra as mudanças feitas no projeto|
|**git log**|Mostra o histórico de commits|
|**git log --graph**|Mostra o histórico de branches e commits de forma visual|
|**git pull**|Puxa as atualizações de uma branch do remoto para o local|
|**git git checkout branch**|Muda para a branch e sincroniza os arquivos de acordo com essa branch|
|**git checkout -b branch**|Cria uma nova branch e muda para ela|
|**git reset --hard**|Remove todas as alterações feitas|

