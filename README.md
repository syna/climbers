# Climbers and Playtomic
Climbers, the open source game by Sergey Tikhonov is now integrated with Playtomic's analytics. Game developers, feel free to use this example to integrate Playtomic's APIs into your game.

## Integrated so far
- Custom metrics
- Level metrics
- Heatmaps

## Metrics being tracked
- Game Intro Menu : "Play", "More games" and "Source code" button
- Levels : Begins, Fails, Restarts, Percentage of stars collected
- Heatmaps : Snap positions of the climbers, in all 15 levels

Tip: after cloning the project, search for all "Playtomic" instances in Game.m, to see how we did it.
 
## LIVE DATA
View the public [dashboard][1]

## Heatmap Example, from Level 10
![Heatmap](http://i.imgur.com/URxHF.png)

Notice how we can study the player's movement based on where they tend to snap the climbers. Combined with level metrics, we can design better levels!

## Future implementations ( which you can do yourselves, by reading the [iOS documentation][3] )
- Game leaderboards
- Player generated levels
- Game variables (stored on Playtomic, loaded onto the game at runtime. Allows for realtime variable tweaking )

## Lastly, have lotsa fun making games!

[1]: http://playtomic.com/dashboard/overview/5139
[2]: http://haqu.net/
[3]: http://playtomic.com/api/ios