cs56-games-treasure-hunter
==========================

The project creates an instance of the game which allows the user to control a player in search of multiple pieces of treasure in a map made up of grass and bush tiles. The game is fully functional and allows the user to explore the map even after finding the multiple pieces of treasure.

-GameComponent.java contains most of the important implementations of the game. Any problems with the player movement, loading of map and player or the actual paintComponent method are found in that file.

-GameGui.java contains the code for the creation of the GUI and different instances of treasure and player.

-Player.java contains the code for the actual implementation of the player. Any problem occurring with the player moving in the wrong direction or not being created, a look should be taken at this file.


In order to run the game you must do the following:
1. type "ant run"  