# Protocolo HTTP

Permite a obtenção de recursos, como documentos HTML. É a base de qualquer troca de dados na web e um protocolo cliente-servido.

# Fetch
Metôdo do javaScript pra fazer requisições HTTP assíncronas.

```javascript
// Exemplo

function getProduct() {
    fetch('http://localhost:3000/produtos')
        .then((response) => response.json())
        .then( (dados) => {
            var list = document.getElementById("product-list")
        })
}

getProducts();

```

 