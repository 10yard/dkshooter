# **GalaKong: A Galaga Themed Shoot 'Em Up Plugin for Donkey Kong** #

Tested with latest MAME version 0.239
Fully compatible with all MAME versions from 0.227

Jumpman is assisted by an accompanying ship which can take out barrels, fireballs, firefoxes, pies and springs.  Bonus points are awarded for destroying multiple targets.

The default mode is single player,  with your ship following Jumpman's position.  Jumpman can control the ship independently when he is on a ladder.  The jump button also shoots.

There is also a 2 player co-op mode where a 2nd player controls the ship using separate controls.
 	P1 Start = Left
    P2 Start = Right
	Coin     = Fire

The hack features a scrolling starfield background.
You can disable the starfield (which can be a little distracting) by setting an environmental variable before you run MAME.

```SET GALAKONG_NOSTARS=1```
  
## Installing and running
 
The Plugin is installed by copying the "galakong" folder into your MAME plugins folder.
Galaga game sounds are supported on Windows and Raspberry Pi 4/400.

The Plugin is run by adding `-plugin galakong` to your MAME arguments e.g.

```mame dkong -plugin galakong```  


## Feedback

Please send feedback to jon123wilson@hotmail.com

Jon

