##Goal
 - Make a standard level of Game 
 - acquire the knowledege of cocos2d,c++ and basic game development of native game
##Approach(Last two week)
- Finished the games with all basic feature
  - two more Items
    - Move arrow - which ball can have be change to a certain angle
    - powerUp - Ball can be shoot in a more fast speed
  - Thirty Stage of Games
  - Title Scene and Top Bar
  - Sound
  - Fix all bugs of games
   - Try to thinking about why I got that bugs and how to prevent it appears(also bugs is always exists in codes)

- Refacotring code using C++ style
  - const correct : Do not need to be perfect but let myself be familar with const correct coding style
  - some duplicated code should be ordered : also do not need to be perfect but try to figuring out some way of refactoring and which is good or bad

##detail Planing
###priority
  - high : which must do because of strong relative with the Goal
    - e.g. basic feature of game
    - e.g. skill which would certainly help for future working in gree
    - e.g. Schedule management,analyzing the problem and figure out the solution
  - middle : which should do because of normal relative with the goal or personal improvoment
    - e.g. basic polishing 
  - low : which is optional to do because of week relative to the Goal
    - e.g. advance polishing 

###Todo list
  - Items Move arrow:(3h) high
    - Art of Move arrow
    - implement of Moving arrow in single mode(New game state and items)
    - implement of Moving arrow in multiplay mode(data sync)
   - result: 1 hour to try to figure out art set. It totally waste of time to do such of thinks. Just make some a simple items to do since my job is not creating art asset. 3 hours to implement the touch event. different from other items, transport has a total different ways to use. Custom class and Game logic method is needed for transport.
  - Items power up:(2h) high
    - Art of Power up
    - implement of Power up in single mode(New game state and items)
    - implement of Power up in multiplay mode(data sync)
  - result: finished in 1h20min. Witout polishing the effect, framework make it quite simple for implementation but multiplay test takes times.
  - Refactoring:(4h)
    - GameScene.cpp : make it more readable and structed (high)
    - getter and setter Method: const correct and const & to make it more efficient (low)
  - Title Scene(3h) high
    - two button:single and multi
    - Backgrond and logo charactor art work
    - Name of Games
  - Sound(1.5d) high
    - find the asset of Games(0.4~0.7d)
      - backGound BGM
      - shooting effect
      - Bomb Effcet
      - collusion Effect
      - level Clear
    - implement of sound effect code (reffer to the books) (0.5d ~ 1d)
  - Stage design(1d) high
    - easy stage about 10
    - middle stage about 10
    - hard stage about 10 (need bouncing and using items to clear)
  - Tutorial of Items Use(0.5d) high
    - Another tutorial over 10 stage to let user know how to use items
  - polish(2d~) middle
    - make info how many Ball left
    - make tutorial touch to move next
    - make charactor animation more enjoyable(low)
    - make level clear scene more enjoyable
    - make a cusino of item get
    - make a bigger and enjoyable collecting coin animation 
    - make a failed level up (maybe high)
    - make a thunder effect
  - Bug Fixs:(2d~) high
    - Bomb collusion contact
    - MultiPlayer Game over not sync(2h)
    - data Sync of Ball Coin and items for multi player(4h)
  - Optional Feature(low)
    - more items(fog - make all ball invisible)
    - more level
    - more map of multi play mode
    - control the power of cannnon

##Addition work
  - thinking style of American People
  - experience in silicon valley

