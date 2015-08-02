##Plan for 7/27 week
 - Implement items to make game more fun
   - Item Box
   - Bomb Item
   - Ball Box item
   - Aim Item
 - Polishing
   - Animation of items(bomb)
   - make topbar more pretty(font, division and others)
   - make treature box and animation for this(like a casino)
 - Level Design
   - Design 15 level(Until Fri PlayTesting)
 - Considering the items of multiplay(Important!!)
 - Implement the simple mode of multiplay(unti Wed)
   - simple data sending and reveiving
   - same game mode to single mode
 - Other todo(maybe Not this week)
   - Level clear all button
   - Animation of level clear

##Daily Report
###Mon
- Liked - cocos2d animation(so easy to make)
- Learned - cocos2d memory control 
- Lacked - Ideas of game multiplay design
- Longed for - some animation effect to make game more enjoyable

###Thu

### MultiPlayer Design
- before Game Start
  - send each device name to others
  - use to device name to decide who is host
  - host randomly choose who is first to play
  - host send info to guest
- Game Scene(loop)
  - every state change send a data to other device
  - other device similate the input of device
  - define a finished status ot change (if necessary sync the data on stage so that two device share the same items)
- After
  - Who get the target send game over to another
- rule: try to get the Target coin( e.g 40)
  - coin will keep invisible until you own turn

- Liked - Game State Design
- Learned - Multiplay communication pattern
- Lacked - Level Design knowledge
- Longed for - Good way for Project management

###wed
- Liked - PM group MTG
- Learned - forcast task correctly 
- Lacked - Time to make tutorial
- Longed for - refactoring


###Tur
 - Like : MultiPlay designing of Games
 - Learn : Design of tutorial and polishing
 - Lacked : Time
 - Longed for : desgin of

###Fri
 - like - Play testing
 - Lean - some ways to make game enjoyful
 - lacked - idea of polishing
 - Long for - skill of refactoring

##Weekly review
this week almost make multiplay mode and implement some feature of games. Try to finish all game feature in next week. Basic skill of cocos2d is covered in previews two week. I'd like to focus on PDCA of developing process but not only coding.( how to correctly forcast the schedule, how to solve the problem I met last two week.)  
Two big problem are occured in last two weeks development. Firstly, changing the way of implement without thinking deeply. Usually those implementations are not really appropriate. Sencondly, do not have Todo list with priority so that I don't have a wholely image of the total development.

###Keep
- refactoring code to learn more about c++

###Try
- make a detail plan of Todo list(maybe using the google spread sheet)

###Problem
- lack the controlness of my own product.
