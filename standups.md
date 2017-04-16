# Monday standup
Apr 10, 9:30 AM

## Where are we at
### Regenal
Planning document, wireframes

### Serg
Preparation

### Robert
Planning document, wireframes

## What we need to do today
- Get Xcode project started with initial storyboard
- Build basic model objects
- Researching CloudKit sharing

## Who's doing what
- All: Set up project, storyboard layouts, model objects

## What challenges we expect
- Getting started (where to start?)
- Gesture recognizers
- Keeping timers active in background


# Notes
## Questions
- How to strategically use nav bars/controllers

## to research
- NSTimer
- Get a placeholder player image
- eventkit
- init game objects with roster

## feedback
- seasons
- leagues, number of players, game duration
- add existing players to new team
- ability to edit timer start
- edit start first half, 2nd half times
- period times

# Wrap up
- [x] Project & repo initialized
- [x] Model object classes built
- [x] Wireframes & storyboard built out
- ~~CloudKit research~~

---

# Tuesday standup
Apr 11, 9:45 AM

## Where we are at
- Core views and model objects defined.
- Good progress on wireframe, workflow.
- Feedback from client (Brook) driving some changes

## What we need to do today
**Core functionality:**

- Create players to add to team
	- Text fields
	- Capturing favored positions
- Add players to field
- Timers?
- Adjust # of positions on field

### Who's doing what
Shared programming for now, we may split responsibilities when we start tackling individual features.

## What challenges we expect
- Persisting state [Ray Wenderlich tutorial](https://www.raywenderlich.com/117471/state-restoration-tutorial)
- Tackling timers
- Saving data (season records, etc.)

---

# Wednesday standup
Apr 12, 9:15 AM

## Where we are at
- Able to add players to a singleton Team object and create a new row on the table view
- Started creating the field view with player positions and bench collection view, Serg finished setting up grid

## What we need to do today
- Display player data on the roster table view
- Display players on the field view's bench collection
- Put players in position from the bench
- Get a working timer

### Who's doing what
- **Robert:** Player objects & roster
- **Serg:** Game field, move players between bench and roster
- **Regenal:** timers

## What challenges we expect
- Timers
- Moving players (maybe drag & drop, image crop/ borders)
- Player & roster model structure
	- We want to share a single array, and modify from either roster table view or game field collection view
	- Don't remove from roster; mark as on field or not

--

# Wednesday PM todos:
- [x] Remove/hide players from bench when added to field
- [ ] Move players between positions
- [x] Return field players to bench
- [ ] Replace players on field
- [x] Return to full roster view
- [x] Update timers on players

---

### Timer stuff
change timer gestures?

- double tap, reset game timer, pause player timers  
- long press, reset all
 

---
# Friday final touches

- launch screen storyboard
- remove background colors from active player cells
