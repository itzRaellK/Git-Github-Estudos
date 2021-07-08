

## Guia de sobrevivência do Git (Socorro!)

- O que é um **repositório?**

  Basicamente é um local onde todos os códigos de um software (de um projeto) são armazenados. Funciona, de certa forma, semelhante a "arquivos em um HD". Os repositórios são mandados geralmente para servidores especializados como o Github, por exemplo, levando em consideração pontos importantes tais como segurança, organização, performance e manutenção.

   

  - [x] Primeiro passo, criar um **repositório local**:

    - Escolha uma pasta para o seu projeto e o acesse pelo terminal (git bash, vscode com terminal integrado, etc.)

    - Estando no diretório do seu projeto, use o comando:

      ```
      $ git init
      Initialized empty Git repository in C:/projeto-estudo-curso/.git/
      ```

  

  - [x] Segundo passo, **executar os comandos** para preparar o futuro envio do **repositório local**:

    - Via terminal, use o comando abaixo para adicionar "no radar do git" todos os arquivos no diretório em que se encontra:

      ```
      $ git add *
      ```

    - É bom ressaltar que conseguimos adicionar arquivos específicos de acordo com nossas necessidades, por exemplo:

      ```
      $ git add README.md
      ```

    - Somente um exemplo para que fique fácil a visualização. Seguindo com os passos, **commit** e dê uma referência (ou um nome) para especificar qual é aquele **commit**:

      ```
      $ git commit -m "Primeiro commit"
      ```

      

  - [x] Terceiro passo, criar um **repositório remoto** (o servidor ficará ao seu gosto igualzinho ao sal):

    - No meu caso, criei um repositório remoto no Github. Não é nada complexo, no próprio site, você obtém de forma fácil e objetiva como proceder para continuar com o processo. De forma resumida, você deve criar um repositório, dando-lhe nome e configurando de acordo com sua necessidade.

    - Logo depois, copie o link que usará para **sincronizar** o **repositório remoto** com o seu **repositório local**.

    - Em seguida, com esse link em mãos, você executa o seguinte comando no seu terminal:

      ```
      $ git remote add origin git@github.com:itzRaellK/teste123testando.git
      $ git branch -M main
      $ git push -u origin main
      ```

      
