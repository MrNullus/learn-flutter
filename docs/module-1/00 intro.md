# Learn Flutter

## Modulo Dart


### O que é Dart?
Dart é uma linguagem de programação criada pela Google, por Lars Bak e Kasper Lund do Google Chrome (V8).
Criada para:
    - **Substituir** o JavaScript e o Java, sendo uma linguagem de script;
  
### O que tem demais?
Dart é uma linguagem voltada para a **Web**.

No **ecossistema** do Dart foi criado um framework para a criação de mobile apps híbridos, que visa progressivamente ir para 
a web.

Possui **desenvolvimento híbrido**:
    - Web
    - IOS
    - Android 


### Sobre a linguagem:
- Linguagem open-source, com uma licença: BSD;

- Possuindo influencia: Go, JavaScript, CoffeScript, etc;

- Os programas criados nessa linguagem podem ser executados tanto em uma maquina virtual (Dart VM), como compilado em JavaScript;

- Multiparadigma

- O SDK posssui um utlitario para fazer essa tradução do código equivalente a JavaScript para Dart Script;


### Suporte para desenvolvimento (IDEs)
Algumas boas IDEs para usar são:
- Eclipse
- WebStorm
- IntelliJ
- VS Code
- DartPad Online
- Replit


## Instalação 
- Para instalar siga a documentação: [https://dart.dev/get-dart](https://dart.dev/get-dart)
- Extensão dos arquivos: .dart
- Execução dos programas: 
  - Checked Mode: "-c" ou "--checked" |> egg: dart teste.dart
    - Auxilia nos warnings e errors;
    - Reforça várias verificações como a verificação de tipo e etc...;
  - Production Mode: Default |> dart teste.dart;

### Comentários
- `//` -> comentario inline;
- `/* */` -> comentario multline;


### Espaços em branco, ponto e virgula (;), quebras de linhas
- O Dart ignora espaços em branco e quebras de linhas
- O ponto e vírgula é usando obrigatoriamente no final de cada statements, ou seja, temrinal um comando coloque (;)


### Exemplo de Código
O Dart funciona como o C ele possui uma função principal, chamada `main` que será chamada assim que o programa for executado,
ou seja, todo o funcionamento do programa estará relacionado a essa função.

```dart
// Definição de uma função
void exibirMensagem(mensagem) {
    print(mensagem);
}

// Definição da função principal
void main() {
    exibirMensagem("HELLO WORLD!");
}
```