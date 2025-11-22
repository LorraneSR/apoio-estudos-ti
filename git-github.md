# Git e GitHub

### Configurando seu nome de usuário e e-mail
Comando para definir um nome do usuário para os commits
~~~
git config --global user.name "Seu Nome"
~~~

Comando para definir um e-mail do usuário para os commits
~~~
git config --global user.email "seuemail@exemplo.com" 
~~~


### Gerenciamento de repositórios
Comando para inicializar um novo repositório Git no diretório atual
~~~
git init
~~~

Comando para cria uma cópia/clone local de um repositório remoto existente
~~~
git clone <URL do Repositório no GitHub>
~~~


### Limpando os comandos
Comando para limpar a tela e remover todos os comandos digitados
~~~
$ clear
~~~


### Listando arquivos
Comando para listar todo o conteúdo que está dentro do repositório
~~~
$ ls
~~~


### Criando uma pasta
Comando criar uma pasta dentro do repositório
~~~
$ mkdir nome-pasta
~~~


### Criando um arquivo
Comando para criar um arquivo dentro do repositório. Por exemplo: para criar um arquivo chamado README.md:
~~~
$ echo > README.md
~~~

Comando para criar um arquivo dentro do repositório e adicionar um título ao conteúdo. Por exemplo: para criar um arquivo chamado README.md com o título "Introdução":
~~~
$ echo "# Introdução" > README.md
~~~


### Gerenciamento de alterações
Comando para mostra o status atual do seu repositório (arquivos modificados, preparados, etc.)
~~~
git status
~~~

Comando para adicionar alterações de um arquivo específico à área de preparação (staging area)
~~~
git add <nome do arquivo>
~~~

Comando para fazer um commit, ou seja, salvar as alterações que estão no repositório local e adicionar uma mensagem descritiva
~~~
git commit -m "Mensagem do commit"
~~~

Comando para mostrar as diferenças entre o estado de trabalho atual e a última versão confirmada 
~~~
git diff
~~~


### Sincronizando com repositórios remotos
Comando para adicionar um repositório remoto como origin 
~~~
git remote add origin <URL do repositório remoto>
~~~

Comando para enviar os commits locais para o repositório remoto 
~~~
git push -u origin <nome da branch>
~~~

Comando para atualizar o repositório local puxando as alterações mais recentes do repositório remoto
~~~
git pull origin <nome da branch>
~~~

Comando para baixar as alterações de um repositório remoto sem incorporá-las automaticamente ao sua branch local
~~~
git fetch
~~~

### Gerenciamento de branches
Comando para listar todas as branches locais
~~~
git branch
~~~

Comando para criar uma nova branch e mudar para ela
~~~
git checkout -b <nome da nova branch>
~~~

Comando para mesclar as alterações de uma branch para a branch atual
~~~
git merge <nome da branch>
~~~


### Histórico de commits
Comando para exibir o histórico de commits
~~~
git log
~~~

Comando para mostrar estatísticas de alteração (quais arquivos foram modificados) para cada commit
~~~
git log --stat
~~~
