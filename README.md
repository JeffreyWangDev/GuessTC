# Guess the Color

This project is a simple web-based game where players guess the resulting color by mixing four different colors.



## How to Run

1. **Clone the repository**:
    ```sh
    git clone https://github.com/jeffreywangdev/GuessTC.git
    cd GuessTC
    ```

2. **Build and run the Docker container**:
    ```sh
    docker build -t guess-the-color .
    docker run -p 80:80 guess-the-color
    ```

3. **Open your browser** and navigate to `http://localhost` to play the game.

## How to Play

1. Select four colors from the palette.
2. Click "Enter" to see the resulting color and how close it is to the target color.
3. Repeat until you guess the correct color or run out of attempts.

Enjoy the game!