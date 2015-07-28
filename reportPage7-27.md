##Plan for 7/21 week
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
