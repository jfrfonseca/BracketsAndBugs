# Brackets&Bugs
Brackets &amp; Bugs (B&amp;B, obviously) is a tabletop-role-playing-game in wich teams play as Information Technology Adventurers to crawl through Brackets and fight Bugs, Issues and Difficulties in the mythical land of Projects.

## Game Mechanics
### Players
Players instantiate themselves as IT_Adventurer's: multiple-inheritance objets of the many subclasses of the Developer class.
Each class grants an IT_Adventurer instance a different range to set values for the same few attributes.
Those attributes are:
  * Average Work Time per Function Point: A sequence of tuples, each with two double-precision values. The first value in each tuple is the bell-curve frequency of the second value, that is a quantity of time in work hours.
  ** Example: [(50, 3), (25, 8), (20, 12), (5, 24)]
  * Tool Affinity: A set of equipmen... er, I mean, "tools" and technologies chosen by the player for the IT_Adventurer to be familiar with. The size of the set is determined by the class, and so are the options to fill it. Each Tool grants its master some Attribute boosters.
  * Work-hour cost: AKA wages, AKA salary, AKA the amount of money the IT_Adventurer makes by the hour. There are a minimum and a maximum value, determined by the class, for the Work-hour cost of the IT_Adventurer.
  * Money: The amount of money that the IT_Adventurer owns and is immediately available. Is an integer number within a range determined by the class. If the amount of money an IT_Adventurer owns fall outside of the class limits, the IT_Adventurer must apply the excess money, or drop classes and/or attributes until an acceptable value is within limits old or new.
  * Skills: Arguably the most important Attribute, the set of Skills chosen by the Player among the ones provided by the class.
  * Skill Points: The initial number of skill points for the player is defined by the class, and can be traded for skills within the skills allowed by the class. During the gameplay, money can be traded by new skill points for a IT_Adventurer.
  * Specials: A set of special effects provided by a class to its instances.
