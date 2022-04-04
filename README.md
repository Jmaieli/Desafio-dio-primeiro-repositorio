# Desafio-dio-primeiro-repositorio
Desafio de projeto sobre Git/GitHub

# Criando meu primeiro repositório no Git/GitHub
**O que é o Git/GitHub?**: 
 Git e Github são utilizados no dia a dia das pessoas que criam software pois tem uma forma fácil de gerenciar as versões do código fonte da aplicação, do sistema/produto de forma distribuida e segura.
 Já que muitas vezes os códigos são modificados de forma simultanea por diversos devs é necessário conseguir garantir o histórico dessses *commits*, para em caso onde seja necessário voltar a trás e recuperar algum trecho ele esteja lá.
 
 
# **Comandos basicos no Git/Github:**
## **CONFIG**
***O que é o comando config?***
Esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada commit.

Exemplo:
Os comandos do git sempre devem ser escrutos da seguinte folma:
 ***Git config***
$ git config –global user.name “Seu nome”

$ git config –global user.email “Seu email”

## **INIT**
***O que é o comando init?***
É utilizado para criar um novo projeto no git. O comando cria um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvar guardar as alterações etc.

Exemplo:
Os comandos do git sempre devem ser escrutos da seguinte folma:
 ***Git init***
 
Se você já possui um repositório anterior ou deseja criar um repositório com um nome em específico, você pode passar o nome como parâmetro do comando:

$ git init < nome do seu repositório>

## **CLONE**
***O que é o comando clone?***
Esse comando Git cria uma cópia exata de um repositório já existente que estão remotas no git para nossa máquina local.

Então… quando usar git init e quando usar git clone? O git clone é mais avançado, uma vez que ele mesmo executa um comando git init internamente. Além disso, ele verifica todo o conteúdo do projeto.

Exemplo:

git clone <URL do seu projeto> (URl do projeto que temos no git).

## **ADD**
***O que é o comando add?***
 Adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados. Oferece diferentes formas de sintaxe.

Exemplo:

$ git add seu_arquivo (esse comando irá adicionar o arquivo em específico ao repositório)

$ git add * (esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório)

## **COMMIT**
***O que é o comando commit?***
 
 É importante sabermos a diferença entre git add e git commit:

git add adiciona seus arquivos modificados à fila para serem submetidos a um commit posteriormente. Os arquivos não passaram por um commit.

O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. Por outro lado, se você não adicionar nenhum arquivo, o git não fará o commit de nada.
É possível combinar as duas ações em um único comando: $ git commit -a.

Também é possível adicionar uma mensagem para a execução de um commit. Exemplo:

$ git commit -m “seu comentário”

## **BRANCH**
***O que é o comando branch ?***
É comum na maior parte do tempo possuir múltiplas variações em seu repositório Git, chamadas de branches (“ramificações”). A grosso modo, um branch é um caminho independente de desenvolvimento, uma alternativa.

A princípio pode parecer fácil se perder em diversos caminhos, mas o comando git branch facilita o gerenciamento de tudo isso. Com diferentes parâmetros, é possível listar, criar ou apagar as branches.

Exemplos:

$ git branch (lista todas as ramificações)

$ git branch <nome_do_branch> (cria um branch com o nome especificado)

$ git branch -d <nome_do_branch> (deleta o branch com o nome especificado).

## **CHECKOUT**
***O que é o comando checkout ?***
Ainda sobre branches, esse comando Git pode ser utilizado para trocar de uma ramificação para outra.

Exemplo:

$ git checkout <nome_do_branch>

Também é possível combinar operações, criando e fazendo o checkout de um novo branch com um único comando:

$ git checkout -b <nome_do_branch_novo>

## **REMOTE**
***O que é o cimando remote ?***
O comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.

Exemplo:

$ git remote add <nomecurto> <url>

## **PUSH**
***O que é o comando push?***
Esse comando serve para subir suas modificações para um repositório remoto conectado anteriormente com git remote.

Exemplo:

$ git push -u <nome_curto> <nome_do_branch>

É importante especificar a origem e o upstream antes de usar o git push. Veja o exemplo:

$ git push –set-upstream <nome_curto> <nome_do_branch>

## **FETCH**
***O que é o comando fetch?***
Quando você precisa baixar as mudanças criadas por outros membros do seu projeto colaborativo, você precisa do comando Git fetch. A partir desse comando, você irá receber todas as informações de commits, para avaliar, antes de aplicar essas alterações na sua versão local do repositório.

Exemplo:

$ git fetch

## **PULL**
***O que é o comando pull?***
O comando Git pull baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu contreúdo para a última versão.

Exemplo:

$ git pull <URL>

## **STASH**
***O que é o cimando stash?***
Armazena temporariamente seus arquivos modificados em uma área chamada stash (“esconderijo”), sem interagir com os outros arquivos até ser necessário.

Exemplo:

$ git stash

Para listar todos os seus “esconderijos”, usamos:

$ git stash list

Quando for o momento de aplicar o conteúdo do stash a um branch, usamos o parâmetro “apply”:

$ git stash apply

## **SHOW**
***O que é o comando show?***
Quer detalhes específicos sobre um commit que o log não mostra? O comando Git show é a resposta.

Exemplo:

$ git show <hash_do_commit>

## **RM**
***O que é o cimando rm?***
Para remover arquivos da sua pasta, você pode utilizar o comando Git rm.

Exemplo:

$ git rm <nome_do_arquivo>

## **HELP**
***O que é o comando help?***
Existem inúmeros comandos no Git, muito mais do que os 25 dessa lista, cada um com sua função, parâmetros e características. Felizmente, o próprio Git tem o comando help para trazer ajuda diretamente no terminal.

Exemplo:

$ git help <comando que se tem dúvida>

## **MERGE**
***O que é o comando merge?***
Integra as mudanças de dois branches diferentes em um único branch. Ele precisa ser iniciado a partir de um branch já selecionado, que será mesclado com outro, com o nome passado por parâmetro.

Exemplo:

$ git merge <nome_do_branch
.
Caso queiram saber um pouco mais sobre esse modele de arquivo (.md) que estamos usando para criar esse trabalho acesse o link a baixo,onde vocês encontarão tudo que precisan saber 
(https://www.markdownguide.org/basic-syntax)

Para aprender mais sobre o git acesse o link:
(https://www.youtube.com/watch?v=DqTITcMq68k)

