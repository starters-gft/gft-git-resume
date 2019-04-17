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
