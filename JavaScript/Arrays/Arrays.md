# Arrays em JavaScript

São estruturas de dados com "espaços" que podem ser acessados e manipulados de diferentes formas.
Eles nos ajudam a lidar com dados "parecidos", listas, conjuntos, etc.

Exemplos: 
- lista de filmes
- lista de usuários

```javascript
const ingressos = ["Sexta", "Sabado", "Domingo", "Segunda"]

// ou

const ingressos = new Array("Sexta", "Sabado", "Domingo")

// Acessando os elementos dentro do Array

alert(ingressos[0])

// A Saída será Sexta

ingressos.lenght // Tamanho do Array
ingressos.sort() // Ordena o Array
```

# Operadores de um Array

Operadores ajudam a manipular Arrays de forma eficiente para fazer uma série de ações:

- Deslocar membros
- Acrescentar membros
- Clonar
- Quebrar em partes

```javascript
// O PUSH serve para inserir um novo valor no final do Array
ingressos.push("Terça")

// UNSHIFT insere um valor no começo do Array 
ingressos.unshift("Quarta")

// POP retira o ultimo elemento
ingressos.pop()

// SLICE cria uma cópia de um array
ingressos2 = ingressos.slice()

// INCLUDES serve para verificar se em um Array tem algum valor
ingressos.includes("Sexta") // se esse valor existir nesse Array, então irá retornar TRUE

// INDEXOF retornar a posição de um valor
ingressos.indexOf("Sexta")

// SPLICE serve para adicionar ou deletar valores em um Array
// Nesse caso, o primeiro paramêtro refere-se a posição do Array, nesse caso, a partir da posição 2
// O segundo paramêtro refere-se a quantidade de valores que é pra excluir, nesse caso, 0
// Os outros parametrôs serão adicionados
ingressos.splice(2, 0, "Indisponivel", "Disponivel")

// exemplo deletando itens
ingressos.splice(2, 2)
```
