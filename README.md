Here is the source code from last project that I have developed. All game units stats are tweaked from SOUpdater that extracts data from Excel sheets and puts them into ConfigManager. 
DataCentralService is resposible for data persistance in game. MergeController is resposible for main mechanic in game. UI is implemented in different named Window Classes.
Which Are all derived from Window classes. Game RuntimeState is controlled using RunTimeStateMachine. And GameStateMachine is responsible for game states. BaseUnit is a parent classs for EnemyUnits.
PlayerUnitModel has all logic for player unit. And UnitView and PlayerView are Views. Projectile is responsible for projectile movement. 
