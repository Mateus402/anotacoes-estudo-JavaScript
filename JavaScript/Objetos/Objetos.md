# Objetos em JavaScript

Objetos permite guardar as informações como um Array, porém, os objetos permitem nomear as informações guardadas:

```javascript
let amigo = {
    nome: 'Mateus',
    sexo: 'Masculino',
    peso: 80
}
```

Também é possível inserir uma função dentro do objeto:

```javascript
let amigo = {
    nome: 'Mateus',
    sexo: 'Masculino',
    peso: 80,
    pesagem(pesoAtual) {
        console.log('Nova pesagem realizada')
        
        //O this serve para acessar um objeto detro desse objeto
        this.peso = pesoAtual
    }
}
```

Para deletar ou adicionar algum objeto:

```javascript
// Adicionando objeto:

amigo.idade = 31

// Deletando objeto

delete amigo.idade

```

Pode haver também um Array dentro de um objeto:

```javascript
let amigo = {
    nome: 'Mateus',
    sexo: 'Masculino',
    peso: 80,
    irmaos: ['Stefhani', 'Eduardo']
}
```

E pode também, ter um objeto dentro de um array:
```javascript
var selecao = [
    {
        nome: 'Neymar',
        funcao: 'Atacante'
    },
    {
        nome: 'Robinho',
        funcao: 'Meio Campo'
    },
    {
        nome: 'Rogério',
        funcao: 'Goleiro'
    }
]

// Exemplo de print para esse array

console.log(selecao[2].nome)

// Saída esperada
Rogério
```

