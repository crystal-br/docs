# Getting started

Olá e boas-vindas ao livro de referência sobre Crystal!

Primero, tenha certeza de [instalar o compilador](https://crystal-lang.org/install/) para que possamos testar todos os exemplos neste livro.

Uma vez instalado, o compilador Crystal deve estar disponível com o comando `crystal`.

Vamos tentar!

## Crystal version

Se Crystal for instalado corretamente, podemos então checar a versão do compilador desta forma:

```console
$ crystal --version
--8<-- "crystal-version.txt"
```

Ótimo!

## Crystal help

Agora, se nós queremos listar todas as opções dadas pelo compilador, podemos executar apenas `crystal` sem nenhum argumento:

```console
$ crystal
Usage: crystal [command] [switches] [program file] [--] [arguments]

Command:
    init                     generate a new project
    build                    build an executable
    docs                     generate documentation
    env                      print Crystal environment information
    eval                     eval code from args or standard input
    play                     starts Crystal playground server
    run (default)            build and run program
    spec                     build and run specs (in spec directory)
    tool                     run a tool
    help, --help, -h         show this help
    version, --version, -v   show version

Run a command followed by --help to see command-specific information, ex:
    crystal <command> --help
```

Mais detalhes sobre como usar o compilador podem ser encontrados no *manpage* (`man crystal`) ou em nosso [manual do compilador](../using_the_compiler/README.md).

## Hello Crystal

O exemplo a seguir é o clássico "*Hello World*". Em Crystal é o seguinte:

```crystal title="hello_world.cr"
puts "Hello World!"
```

Podemos executar nosso exemplo desta forma:

```console
$ crystal hello_world.cr
Hello World!
```

!!! note
    Não há necessidade de definir uma função "*main*" ou algo semelhante. Crystal entende o programa inteiro como função principal.

Em seguida, você pode querer dar uma olhada no [Tour Introdutório](../tutorials/basics/README.md) para conhecer mais sobre a linguagem.

---

Aqui temos mais dois exemplos para continuarmos nossos primeiros passos em Crystal:

- [HTTP Server](./http_server.md)
- [Command Line Application](./cli.md)
