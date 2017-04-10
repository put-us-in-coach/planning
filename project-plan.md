## Team name:
 - Put Us In, Coach!

## Team members:
 - Reginal Grant
 - Serg Tsogtbaatar
 - Robert Hatfield

## Overview & concept:
An application that tracks player positions and time on field, with dynamic player substitution.  
Emphasis on an intuitive interface.

## Model layer:

### Players
- Name
- Photo
- Current play time
- Role call (Bool, is present?)
- Total # games played
- Total play time
- Notes
- Positions 

### Teams
- Players (an array)
- Games (an array)

### Games
- Lineup / players present (an array)
- Positions w/ player currently in game (dictionary collection), e.g. `playfield.center`, `playfield.forwardLeft`
- Total game time
- Player play times

## Wireframes:
[Pre-game](media/pregame.png)  
[In-game](media/ingame.png)

## Expected Frameworks & Libraries:
  - CloudKit for device sync
    - May use this to share with other coaches, possibly other types of users
	- Gesture recognizers
  - UIImages w/ photo library and camera capture
  - Timers

## Minimum Viable Product:
  - **Players**
    - can be assigned positions on the field or court
    - have cumulative and instance timers to track time on field
    - can have a photo assigned to their record
  - **Games**
    - have a timer that can be started or stopped
    - include appropriate period / quarters based upon which sport is tracked
  - **Position assignment**
    - May be drag & drop
    - Or tap to select a player, then tap a position to assign that player
    - If position is currently filled, send current player to the bench

## Stretch goals:
  - Sharing
  - Player notes / standard position
  - Multiple teams / squads
  - Multiple sports
  - Alternate device views
  - Scroll bench view in sync with game timer
  - Show progress bar / color player timers based on fair share of time played

## Task management:
GitHub Projects will be used to manage tasks and issues.
