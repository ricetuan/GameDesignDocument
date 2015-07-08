# GameDesignDocument
## Game Design
### Objective
Try to get higher score by shooting ball pass the point circle which contains scores likes +10, +20, -10 in the map.

### Gameplay Mechanics
The ball shot by player will follow the physical rule. The ball will move, slow down, accelerate depends on the environment.
Players decide the angle and power to shoot the ball by using touchEvent and the ball will follow the physical rule to move.
whenever the ball pass the circle, player will get the point of circle.
### Level Design
The game will perform for two mode. Simple mode and Advanced mode.In tutorial, there will be about 10 ~ 20 situation to make player farmilar with the item and the game. 
* Simple Mode
  * Only ball is allowed to shoot and play
* Advanced
  * other items which may accelerate the ball or make a block can be used in the game.

## Technical
### Scenes
* Lobby Menu (Single player and multiplayer )
* GameScene
* Item Box (Player choose item when their play)

### Controls/Input
* Swipe based controls(Like angry bird) 
  * Swipe behind to create an angle and decide the power of shooting
  * touch items if you would like to use one

### Classes/CCBs
* Scene
 * GameScene
 * Lobby
* Node/Sprite
 * Item
 * Network
 * Json
 * Ball
 * world
 * ScoreBorad
* Something with physics

## MVP Milestones
### Week 1 (7/13 - 7/19/2015)
* implement basic physics world
  * add ball with physics
  * ball collision
* implement single player game scene
* Designing basic level of Map

### Week 2 (7/20 - 7/26/2015)
* implement point calculating system
  * add detect if a ball pass the point circle
  * calculate point of player
* implement single player game scene
* Continuously designing basic level of Map

### Week 3 (7/27 - 8/2/2015) - finish core game play
* implement some basic items
* implement the animation of collision
* Polishing UI
* Continuously designing basic level of Map

### Week 4 (8/3 - 8/9/2015)
* implement Tutorial
* implement the all level of single player
* Testing

### Week 5 (8/10 - 8/14/2015)
* Testing
* shipping the app to appstore
* 
