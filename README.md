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