In this project, I created an interactive graphical racing game using Python's turtle module. 
I applied Object-Oriented Programming (OOP) principles to dynamically instantiate and style multiple turtle objects. 
The program utilizes GUI text prompts for user interaction, the random module to generate unpredictable movements, 
and coordinate system boundaries to accurately detect the winner of the race.

# Graphical Turtle Race Game (Python)

An exciting, interactive graphical game built using Python's native `turtle` graphics framework. Users can place a bet on their favorite color, 
watch 6 turtles race dynamically across the screen, and see the final result outputted straight to the console.

## Features
* **Graphical User Interface (GUI):** A pop-up prompt allows users to type in their bet directly into the game window.
* **Object-Oriented Design:** Dynamically instantiates 6 unique turtle objects with different color themes.
* **Randomized Racing Mechanics:** Uses pseudo-random distance increments so that every single race has a unpredictable outcome.
* **Win/Loss Validation:** Checks the winner against the user's initial bet and displays a personalized feedback message.

## Technical Concepts Used
* **Turtle Graphics:** `Screen` customization, dimensional setups (`setup`), and absolute coordinate movements (`goto`).
* **State Management:** Uses boolean flags (`is_race_on`) to control when the animation loop starts and stops.
* **List Management:** Loops over lists to construct multiple objects and update their parameters dynamically.

## Preview Screenshot / Concept
```text
[ Pop-up Prompt: "Which turtle will win from the given colors?" ]
-> User inputs: "blue"
[ Window opens: Red, Orange, Yellow, Green, Blue, and Purple turtles race to the right ]
-> Console Output: "You've won! The blue turtle is the winner!"
```
