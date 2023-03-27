# Learn Flutter

## Modulo Dart

### Identificadores
São os nomes dados as variaveis, funções, programas, etc...

  - Não pode conter número no começo, deve conter outro dígito;
  - Não pode conter espaços;
  - Pode possuir os caracteres: `$`, `_` e nem palavras reservadas;

Em contra partida ao Java o dart não possui as palavras reservadas: `protected`, `public` e `private`.
  -  Se ela for privada ela contera o underline no começo de seu nome:
    ```dart
    class Person {
      int _cpf;
    }
    ```

### Tempos de Amarração 
O identificador `var` faz inferencia (palpita o tipo da variavel)