## Criando tags

​	Utilize o comando **git tag -a <nome> -m "<mensagem sobre a tag>"** para criar uma tag em uma branch do seu interesse. Criar tags em branch significa que você estará salvando um ponto do seu projeto. Como um **checkpoint**. Essa técnica é muito utilizada para demarcar estágios do desenvolvimento de algum recurso ou projeto.

Ex:

```
$ git tag -a v1.0 -m "Primeira versão"
```

Com o comando **git tag** apenas, você recebe de volta uma lista com suas tags no momento.

```
$ git tag
```

