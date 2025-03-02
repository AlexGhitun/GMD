# GMD
This repository holds all the GMD assignments that I will make.

## Development Blog

### Roll-a-ball (03/03/2025)

This project is the first assignment received from the GMD course which involves following the Unity tutorial for creating a game where the player is the ball and tries to get collectibles while avoiding enemies.
This being the first time I use Unity it took not that much time to get used to its functionalities and to start understanding its capabilities. Overall I am excited about the posibilities of creating games and trying new things to see how the engine runs.

In the beginning, it was interesting to see how the objects get created within a game and scripts are written to let the user input actions to move their object. Creating different materials and the playground where the player is allowed to move gave me a lot of insight as to how much customizability there is for a developer when making a game.

After creating the player object and the playground, next step was to add the collectibles. These would be spinning in place with the help of a script, but one of the issues I didn't expect was having to make them dissapear after the player would collide with them, while also increasing a counter to represent how many collectibles were gathered. This was an interesting aspect as I assumed that there would be just a function within Unity to be able to do without the help of a script, but regardless it wasn't that difficult.

The system with tags in Unity makes it really easy to be able to detect different actions and interactions between the player and different objects. This was used for detecting collision between the player and the enemy and for making the enmy dissapear after the player collects all the collectibles. The text for the winning screen and losing screen were pretty easy to figure out, but I still need to learn a bit more about how the Scene works in Unity to be able to easier interact with the game objects.

Finally, I added the victory text once all 8 cubes were picked up and added a few obstacles such as walls, pillars, ramps and moveable cubes around the playground so that it would be a bit more difficult for the player to get every collectible. This turned out to also mess with the AI of the enemy movement as it would not detect the objects the first time around, and later on having to modify how high the enemy can climb surfaces and at which angle so that it would properly follow the player and not go through objects.

There are still a few issues I am trying to improve before adding new features, one of them being related to the shadows not being loaded properly when the player is moving across the playground and the AI pathing not always climbing on surfaces the right way(climbing ramps from the side).

Next features to implement for the game:
Obstacles in the course that move which upon collision with the player would toss the player around the playground, I need to take into consideration enemy behaviour
Extra level that could be a follow-up to the already existing one
Power-ups, such as freeze enemies, that could spawn on the playground at random times and places 
Timer mode, which could have an amount of time to complete each level, otherwise the player would lose (this feature could also be just an addition to add a timer in the UI for the user to be able to compare with previous runs)
