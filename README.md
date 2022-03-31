Hello there ! I'm releasing a free edited fivem base with esx-legacy 1.6 (before 1.6.5 release) compatible and made for Quasar Inventory 1.4.

How can I install it ?

--> Download :

download this repository, latest fivem artifact and also download [inventory] assets from keymaster.fivem.net
don't forget to download quasar's progressbar. (https://github.com/quasar-scripts/progressbar)
--> Setup :

config the server.cfg file, install the artifact, drop the inventory asset somewhere in /resources .
start xampp and create your database(utf8_general_ci), import legacy.sql and then inventory sql.
Config anything else you would like to change.
--> Run it:

try to start the server, be patient the first time and check if there are any errors..
and enjoy your new server ! :)
What changed from the latest release (esx-legacy-for-quasar-inventory 1.5 and 1.6) ?

--> Fixes/Updated resources :

Obviously a lot of esx scripts were update (hehe ^^), check esx-legacy 1.6 changelog for more informations.
Oxmysql is now updated to v2.2.1 (no need think about it when installing Quasar-smartphone.)

--> esx_multichar :
It's now available and is working, just remember that it changes the identifier. (ex: char1:xxxx...)

--> Some commands were edited/removed :

giveweapon ammo arguments were removed, inventory doesn't support it. (now : /giveweapon 'id' 'weaponname')
/group and /job were removed too, /info does the same thing and also prints the player name so it's useless.
/clearinventory command from es_extended was removed, Quasar Inventory has it own.

--> esx_property :
Fixed a bug in client/main (822), I don't recommend to use this script but you can still try it.


That's all ! basically nothing more than my last esx-legacy release for Quasar Inventory. This free edit is nothing than a little nudge to help you to launch your first server with the inventory. As mentioned before I'm not selling anything ! At the beginning, I only wanted to share my personal base because I received a few messages on discord of people having troubles with the installation of 1.5 esx-legacy and I wanted to help them by sharing my files. Now inventory 1.4 was released, I updated my little work. Hope you enjoy it !

If you want to know more about the esx framework on fivem, this is their github :

https://github.com/esx-framework
If you want to purchase Quasar Inventory or just want to know more about it :

Inventory https://quasar-store.com/package/4770732
Preview https://www.youtube.com/watch?v=PsqMPUhJHMg
Thanks for your attention :)