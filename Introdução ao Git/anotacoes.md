# Comandos para iniciar um repositório no Git através do terminal:desktop_computer: 

**Windows**  

Abrimos o terminal, criamos uma pasta exemplo `workspace`, abrimos essa pasta para facilitar iniciamos o `Git Bash` dentro dela, com o bash aberto na pasta, criamos outra pasta com o comando `mkdir nome da pasta`, vamos cria um arquivo `markdown` nome do `arquivo.md`.

Para mover este arquivo para a pasta que criamos usamos o comando `mv arquivo.md ./ nome da pasta`, digite Ctrl l para limpar o terminal, `gi add nome do arquivo`, e vamos criar um commit, `git commit -m "criar pasta"` um git status para verificar se temos alguma pendência.

**Linux**:penguin: 

No Linux vamos iniciar no terminal, abrindo a pasta `cd "nome da pasta"` podemos criar outra pasta dentro dessa em que estamos para ,mover nossos arquivos, mesmos comandos descritos acima porem temos que iniciar o Git através do comando `git init` isso serve para os dois sistemas operacionais. 

Após iniciar o `git init`no seu termina você tem que configurar seu nome e email, igual está no seu GitHub, com os comando `git condig --global user.name "nome", ` `git config  --global user.email "email"`para verificar use `git config --list --schow-origin`, Git Bash é um terminal estendido para otimizar o uso do Git.





# Comandos:keyboard:

**git init** = Isso cria um subdiretório `.git`contendo todos os seus arquivos.

**git add** = Inicia um controle de versão dos arquivos e começa a rastrear os arquivos.

**git commit -m** = Inicia o projeto de versionamento, commit inicial.

**echo > README.md** = Adiciona um arquivo índex.

**git add *** = Adiciona tudo o que está na área de trabalho.

**ls** = Verifica se as mudanças foram feitas. 

**git add README** = Adiciona o arquivo README.md.

**git status** = Verifica se os arquivos estão sendo rastreados, se tem alguma pendência.

**Ctrl + L** = Limpa o terminal.

**mv** = move o arquivo para a pasta `mv arquivo.md ./ nome da pasta`.

Alguns comandos para usar através do terminal, na próxima atualização vou passar mais comandos de como clonar um repositório no GitHub e seus comandos, porém para uma melhor compreensão leia o livro e assista os videos da DIO, **introdução ao Git e ao GitHub**, **criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso** .

# Lista de tarefas:bookmark_tabs: 

- [x] git init
- [x] git add
- [x] git commit
- [x] git ststus
- [x] mkdir
- [x] Git comandos
- [ ] GitHub comandos
- [ ] git clone
- [ ] git remot  add origin
- [ ] git remote -v
- [ ] git push origin master





# Referências 



Links para o curso Introdução ao Git e ao GitHub:(https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9?back=/track/localiza-net-developer-2)

Link para o curso Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso :(https://web.dio.me/project/criando-seu-primeiro-repositorio-no-github-para-compartilhar-seu-progresso/learning/a6e285fa-b9a0-4bc2-8353-7b729dabcf0c?back=/track/localiza-net-developer-2)

Link para download do Git :(https://git-scm.com/downloads) 

