# Slot-Machine-Project

This is a simple slot machine game played inside the Terminal where the user can win on multiple rows.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Play the game by typing commands into the terminal
- Receive an output of
  - A visual display of the slots 
  - How much money they won
  - What lines they won on
  - Their current remaining balance
  - The option to play again if they have enough money

### Screenshot

![]()

## My process

### Built with

- Python
- Visual Studio Code
- PyCharm

### What I learned

While working through this project, some of my major learnings were defining my own functions where each one played an essential component in how the game represented slots. By implementing dictionaries that contained key-value pairs of symbol letters and values, I was able to utilize and apply them to the rows and columns of the slots. With the random library included, I was able to mimic the randomness that slots produce when they are spun each time.

```python
def print_slot_machine(columns):
  for row in range(len(columns[0])):
  #gives index as well as item
    for i, column in enumerate(columns):
      if i != len(columns) - 1:
        print(column[row], end=" | ")
      else:
        print(column[row], end="")

    print()
```

### Continued development

In future projects, I would focus on the concept of nested for loops as I had some issues with it during the start of my build when trying to connect the rows and columns of the slots. I would also want to see how I can further optimize my code and implement object-oriented programming practices.

## Author

### Danny Yu
