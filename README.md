# ui-game-console

Esta librería permite dibujar caracteres en la terminal de forma sencilla, además de manejar eventos del teclado.

### Dibujo de caracteres
```javascript
import { UI } from 'ui-game-console'

// crea un canvas de 8x8
const ui = new UI(8, 8)

// dibuja el caracter '#' en la posición (3, 5)
ui.printCharacter(3, 5, '#')
```

### Eventos del teclado
```javascript
import { UI } from 'ui-game-console'

// crea un canvas de 8x8
const ui = new UI(8x8)

// detecta el evento keypress
ui.screen.on('keypress', (char, key) => {
  console.log(key.name)
})
```