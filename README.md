# number_guessing_game

This repository contains code for a simple number guessing game which was written in Rust.  

The code is borrowed from  https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html

## Preview

    $ cd <project_root> 
    $ cargo run
        Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.05s
         Running `target\debug\guessing_game.exe`
    Guess the number!
    Please input your guess.
    500
    You guessed: 500
    Too big!
    Please input your guess.
    100
    You guessed: 100
    Too big!
    Please input your guess.
    50
    You guessed: 50
    Too big!
    Please input your guess.
    25
    You guessed: 25
    Too small!
    Please input your guess.
    30
    You guessed: 30
    Too big!
    Please input your guess.
    27
    You guessed: 27
    You win!

## Requirements

- rustc 1.84.0 (9fc6b4312 2025-01-07)

## Setup
The following instructions assume the user has Ubuntu as their local machine's OS. Most instructions should work for other Linux distributions as well, though mileage may vary.

### Step 1: Install Rust
Set up Rust (v1.84.0) on the local machine.

    curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
    
### Step 2: Clone the project
Clone this GitHub repository into the local machine.
    
    git clone --single-branch -b main <project_repo_url> <project_root> 
    
### Step 3: Resolve dependencies 
Install missing libraries required for running the project (if any).
    
    cargo build
    
### Step 4: Run the application
Run the application from the command-line.

## Usage
    
    cd <project_root>
    cargo run

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
