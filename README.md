# Bingo!

![Parse](Spaceship.png)
This is an online bingo game. Here is the data diagram:

## Team
Name | Email | Phone
--- | --- | --- 
John | J@bingo.com | (887) 647-2355
Sara | J@bingo.com | (335) 696-4749

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
