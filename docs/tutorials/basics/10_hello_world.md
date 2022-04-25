# Hello World

A primeira coisa que você precisa aprender em qualquer linguagem de programação é o famoso [`Hello World!`](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program).

Em Crystal isso é muito simples, talvez até um pouco chato:

```crystal-play
puts "Hello World!"
```

!!! tip
    Você pode compilar e executar exemplos de código interativamente neste tutorial clicando no botão "Run" (obrigado [carc.in](https://carc.in)).
    A saída é mostrada diretamente em linha.

    Se você quiser acompanhar localmente, siga as instruções em [Instalação](https://crystal-lang.org/install/) e [Começando em Crystal](../../getting_started/README.md).

!!! info inline end
    O nome `puts` é uma abreviação para  "*put string*".

Todo o programa consiste em uma chamada para o método ['puts'](https://crystal-lang.org/api/toplevel.html#puts%28%2Aobjects%29%3ANil-class-method) com a string "Hello World!" como argumento.

Este método imprime a string (e um caractere de linha nova) na [*standard output*](https://en.wikipedia.org/wiki/Standard_output).

Todo o código no escopo global (*top-level*) faz parte do programa principal. Não há função "*main*" explícita como [*entry point*](https://en.wikipedia.org/wiki/Entry_point) para o programa.
