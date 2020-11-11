# Exercício FizzBuzz em Elixir

Bom, estou aprendendo um pouco sobre Elixir e esse foi o probleme proposto a
mim.

## Explicação do Problema

* Múltiplos de 3 substituidos por "Fizz"
* Múltiplos de 5 substituidos por "Buzz"
* Múltiplos de 3 e 5 por "FizzBuzz"

### Exemplo:

``
[1,2,3,4,5,15] => [1,2, Fizz, 4, Buzz, FizzBuzz]
[1,2,4,8,10] => [1, 2, 4, 8, Buzz]
``

## Detalhe Importante
* Vamos ler a lista de números de um arquivo!
  * Caso o arquivo não exista, devemos exibir uma mensagem de erro para o
      usuário
