# GameDesignDocument
## Game Design
### Objective
Try to get higher score by shooting ball hit others ball

### Gameplay Mechanics
Players decide the angle and power to shoot the ball by using touchEvent and the ball will follow the physical rule to move.
whenever the ball hit the same color of ball, they get point.
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

### Scene Design
* Scene with Physics(Scene)
 * Game Scene(Node)
   * mainScene(Node)
     * cannnon
     * background
     * Back button
     * Score Label
     * Ball 
     * Block

### Controls/Input
 * Move left and right to change the angle of cannon
 * touch the screen to shoot the ball
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
* Read Level Setting from Json and set map depend on data
  * Design the data flow and structue of state
  * make JSON Packer: which read from json setting to decide stage setting
  * Make the Ball bag to Hold balls and create ball
* Make a point calculate system
  * MVP just make some score on the board
* change the asset to make the resolution of physics words of multi device worked
  * Physics world should be the same for different device
* think about 2 ways to paly games
* config ball setting (speed mask and so on) item setting, let it be more structure
* Design some 2 items that make the game interesting
  * implement items box
  * add touch event and stage control


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
