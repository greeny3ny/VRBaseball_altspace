# Changelog

28/05/2017 Changes:
  - Added Teams
  - Runs correctly add to respected team
    - No run added if not in team
  - Players on teams displayed
    - Needs work
  - Buttons with text added
    - Stop Music
    - Join red/blue team
    - Reset teams (possibly temporary)

29/05/2017 Changes:
Version 0.1.e.3

  - Player *should* now be removed from inSession when they leave
    - Not fully tested
    - Coded in some horribly complicated way
  - Team names added
  - Team Shirts added
    - equipped when player joins team
  - Aesthetic changes
  - Code made slightly more efficient
  - Code cleaned up
  
FOUND BUGS :
  - Database resets scores occasionally?
  
Version 0.1.e.5:

  - Player *should* be removed from team when they leave the game
    - Not tested
  - Currently broken when only 1 player is in the game
    - When they leave database does not remove them
    - When a new player joins for the first time database is reset? (i think)
      - Not supposed to happen

Version 0.e.h.2:
  - Heartbeat system added
    - Players now join with a heartbeat, if server does not recieve heartbeat, player is removed from game
    - Should now allow players to be removed from team when they leave

