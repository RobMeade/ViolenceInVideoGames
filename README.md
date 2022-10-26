# Violence in Video Games - Experiment Environment

This 2D platformer game was used as a experiment environment in a research study.

## Research Study
The study looked at human psychology, focusing on player behaviours and motivations.  The study featured three specific experiments which introduced creative, destructive, and violent game mechanics to the player. 

## Development
The game was created using Unreal Engine (4.26).  Code was written using Blueprint, and implemented Interfaces, Enums, and Structs.  The game uses Flipbooks for sprite animation and TileSheets and TileMaps for level design. 

The primary source of 2D art assets came from Kenney (https://kenney.nl/).

The game includes the following mechanics;
- player movement (left/right)
- player jump
- player create block (build tool)
- player destroy block (build tool)
- player shoot
- level timer
- non-player character movement (simple patrol)
- gravity for blocks

The game features a simple user-interface which the participant is guided through ensuring experiments are conducted in the correct order.

## Game Loop
The player explores the level by creating and destroying blocks to traverse difficult terrain and searches for the objective, indicated by an animated flag.

## Implied Motivation and Goal
A level timer appears at the top of each level and increments continually until the level objective is achieved.  The level timer implies a goal and creates a motivation for the player to complete the level as quickly as possible.  In turn, the level timer can add additional pressure to the player.

The level timer, in reality, has no other significant bearing on the gameplay and offers no reward for the player, as the participant of the research study will complete each level only once.  The level completion time is however quantitative data from which assertions may be made in conjunction with other game metrics.

## Levels and Experiments
The game is split into three levels, each providing a unique experiment environment and allows for the capture of quantitative data for the researcher.

### Level #1
The player is introduced to the level and familiarises themselves with the movement controls for the character.  The player can move horizontally and jump.  The player is given access to the _creative_ game mechanic, allowing them to create blocks with the build tool.

To prevent a situation where the player could block themselves into the level and fail to achieve the objective, a reset level mechanic is enabled for level #1.  Resetting the level will remove all of the blocks which the player has placed, allowing them to continue from where they are, however the level timer is not reset.

![Level #1](/Images/Level1.png)

### Level #2
The player is introduced to the _destructive_ game mechanic, allowing them to destroy blocks with the build tool.

The reset level mechanic is now unnecessary and is therefore disabled.  The player is required to use both the _creative_ and _destructive_ game mechanics to complete the objective, as some blocks are already placed in the level which prevent the player from moving from one area to another directly.

![Level #1](/Images/Level2.png)

### Level #3
The _violent_ game mechanic is enabled, the player can now shoot a projectile.  Non-player characters are also added to the level.  Projectiles will destroy blocks and non-player characters.  Non-player characters do not hinder or harm the player.  

The player is still required to use the _creative_ and _destructive_ game mechanics to complete the objective, but is not required to use the _violent_ game mechanic, but they can if they choose.  The reset level mechanic remain unnecessary and remains disabled.

![Level #1](/Images/Level3.png)

## Game Metrics
Game metrics are recorded during gameplay and include;

- blocks created by player
- blocks destroyed by player (destructive game mechanic)
- blocks destroyed by player (violent game mechanic)
- player fired weapon count
- non-player characters destroyed
- time to complete the objective

Participants are advised in-game to send their game data file to the researcher.  The researcher can use the game's administrative user-interface to view and extrapolate the quantitative data they have received and require.