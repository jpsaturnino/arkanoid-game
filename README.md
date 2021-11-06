# Arkanoid Game

## About the Project
"Develop the classic game called Arkanoid. The concepts of OOP and JavaFX should be used"

## Game components

- <strong>Ball:</strong> there are a finite number of balls, they move vertically (up and down) and diagonals, it is the main object of the game, it has the mission of destroying the blocks, when the lines are exhausted, the game is finished.

- <strong>Racket:</strong> has the objective of hitting the balls, moves to the right and left, according to the user's actions (keyboard and / or mouse).

### Blocks: have different behavior and different colors
- *Yellow:* stays in a static position, is destroyed with a single collision. <br>
- *Green:* remains static until the first collision, then descends to a height close to the racket and moves continuously, left and right, until it receives a second collision with the ball. <br>
- *Blue:* when the collision with the ball occurs it is destroyed and a second ball is generated, with a horizontal direction opposite to the current ball <br>
- *White:* every time the ball hits a white block it is destroyed and the ball gains twice the speed for 15 seconds, then returns to normal speed <br>

## Video Preview
https://drive.google.com/file/d/1ZI1fkQpIKXtAJoHvoQxPiZJKfPSsy4_z/view?usp=sharing

## Participants
[mariaclara-rs](https://github.com/mariaclara-rs)
<br>
[rxngui](https://github.com/rxngui)
