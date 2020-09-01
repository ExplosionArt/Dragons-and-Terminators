# Dragons and Terminators
 Course Project for Python and OOP Concepts - 10xiitian IB Hubs.
 
 Dragons vs Terminators is a tower defense game where the goal is to defend the Dragon's territory by obstructing the Terminators.
 
 ## Storyline of the game
 - The Terminator Robots are trying to steal the Dragon Eggs and the heart of the Dragon King
 - Dragons win if all the Terminators are destroyed
 - Terminators win if they reach the end of the tunnel or kill the Dragon King
 - You are expected to place different types of Dragons in the path to protect the Dragon Colony and destroy the Terminators!
 
## Dragon Descriptions
| Dragon | Food Cost | Armor | Damage | Description |
| ------ | --------- | ----- | ------ | ----------- |
| Harvester Dragon | 2 | 1 | 0 | A Harvester Dragon add one food to the colony in every time unit. |
| Thrower Dragon | 3 | 1 | 1 | A Thrower Dragon that throws stones and damages the first Terminator in front of it that is still not in the Skynet. |
| Long Thrower | 2 | 1 | 1 | A cheaper version of Thrower Dragon that throws stones and damages the first Terminator in front of it that is still not in the Skynet and is atleast 5 places away from it's position.|
| Short Thrower | 2 | 1 | 1 | A cheaper version of Thrower Dragon that throws stones and damages the first Terminator in front of it that is still not in the Skynet and is atmost 3 places away from it's position. |
| Fire Dragon | 5 | 3 | x | A special type of Dragon which does damage when it recieves damage. If it is damaged by 'x' armor units and does not die, it does a damage of 'x' armor units to all the terminators in it's place(reflected damage). If it dies, it does an additional amount of damage, which is by default 3. |
| Hungry Dragon | 5 | 3 | x | A Hungry Dragon will select a random Terminator for it's place and eat it whole. After eating a Terminator, it must spend 3 turns digesting before eating again. If no terminator is available, it does nothing. |
 
