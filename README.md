MySQL or SQLite Database / Maybe Mongo? - Connected to a Go restful API

Database to hold:

Saved Game state
List of Cards
List of Equipment
List of Events
List of High Scores?


Components: 
Single Controller route

Major Components:
Title/splash/Game Start
Map - Grid full of components, empty are unclickable, filled send you to combat or events
Combat - Player and player status components, enemy and enemy status components, in an array for each enemy, hand component, deck component, flag for boss and/or elites?
Event - Unique sub component for each event?
Deck display
Relic display
Save and Quit menu
