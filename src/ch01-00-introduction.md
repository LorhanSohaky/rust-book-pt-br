# Introdução

Seja bem vindo(a) ao “Linguagem de Programação Rust”, um livro introdutório sobre Rust.

Rust é uma linguagem de programação que ajuda você a escrever softwares mais rápidos e
confiáveis. A ergonomia de alto nível e o controle de baixo nível estão frequentemente em desacordo um com o
outro no design da linguagem de programação;Rust fica para desafiar isso.
Através do balanceamento de uma capacidade técnica poderosa e de uma excelente experiência de desenvolvimento,
o Rust oferece a opção de controlar detalhes de baixo nível (como uso de memória)
sem todos os problemas tradicionalmente associados a esse controle.

## Para quem é o Rust

Rust é indicado para varias pessoas por diversos motivos. Vamos falar alguns dos
grupos mais importantes.

### Times de desenvolvedores

Rust está provando ser uma ferramenta produtiva para colaboração entre grandes equipes de
desenvolvedores com diferentes níveis de conhecimento de programação de sistemas. Código de
baixo nível está propenso a diversos bugs sutis que na maioria das outras linguagens podem ser capturadas por
testes extensivos e revisão de código cuidadosa por programadores
experientes. No Rust, o compilador desempenha um papel de vigia, recusando-se
a compilar código com esses tipos de bugs - incluindo bugs de concorrência. Ao trabalhar
ao lado do compilador, o time pode dedicar mais tempo na
lógica do programação ao invés de caçar bugs.

Rust também traz ferramentas de denvolvimento modernas ao mundo de programação de sistemas:

* Cargo, o gerenciador de dependência e ferramenta de construção, torna a adição,
a compilação e o gerenciamento de dependências fácil e consistente em todo o
ecossistema Rust.
* O Rustfmt garante um estilo de codificação consistente entre os desenvolvedores.
* O Rust Language Server fornece integração à IDE para criação de código e
mensagens de erro embutidas.

Usando essas e outras ferramentas no escossistema Rust, os desenvolvedores podem ser
produtivos enquanto escrevem códigos em nível de sistema.

## Sobre a Tradução

Esta é uma tradução *não oficial* da [nova versão] do livro  “The Rust
Programming Language”. Várias porções desta tradução (assim como do original)
ainda estão incompletas. A [versão antiga] do livro (em inglês) ainda é a
leitura de referência recomendada da linguagem.

[nova versão]: https://rust-lang.github.io/book
[versão antiga]: https://doc.rust-lang.org/book

Sempre que possível, nos exemplos de código, optamos por usar nomes de
variáveis, funções e arquivos em português. Essa escolha foi feita para fins
didáticos, e se limita às porções de código de exemplo apresentadas. Os nomes
provenientes da biblioteca padrão da linguagem, bem como de *crates* já
existentes são mantidos no original em inglês, para que o código funcione
corretamente. (Ex: `Usuario` em vez de `User`, mas manteremos nomes como `Box`
em inglês). Para fins de compatibilidade, utilizaremos somente caracteres sem
acento e cedilha.

Apesar da escolha didática do livro, recomendamos que, ao escrever código “de
verdade” em Rust, utilize sempre que possível nomes em inglês, especialmente
para projetos *open source* a fim de tornar seu código acessível para uma maior
audiência.

## Contribuindo com o Livro

Este livro é *open source*. Se encontrar um erro, por favor não hesite em abrir
uma *issue* ou enviar um *pull request* [no GitHub]. Leia
[CONTRIBUTING-pt-br.md] para mais detalhes.

[no GitHub]: https://github.com/rust-br/rust-book-pt-br
[CONTRIBUTING-pt-br.md]: https://github.com/rust-br/rust-book-pt-br/blob/master/CONTRIBUTING-pt-br.md
