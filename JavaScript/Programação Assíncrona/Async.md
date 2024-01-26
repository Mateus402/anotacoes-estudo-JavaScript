# Programação Assíncrona

Programação assícrona é basicamente as funções que não são executadas necessáriamente uma após a outra. 

### Promise
Um objeto que representa o resultado futuro de um comando assíncrono. É basicamente uma promessa do que vai acontecer.
Existem metodos que pode ser usado como promise:
- then() - Ela vai ser executada quando a promise for aceita, ou seja, quando deu certo.
- Catch() -  Quando algo da errado ele lança uma exceção e o Catch é executado.
- Finally() - recebe uma função de callback, ela é executada no final independente do resultado.

### Callback
Quando uma requisição é finalizada existe uma função de callback, que determina o que é pra fazer dependendo do resultado do comando.

### Async
É usada na definição de uma função que contenha alguma expressão que retorna uma Promise. Ou seja, quer dizer que a função é assíncrona.

### Await
Palavra chave usada antes de uma expressão que retorna uma Promise, dessa forma a função definida com a palavra ASYNC irá aguardar a resolução da Promise.

### SetTimeout
Define o tempo que vai levar para algo acontecer. Ex: em um chat quando você fica um determinado tempo sem interagir, o chat irá encerrar. Ou em casos de autenticação.
Exemplo prático:

```javascript
// O tempo é em milisegundos, e o primeiro parametro é a função
const myTymeout = setTimeout(myGreeting, 5000);
```

Obs: para encerrar um timeout utilizasse clearTimeout.

```javascript
function stopFunction() {
    clearTimeOut(myTimeout)
}
```