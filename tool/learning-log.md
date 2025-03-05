# Tool Learning Log

## Tool: GoDot

## Project: Making a two player fighting game either street fighter style or the way a fight of glorton which was a browser game.

---

### 10/21/24:
* Im surprised it actualluy uses scenes like it did for kaboom,
* To start making your game you will need to define a player a mob/enemy type character, and a HUD
* To define the player it can be done even before testing the other aspects of the game
* Choose the root node the player object will be connected to (Add an Area20 noode)
* Area20 checks like any collisions or anything that cross the player

### 10/28/24:
* Godot uses different naming conventions when writing in their GDScript for classes they use PascalCase varibles and functions use snake_case
* I'm not sure if I will use constants but for them you use ALL_CAPS
* AnimatedSprite2D will be the tool use that will hold our player sprite and animations to be used later
* Something different that I like that Godot has is that for animations you can preview your animation unlike in kaboom where the animation is more complex and you have to make your own spread sheet

### 11/18/24:
* Godot has a lot more of customizability than kaboom which evident when defining a sprites hitbox. In Godot you can accurately set the rangeof when the player should be defined as making contact with another object in your game. It wasn't impossible to preform the same action with kaboom but it felt more tedious to do as sometimes your sprite would have a hit box so far off the engine would register a contact was made even before the sprite looked like it was close.
* With Godot the sprite you have already made before should already have a set body but it can modified by as simple as dragging and clicking on a set hitbox
<!--
* Links you used today (websites, videos, etc)

* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
[video](https://youtu.be/LOhfqjmasi0?si=97RQQAm9aia7c_2w)

### 12/8/24
* Godot allows for the user to use already created sprites for building blocks that can be placed anywhere after setting the colliide node to the player because without it the player will not be able to interact with any of the plateforms and will fall through the floor
* But for the floor to start to move on their own you would have to add an animation node

### 1/6/25
* 