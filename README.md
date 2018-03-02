## WHAT IS ROW PLANTER?

Row planter is a minecraft server skript plugin that plants a row of crops in the direction the player is looking. It can also place a line of rails or fences or most other blocks.

## TUTORIAL

Stand at one end of a field holding some seeds. point your curser to the other end of the field and type `/row plant`. or you could type `/row oneclick true`, look over that field then hold shift and right click!

## COMMANDS

* `/row plant` Used to plants a row of crops using the items from the players hand.

* `/row place` Places a row of blocks from the players hand on the ground. note that it uses the block you're standing on as the ground, for example if you where standing on stone it will only place rails on stone and will skip over grass or dirt. this trick is also used when planting sugarcane.

* `/row oneclick [ true | false | toggle ]` turns one click mode on and off. with click mode on holding shift right click will run `/row plant`, and shift left click will run `/row place`.

* `/row free [block] [ground]` this command places a row without the item cost and allows you to set the parmiters manualy. if you leave the arguments blank it will take `[block]` from your hand and `[ground]` from the block your standing on.

* `/row help` displays help.

* `/row version` displays version.

## PERMISSIONS

You will need to add a few permissions to your permissions plugin.

If your running a spigot server and you don't know what permissions are then you need to learn what they are and how to use them. i would say its the most important thing to know when it comes to bukket servers.
 
I recommend adding these permissions to users or members type groups:
```
- skript.row.user.*
- skript.row.user
```
I recommend adding these permissions to builders or admin type groups:
```
- skript.row.admin.*
- skript.row.admin
```
Here is the full list of permissions and what they allow:
```
- skript.row.user - /row
- skript.row.user.help - /row help
- skript.row.user.plant - /row plant
- skript.row.user.place - /row place
- skript.row.user.oneclick - /row oneclick
- skript.row.admin.free - /row free
```
## DEPENDENCIES

Row Planter depends on tim740's skAliases, which if you don't have and you skript you should get anyway.

https://github.com/tim740/skAliases/releases/

https://forums.skunity.com/resources/aliases.27/

## INSTALLATION

* Make sure skript is installed. If not install it. https://docs.skunity.com/downloads
* Install tim740's skAliases. https://forums.skunity.com/resources/aliases.27/
* Downlaod row_planter.sk and put it in `yourServer/plugins/skript/scripts`.
* Run `/skript reload all`.
* Make sure to add the permissions to your permission manager.

### version notes

I have tested Row Planter v18.3 on minecraft version 1.12.2 using Skript 2.2 bensku-dev33 I havent tested it on other versons. 18.3 is just the year and month btw.
