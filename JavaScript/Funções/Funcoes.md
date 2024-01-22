# Funções

Funções são parcelas de código que podem ser parametrizadas, ou seja, que podem ser chamadas em diversas partes do código.

### Vantagens:
- Código legível
- Manutenção do código melhor
  - Possibilidade de corrigir o código em somente um local do projeto
- Repetibilidade
  - Refere-se a reutilização do código

### Exemplos de funções:

```javascript
function nomeFuncao(parametro1, parametro2) {
    return parametro1 + parametro2;
}
```

Exemplo de função que estiliza bordas:

```javascript
function addRedBorder(id) {
    element = documento.querySelector('#' + id);
    element.style.border = "5px solid red";
}

// Chamando a função
addRedBorder("id")
```
