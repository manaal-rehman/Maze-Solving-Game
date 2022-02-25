# Maze-Solving-Game

The task to be accomplished was to develop a game in C fulfilling following requirements:
1. It should present the player with options to try different doors.
2. If a door is open, player should find himself in the connecting room.
3. If the entered door number is invalid (e.g. the room only has 2 doors and the user enters 3), the user should get a message to ask him to enter a valid choice.
4. Upon entering the kitchen for the first time only it should print a messaging congratulating the player that he has successfully guided Ali to the kitchen.
5. Upon entering the bedroom after visiting the kitchen, it should print a message congratulating the player that he has finished the game successfully and return exit.

We were given a diagram displaying a map of available connections. First I made a FSM (Finite State Machine) and a flow chart for better understanding and finally I implemented the code in C language.
