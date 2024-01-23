# Event Listener ou Escutar um Evento

Pode ser adicionado um evento qualquer, como por exemplo, o clique do mouse.

```javascript
function addKeyBoardEventListener() {
    //primeiro paramêtro é o evento que deve ser "escutado"
    document.addEventListener('keydown', (event) => {
        alert("Clicou")
    })
}
```