## Primeiros conceitos sobre Tag e Branch

É preciso entender que o Git passou por uma transição que passou a permitir a mudança de Branchs nos projetos. Isso pode gerar conflitos se o Dev não souber em qual Branch fazer o commit, gerando assim algum imprevisto que poderia ser facilmente contornado.

- Para criar uma tag no Git é só executar o comando "git tag" especificando uma versão para o projeto e facilitando na hora de identificar qual tag seria aquela.

  ```
  $ git tag -a v1.0 -m "minha versão 1.0"
  ```

- Usando apenas "git tag", será retornado uma lista com todas as tags criadas. Exemplo:

  ```console
  $ git tag
  v0.1
  v1.3
  v1.4
  ```

- Usando o comando "git show" você consegue ter acesso aos dados da tag junto com o commit onde ela foi realizada. Exemplo:

  ```
  $ git show v1.0
  tag v1.0
  Tagger: Israel Kessler <israel-kessler@hotmail.com>
  Date:   Sun Jul 04 14:50:01 2021 
  
  minha versão 1.0
  
  commit ca85b5dff817ec66f33231226503769b93762943
  Author: Israel Kessler <israel-kessler@hotmail.com>
  Date:   Sun Jul 04 14:56:11 2021 
  ```

- O comando "git checkout" é usado para se movimentar pelas Branchs de um projeto.

  ```
  $ git checkout main
  Switched to branch 'main'
  Your branch is up to date with 'origin/main'.
  ```

  Também é possível criar outras Branchs a partir do "git checkout" **porém, essa não é sua real função.**

  ```
  $ git checkout -b nova-branch
  Switched to a new branch 'nova-branch'
  ```

  