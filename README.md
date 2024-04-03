In this assignment, a battle system between two characters - an Orc and an Elf - is created. Each character has its own level, health points, attack power, and defense.
The following functionality is added:
- After the battle, the level of the winning character increases by 1, but not more than 3. This is achieved by calling the `level_up()` method when the battle ends in the `fight` function.
- The maximum level of a character is limited to 3.
- When a character levels up, their health is restored by half of their maximum health points. This logic is implemented in the `level_up()` method of the `Character` class.
These changes add new elements to the battle system and provide additional depth to the game by allowing characters to develop during combat.
