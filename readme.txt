by ^SoRrIdStRoKeR^

readme for sp sound fix.

to make the weapon sounds work on your sp level:


open pk3

open the folder "sondfix"


open the script "mapswitch"


within that script is a switch:

	switch(local.map)

find your map and enter the weapons that do not work by adding the following variables:

		level.springfield = 1	
		level.rife = 1							
		level.bar = 1								
		level.bazooka = 1
		level.panzer = 1	
		level.mp44 = 1		
		level.shotgun = 1

be carefull not to apply the variable if it is not needed (if the weapon sound works for that level) if you do the 
sound will play twice.


be sure your clients do not have an edited ubersound which includes weapon sounds else you will get double sounds.


a txt file has been included listing all statefile changes.