# LAB_FUNCTIONS_101


## Create a function that takes 1 parameter of type int , then it prints out the result formatted like the following patter (if we give it 5 for example):

**Example Output for `5`**
```
5 4 3 2 1   
4 3 2 1   
3 2 1   
2 1   
1   
```

#### Document the newly created function. describe what it does, then print the documentation. 


# Bonus

# Python Live Coding Challenge: Crack the Alien Vault 👽

Beginner–Intermediate

45–60 minutes

Functions 101

## The Challenge

An alien spaceship has crashed on Earth. Inside, scientists discover a mysterious vault containing advanced alien technology.

The vault is protected by a 4-digit secret code.

Your mission is to build a Python program that allows players to crack the code using clues.

But there's a catch: The vault never tells you which digits are correct!

## How the Vault Works

The secret code is *`4271`*.

When a player enters a 4-digit guess, the vault provides two clues:

- EXACT: How many digits are correct AND in the correct position.
- MISPLACED: How many digits are correct but in the wrong position.

## Your Mission

Create a Python program from scratch that:

1. Stores a secret 4-digit code.
2. Allows the player to guess the code.
3. Calculates the number of EXACT and MISPLACED digits.
4. Displays both clues after every guess.
5. Gives the player 6 attempts to unlock the vault.
6. Announces victory if the code is cracked, or failure when attempts run out.

Important: Digits can repeat in guesses. A digit in the secret code can only be matched once!

## Test Your Logic

Use secret code `4271` and verify that your functions produce these results:

| Player guess | EXACT | MISPLACED |
| ------------ | ----- | --------- |
| `4172`       | 2     | 2         |
| `2471`       | 2     | 2         |
| `4421`       | 2     | 1         |
| `1122`       | 0     | 2         |
| `0000`       | 0     | 0         |
| `4271`       | 4     | 0         |

Watch out for `4421` and `1122`. These are designed to catch mistakes in your logic!

## Programming Rules

- Use at least 3 functions.
- At least 2 functions must accept parameters and return values (one for counting correct misplaced guseses, one for counting exact guesses, and one for running the game).
- Don't put all the game logic inside one function.
- Use functions to divide the problem into smaller, reusable parts.
- You may use loops, conditions, strings, and basic Python operations.
- No external libraries or starter code.

You decide how to design and connect your functions.
