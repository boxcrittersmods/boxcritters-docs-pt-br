# Mundo
A sessão atual aonde o jogador e a sala estão.

Paramêtro|Tipo
---|---
t|[HTMLCanvasElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement) \| [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) \| [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
e|[Socket](https://socket.io/docs/client-api/#Socket)
i|[object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)

## Propriedades
### .events
Tipo: [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
### .player
Tipo: [Player](/Player)
### .critters
Tipo: [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
### .items
Tipo: [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
### .stage
Tipo: [Stage](https://www.createjs.com/docs/easeljs/classes/Stage.html)
### .room
Tipo: [Room](/Room)
### .socket
Tipo: [Socket](https://socket.io/docs/client-api/#Socket)
### .chat
Tipo: [Chat](/Chat)
### .code
Tipo: [Code](/Code)

## Métodos
### .handleSocket(i, o)
Paramêtro|Tipo
---|---
i|[Socket](https://socket.io/docs/client-api/#Socket)
o|[World](/World)

Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .sendMessage(t)
Paramêtro|Tipo|Descrição
---|---|---
t|[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)|Message Text

Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .login(t)
Paramêtro|Tipo|Descrição
---|---|---
t|[object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)|Login Ticket

Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .logout()
Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .joinRoom(t)
Paramêtro|Tipo|Descrição
---|---|---
t|[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)|RoomID

Returns: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .addRoom(t)
Paramêtro|Tipo|Descrição
---|---|---
t|[object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)|Room Creation Data

Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .removeRoom()
Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .addMenu(t)

<div class="admonition attention">
    <p class="first admonition-title">Atenção</p>
    <p class="last">
        A função do paramêtro `t` não é usada aparentemente. Mas rocket snail pode provavelmente usa-lá em criações de Menu futuras.
    </p>
</div>

Paramêtro|Tipo|Descrição
---|---|---
t|[object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)|Unused in the function

Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
### .removeMenu()
Voltas: [void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
