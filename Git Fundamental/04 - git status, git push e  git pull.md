## git status, git push e  git pull

​	Para manter os arquivos locais atualizados e saber quais arquivos estará enviando para o **repositório remoto**, utilizamos alguns comandos que facilitam o controle de versão. 

- O primeiro é **git status**. Esse comando retornará uma lista com todos os arquivos que foram **modificados**, **adicionados** e que estão em estado de **untracked**.

  ```
  $ git status
  ```

- O segundo comando é o **git push**. Com ele você empurra seus arquivos locais para o **repositório remoto**, salvando assim no servidor dedicado de sua escolha, por exemplo, Github, Bitbucket, GitLab e etc. Deve se levar em conta que você deve usar o "apelido" que deu para o seu link (normalmente se coloca origin, por convenção) seguido da branch em que está trabalhando, nesse exemplo é a **main**.

  ```
  $ git push origin main
  ```

- O terceiro comando é o **git pull**. Esse comando irá trazer o **repositório remoto** para o seu **repositório local**. É usado esse comando em casos onde **repositório remoto** tenha alguma atualização ou modificação.

  ```
  $ git pull
  ```

  
