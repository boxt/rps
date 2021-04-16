![BOXT](https://bit.ly/3doa9mZ)

# Rock, Paper, Scissors Challenge

We would like you to implement a simple game of rock, paper, scissors against a computer that selects opposing gestures at random. The user needs to be informed of the result of that game and then able to reset the game to play again.


*This game should play out entirely on the frontend - no need to add any sort of backend or external API.*

*Please include tests for your code and a brief description of how you would continue to develop this application if you had more time to spend on it.*

## ⛰️ 🧻 ✂️ 

### Game logic
- `paper` beats `rock`
- `rock` beats `scissors`
- `scissors` beats `paper`

---
### BDD Acceptance Criteria

```
AS A Player
WHEN I click a gesture from the game logic
AND the gesture the computer picks is not the same as mine
THEN I see a message telling me who won (the player or the computer)
```

```
AS A Player
WHEN I click a gesture from the game logic
AND the gesture the computer picks is the same as mine
THEN I see a message telling me that the game was a draw
```

```
AS A Player
HAVING played a game
WHEN I reset the game
THEN the game is reset 
AND I can play another game
```

## ⛰️ 🧻 ✂️ 🦎 🖖

### Optional
extend the rules to include the `lizard` and `spock` gestures

#### Game logic
- `scissors` beats `paper`
- `paper` beats `rock`
- `rock` beats `lizard`
- `lizard` beats `spock`
- `spock` beats `scissors`
- `scissors` beats `lizard`
- `lizard` beats `paper`
- `paper` beats `spock`
- `spock` beats `rock`
- `rock` beats `scissors`

---



### 💅
Feel free to design the UI as you wish, however please remember we only want you to spend a few hours on this challenge.
