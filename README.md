# Capysaur

Capysaur is a simple endless runner game inspired by the dinosaur game in Google Chrome that appears when you are offline. Instead of a dinosaur, the player controls a capybara that runs, jumps over bushes, and dodges flying birds for as long as possible.

The game was created for the **AWS Learning Club – Holy Angel University** as an interactive activity for students during organization events. It gives visitors at the booth a quick, fun way to play, compete for the high score, and engage with the club.

<!-- Add a screenshot: save it as docs/screenshot.png -->
![Capysaur screenshot](docs/screenshot.png)

---

## Versions

| File | Version | Description |
| --- | --- | --- |
| `capybara.py` | Classic | The original game with a natural theme |
| `capysaur-aws.py` | AWS Edition | A themed version with AWS-styled ground and clouds and the AWS Learning Club logo, made for club events |

Both versions use the same gameplay and controls.

## How to Play

- Press **Space** to start the game.
- Press **Space** to jump over bushes and avoid birds.
- The game gets faster as your score increases, and obstacles appear closer together.
- The game ends when the capybara hits an obstacle. Press **Space** to play again.
- Try to beat the high score.

## Controls

| Key | Action |
| --- | --- |
| Space | Start, jump, and play again |

## Features

- **Endless running:** The game continues until the player hits an obstacle.
- **Increasing difficulty:** Game speed rises as the score grows.
- **Accurate collisions:** Sprite masks are used so the capybara is only hit when the actual shapes touch, not just their outer boxes.
- **Saved high score:** The best score is saved to `highscore.txt`, so it stays even after the game is closed.
- **Sound effects and music:** Background music, a jump sound, and a game-over sound.

---

## How to Run

### Requirements

- [Python 3](https://www.python.org/downloads/)
- [Pygame](https://www.pygame.org/)

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/RandelYumul/Capysaur.git
   cd Capysaur
   ```

2. Install Pygame:

   ```bash
   pip install pygame
   ```

3. Run either version from the main project folder:

   ```bash
   python capybara.py
   ```

   or

   ```bash
   python capysaur-aws.py
   ```

> Run the game from the main project folder so it can find the `capy` folder, which contains the images and sounds.

## Project Structure

```
Capysaur/
├── capybara.py        Classic version
├── capysaur-aws.py    AWS Edition
└── capy/              Images, music, and sound effects
```

## Built With

- **Python**
- **Pygame**
