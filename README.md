# Cat-Chaos
CS 426 Final Project

[Design Document](https://docs.google.com/document/d/1CFu6U85XrUEFJIyIWUjvCOGbUwl8SkGE5plIKW824DA/edit?usp=sharing)

Team Members: Arlette Diaz, Nick Filipov, Diego Bravo

# Assignment 6
**Design and Rationale:** In our game "Cat Chaos", the cat (player) must avoid being caught while causing chaos in the house.
We used Mecanim and AI techniques, such as pathfinding and FSMs, to make the cat's owner patrol the house and chase the cat.
We also used waypoints to make a dog that patrols an area of the house. This will make the level difficult for the player to
cause chaos, which encourages them to be strategic.

### AI implementations:
- FSM on the Owner NPC - Nick Filipov
- Pathfinding on the Owner NPC - Diego Bravo
- Waypoints on the Dog NPC - Arlette Diaz

### Mecanim implementations:
- Owner NPC idle+walk - Nick Filipov
- Cat Player idle+walk - Diego Bravo
- Dog NPC idle+walk - Arlette Diaz

### Physics:
- Speed Boost Power Up (gives player cat more directional force for a duration on collision with power up object)
- Jump Boost Power Up (gives player cat more jump force for a duration on collision with power up object)
- Hinge Door (the owner's bedroom has a hinge door that swings open when the owner walks through it)

### Textures:
There are multiple textures used across the level, such as floor, door, and wall textures.

### Lighting:
There are multiple light sources used across the level, such as lamps.

# Assignment 5
[Assignment 5: Design Document, Tools, Sw Prototype and Level Design](https://docs.google.com/document/d/1FLa1F97W0JR0hCHbJc4M_DVPr4UKmouwLH6_qRgPJr4/edit?usp=sharing)
