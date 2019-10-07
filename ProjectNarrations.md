# Requirements
* Emphasize design processes and show final designs or application
* Define skills/tools acquired in all your examples
* Submit one paragraph narrative per project

# Yggdrasil Wars
## About
*Yggdrasil Wars: Day's of Our Knights* is a game that was created for a group project class by a four-person team of Computer Science and Software Engineering majors. This group was comprised of Jake K., Ashley Y., Andrew M., and myself, Chandler D. The project's development took place over a period of a semester and won the prestige of Second Best Project in the class.

*Yggdrasil Wars* is an online multiplayer game played from the top-down viewpoint where the player must defeat monsters to earn points. These monsters continuously spawn, at different intervals, from castles that are randomly placed upon the game's initialization. These creatures are common fantasy fare, including: bats, spiders, and goblins. Each enemy type has unique characteristics to spice up the gameplay.

 Upon starting the game player is able to pick from a number of classes: Knight, Cavalry, Barbarian, Mercenary, and Rogue. Just like the enemies, each of these classes have unique characteristics and abilities. The Cavalry is very fast; the Barbarian can grow in size; and more! There are also locked chests and an unlocking minigame that you will just have to play for yourself.

## Skills Gained
One of the biggest skills acquired during the development of this game, was experience with the Javascript language. Before working on this project, I was the only team member who had prior experience with the language. Even so, it was just as much of a learning experience for me as it was for the other team members. On top of the Javascript syntax, we also gained extensive experience with the P5js library. This library provided a simple API for implementing the visuals of the game: sprites, textures, collisions, etc. The library also provided an API for playing sound. 

Since none of us had implemented real-time online functionality before, we had to learn a lot to get the game's multiplayer working. For this task, we relied on Node JS, specifically the Express module. This incorporated the use of NPM and the concept of dependency management. One of the take-aways of this project was to start building online services with the online part in mind. We had initially decided to implement everything locally and port to online later; however, we had to refactor the code and structure entirely to work online.

Lastly, we learned how to use Git, as well as general source control concepts. Using this, we learning how to better work as part of a team. 

## Play the Game
Due to the Node dependency, I am unable to directly host the project to this page. If you wish to try the game for yourself, head to the project's Github repository by clicking the green button to the right. You'll find all of the files necessary to host a local server and client to play the game.

---

# Cybots
## About
*Cybots* was a game solo-developed for a game design class. The overall gameplay and several requirements were given by the professor. The way in which we implemented those features were up to interpretation by the students. Also, any other additions to the game were welcome and I took advantage of that to add a little humor into the game.

When you first start up the game, you will yourself in a dimly-lit maze. The controls are mapped to a controller. On the minimap that appears on the screen, you will see yourself as an arrow - yes, where it points is where you're currently looking. On that same map, you will see a blue square. That is your goal. You may also notice some dots moving around in the maze. These are the enemies you need to avoid; they are the Cybots themselves. If they see you, they will freeze you in place for a few seconds. Get cornered by several at once and you lose. Lastly, there are several crates to hide behind or jump on top of.

## Using Cellular Automation to Generate the Maze
One of the things I had the most fun implementing was the procedural generation of the game's maze. To do this, I used a modified version of the classic cellular automation algorithm, Conway's Game of Life. The modifications were mainly changing the death/birth values, as well as removing one of the conditionals. The idea for this game from the following website: [Jrheard's Blog](https://blog.jrheard.com/procedural-dungeon-generation-cellular-automata)

## Enemy Types
Every enemy in this game has a unique personality reflected in their aesthetics and AI. These are:
* **Standard**: Normal. Nothing special.
* **Drunk**: Has a chance to randomly stop chasing player. Vision impaired.
* **Sassy**: Stops to pose when you're looking at it
* **Sneaky**: Doesn't make sound
* **Old**: Slow and can't see very well
* **Fast**: Is fast. Enjoys chili dogs.
* **Starchild**: ALWAYS knows where you are. Oh geez, he comin'.
* **Lonely**: Follows you once it finds you.
* **Stoner**: Is slow. Has a delay before making any decisions. Vision impaired.

## Skills Gained
The first skill that I gained from developing this project is experience with the C# language. This was also the language we used in previous projects, so the usage here was no surprise. For this project, it was used to write the various scripts used in the Unity engine.

I also gained experience using the Unity engine itself through the development of this game. I had only previously used the Unity engine to convert the file types of some 3D models. In particular, I worked with the following Unity tools:
* Animation controller (keyframing, tweens, etc.)
* Texturing
* Lighting
* Physics 
* AI and Decision Trees (using the Behavior Bricks asset)

## Play the Game

<!-- TODO: Try to put the Unity web player here playing the game -->
<h3><span style="color: red;">TODO: Try to put the Unity web player here playing the game</span></h3>

---

# Bow Game
## About
This game is not much of a game and more of an interactive showcase of the different WebGL concepts we learned during my graphic course at university. This project was created with one other person as an assignment for that class. Although the assignment called for a presentation and program on a specific concept, we felt it would be more interesting to combine several concepts into something that our fellow students can play. 

We took inspiration for the game's mechanics from a 2D Adobe Flash game that my teammate and I had played when we were younger. It's simple; two people stand across from each other and take turns shooting at each other with a bow and some arrows. We had the challenge of trying to replicate this gameplay in a 3D environment using WebGL and Javascript. Just like the original game, our game requires players to account for both arrow trajectories (gravity) and windy conditions.   

## Skills Gained
From this project, as well as the class itself, we learned how graphics are actually generated from a very low-level perspective. To implement this project, we worked with vertex positions, vertex shader code, etc. 

**A few ideas shown:**
* 3D object hierarchies
* Animation (or the illusion of)
* Collision Detection
* Raycasting (used in game controls)
* Particle Systems

**More information on techniques used, contributions made, and references, visit the project's Github repository by clicking on the green button on the right! **

## Play the Game

<!-- TODO: Try to put the game's code in a canvas element here -->
<h3><span style="color: red;">TODO: Try to put the game's code in a canvas element here</span></h3>