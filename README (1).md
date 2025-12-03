# Dont't Melt

This is a primary version of this game that has not been perfected. Version 2 coming soon.

## Play the Game
**Unity Play Link**: https://play.unity.com/en/games/3ec104de-25de-4532-a4bb-784990c5aa2a/dont-melt

## Game Overview
Play as an ice cream cone trying to avoid the summer sun!

### Controls
Use your mouse cursor to click and move the cone away from the floating hot suns.

### How to Play
Once the game begins, point your ice cream cone away from the hot suns, avoiding the walls. If you collide with one and melt, simply press restart and go again!

## Base Game Implementation

### Completion Status
- [x] Player movement and controls
- [x] Obstacle spawning system
- [x] Collision detection
- [x] Score system
- [x] Game over state
- [ ] [Any incomplete features]

### Known Bugs
- The speed of the ice cream cone is slower than what appeared in creation and editing.

### Limitations
- Speed of the cone makes it harder to stay alive for a long period of time.

## Extensions Implemented

### 1. Cohesive Color Scheme : 2 points
**Implementation**: I changed the colors to match a warm, sunny day
**Game Impact**: Looks nice visibly
**Technical Details**: Changed my obstacles to images of the sun
**Known Issues**: None

### 2. Core Concept/Swapped Sprites: 3 points & 3 points
**Implementation**: Switched from a rocket ship and rocks to an ice cream cone and suns. Also, switched the borders to images of the sky.
**Game Impact**: Creates a theme that helps make a more innovative experience.
**Technical Details**: Downloaded assets from the Unity store to create the sun's image and used a triangle and circle for my ice cream cone. 
**Known Issues**:None

### 3. Ambient Background Particles : 4 Points
**Implementation**: Added floating white particles into the black background to feel like you were floating in space
**Game Impact**: Added vibe to the experience to make the suns feel more in place.
**Technical Details**: Small particles created that fade in and out within the game borders behind the suns and player controlled ice cream
**Known Issues**: May extend over border, was hard to be sure.

### 4. Difficulty Increasing : 5 points
**Implementation**: The game difficulty increases over time with your obstacles gaining speed and size.
**Game Impact**: Creates a more competitive experience that will prevent repetition.
**Techincal Details**: The speed of each object should increase differently then the others as well as the size of each one.
**Known Issues**: The individuality does not work every time and only works very slowly when it does.

### 5. Border Deletion: 4 points
**Implementation**: When your ice cream cone melts(dies), the borders of the game remove themself to show the game over state.
**Game Impact**: Creates the obvious knowledge that you have failed, shows that your game is now over and to start again
**Technical Details**: The border deletion took me a while as putting the border parent into the player parent took me a while to figure out.
**Known Issues**: None, works as expected.

## Credits
- No outside sources used
- Suns downloaded from Unity Asset store

## Reflection
**Total Points Claimed**: Base: 80% + Extensions: 21 points = Total = 101 points 
**Challenges**: The post game completion steps were the most difficult for me. In creation steps that were difficult were some of the extensions such as border removal because the code for it either did not work, or removed the restart button and its ability. However, I realized that it was not my code, however, my placement of the BorderParent was incorrect.
**Learning Outcomes**: I learned that even the simplest of game creation is hard but it is fun and very rewarding and cannot wait for the next game I make.

## Development Notes
None to Add
