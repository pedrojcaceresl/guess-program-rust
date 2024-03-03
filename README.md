# Guessing Game in Rust

Welcome to the Guessing Game in Rust! This simple console-based game allows you to guess a series of random numbers. The game generates a specified number of random integers between 1 and 100, and your goal is to guess each one correctly.

## How to Play

1. **Clone the Repository:**

    - Clone this repository to your local machine using the following command:
        ```bash
        git clone https://github.com/pedrojcaceresl/guess-program-rust.git
        ```

2. **Navigate to the Project:**

    - Change into the project directory:
        ```bash
        cd guessing-game-rust
        ```

3. **Run the Game:**

    - Build and run the game using the following command:
        ```bash
        cargo run
        ```

4. **Enter the Number of Guesses:**

    - Upon starting the game, you will be prompted to enter the number of random numbers you want to guess.

5. **Make Your Guesses:**

    - For each random number, enter your guess when prompted. The game will inform you if your guess is too high, too low, or correct.

6. **Continue Guessing:**

    - If there are multiple numbers to guess, the game will prompt you to guess the next one until you've completed all guesses.

7. **End of Game:**
    - After all guesses are made, the correct answers will be revealed, and the game will thank you for playing.

## Dependencies

This project utilizes the `rand` crate for generating random numbers. Make sure to include it in your `Cargo.toml` file:

```toml
[dependencies]
rand = "0.8.4"
```

## Contribution

If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request. Your contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
