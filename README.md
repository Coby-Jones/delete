# Bingo!

![Parse](Spaceship.png)

This is an online bingo game. Here is the data diagram:

## APIs
[Join Game](README.md#join-game)


[Anti Up](README.md#anti-up)


[Draw Cards](README.md#draw-cards)

## Join Game
This API allows user to join game, it uses the "get" HTTP method.

Sample Call:
``` HTTP
HTTP://bingo.com/api/joingame?name=Coby

```

This allows a player named Coby to join a game.

Sample Responce
```javascript
{"status": "success"}
```
Sample Error
```javascript
{"status": "fail, player is not old enough"}
```



## Anti Up

## Draw Cards
