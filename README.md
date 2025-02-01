## Comandos Básicos de GIT
### Confira os comandos básicos e os mais utilizados no GIT:

#### Configuração Inicial:

git config --global user.name "Seu Nome" &rarr; Define o nome do usuário.<br>
git config --global user.email "seuemail@example.com" &rarr; Define o e-mail do usuário.<br>

#### Inicialização e Clonagem:

git init &rarr; Inicializa um repositório Git na pasta atual.<br>
git clone URL_DO_REPOSITORIO &rarr; Clona um repositório remoto para o seu computador.<br>

#### Status e Histórico:

git status &rarr; Exibe o status atual dos arquivos no repositório.<br>
git log &rarr; Exibe o histórico de commits do repositório.<br>
git log --oneline &rarr; Exibe o histórico resumido.<br>

#### Gerenciamento de Arquivos:

git add NOME_DO_ARQUIVO &rarr; Adiciona um arquivo específico à área de staging.<br>
git add . &rarr; Adiciona todos os arquivos modificados ao staging.<br>
git rm --cached NOME_DO_ARQUIVO &rarr; Remove um arquivo do staging.<br>
Commits
git commit -m "Mensagem do commit" &rarr; Cria um commit com os arquivos no staging.<br>
git commit --amend -m "Nova mensagem" &rarr; Edita o último commit.<br>

#### Branches (Ramificações):

git branch &rarr; Lista todas as branches.<br>
git branch NOME_DA_BRANCH &rarr; Cria uma nova branch.<br>
git checkout NOME_DA_BRANCH &rarr; Muda para uma branch específica.<br>
git switch NOME_DA_BRANCH &rarr; Alternativa mais moderna ao checkout.<br>
git checkout -b NOME_DA_BRANCH &rarr; Cria e muda para uma nova branch.<br>
git branch -d NOME_DA_BRANCH &rarr; Deleta uma branch.<br>

#### Sincronização com Repositório Remoto:

git remote add origin URL_DO_REPOSITORIO &rarr; Adiciona um repositório remoto.<br>
git remote -v &rarr; Lista os repositórios remotos configurados.<br>
git push origin NOME_DA_BRANCH &rarr; Envia commits para o repositório remoto.<br>
git pull origin NOME_DA_BRANCH &rarr; Atualiza a branch local com a versão remota.<br>
git fetch &rarr; Baixa mudanças do repositório remoto sem mesclar.<br>

#### Mesclagem e Rebase:

git merge NOME_DA_BRANCH &rarr; Mescla outra branch à branch atual.<br>
git rebase NOME_DA_BRANCH &rarr; Reaplica commits da branch atual sobre a especificada.<br>

#### Reversão de Alterações:

git reset --soft HEAD\~1 &rarr; Desfaz o último commit, mantendo as mudanças no staging.<br>
git reset --mixed HEAD\~1 &rarr; Desfaz o último commit e remove as mudanças do staging.<br>
git reset --hard HEAD\~1 &rarr; Desfaz o último commit e descarta todas as mudanças.<br>
git revert HASH_DO_COMMIT &rarr; Cria um novo commit que reverte um commit específico.<br>

Lembrando que existem diversas outras opções de comandos e configurações, que podem ser verificadas na documentação oficial do Git.
