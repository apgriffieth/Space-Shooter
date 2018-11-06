# Space-Shooter
This space shooter game was the third game created in GameMaker. Similar to other arcade style space shooters like Galaga and Space Invaders, this is a high-score based arcade game with no time limits. 

Some info about my game:

 ENEMIES: Red enemies have 7 hitpoints and move in simple horizontal patterns. Blue enemies move with a sine wave pattern. They progress down the screen until reaching a point in which they just move horizontally. They are capable of firing in bursts of 3 and only have 3 hitpoints. There are 3 spawners. One is on at the start, the other two turn on after a certain amount of time.
 
 POWERUPS: Green powerups increase health by 40 to a max of 200. Red powerups give triple damage and rapid fire for 10 seconds. This is communicated to the player through audio and visual effects. A charge up sound plays when the red powerup is collected and a discharge sound plays when it ends. This is further communicated with a red effect surrounding the extra damage bullets. Yellow powerups increase weapon spread from 1 to 3 to 5. They will no longer spawn once the 5 spread weapon is obtained. Yellow powerups spawn based on time and also serve as a signal for another enemy spawner being activated. Red and green powerups come from the same spawner. This spawner randomly spawns one or the other every 20 seconds. It is possible to play an entire game without getting any health powerups or any damage powerups. I like including this element of luck/randomness.
 
 AUDIO/VISUAL: All audio and visual effects were obtained from OpenGameArt. Extra sounds play when a red powerup is picked up/ends and when a yellow powerup is collected. The powered-up bullet was created in GameMaker. Background music was used in the final product but could not be included in this submission as it made the file too large for github.
 
 GAMEPLAY: It is very possible to get a high score in this game but it does take an element of luck. Games will typically last from 45 seconds to 1 minute and 30 seconds. As one continues to play however, the game does get progressively easier suggesting an additional spawner should be activated at a certain time frame.
