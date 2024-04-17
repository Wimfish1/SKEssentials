# SKEssentials

Made by Wimfish1 for Minecraft. Simplify comamnds and add essential tools to your server!

# Requirements

Skript <a href="https://github.com/SkriptLang/Skript/releases">(Link Here></a>
SKCord <a href="https://github.com/Fedox-die-Ente/skCord/releases">(Link Here)</a>


# DOCUMENTATION BELOW 

## Config Lines

Discord Webhook Links: ``Line 102 | Line 120 | Line 134 | Line 163 | Line 253 | Line 278``

Discord Link: ``Line 383``

## Command Documentation


Name: gmc<br>
Description: Sets players gamemode to creative.<br>
Usage: ``/gmc or /gmc <player>``<br>
Permission: ``SKEssentials.gmc``<br>

_________________

Name: gms<br>
Description: Sets players gamemode to survival.<br>
Usage: ``/gms or /gms <player>``<br>
Permission: ``SKEssentials.gms``<br>

_________________

Name: gma<br>
  Description: Sets players gamemode to adventure mode.<br>
  Usage: ``/gma or /gma <player>``<br>
  Permission: ``SKEssentials.gma``<br>

_________________

Name: gmsp<br>
  Description: Sets players gamemode to spectator mode.<br>
  Usage: ``/gmsp or /gmsp <player>``<br>
  Permission: ``SKEssentials.gmsp``<br>
  
_________________

Name: i<br>
  Description: Gives the specified iteml.<br>
  Usage: ``/i <item> or /i <item> <amount> <player>``<br>
  Permission: ``SKEssentials.give``<br>

_________________

Name: tp<br>
  Description: Teleports the player.<br>
  Usage: ``/tp <player>``<br>
  Permission: ``SKEssentials.tp``<br>

_________________

Name: tphere<br>
  Description: Teleports specified player to the executor..<br>
  Usage: ``/tphere <player>``<br>
  Permission: ``SKEssentials.tphere``<br>

_________________

Name: freeze<br>
  Description: Freezes and Unfreezes the player.<br>
  Usage: ``/freeze <player>``<br>
  Permission: ``SKEssentials.freeze``<br>

_________________

Name: mute<br>
  Description: Mutes the specified player. Sends a discord webook if enabled.<br>
  Usage: `` /mute <player> <time in seconds>``<br>
  Permission: ``SKEssentials.mute``<br>

_________________

Name: unmute<br>
  Description: Unmutes the specified player. Sends a discord webhook if enabled.<br>
  Usage: ``/unmute <player>`` <br>
  Permission: ``SKEssentials.unmute``<br>

_________________

Name: fly<br>
  Description: Enables Flight for executor or another player..<br>
  Usage: ``/fly <player> or /fly`` <br>
  Permission: ``SKEssentials.fly``<br>

_________________

Name: ban<br>
  Description: Bans the player. Sends a discord webhook if enabled.<br>
  Usage: ``/ban <player> <reason>`` <br>
  Permission: ``SKEssentials.ban``<br>

_________________

Name: pardon<br>
  Description: Pardons the player. Sends a discord webhook if enabled.<br>
  Usage: ``/pardon <player>`` <br>
  Permission: ``SKEssentials.pardon``<br>

_________________

Name: baninfo<br>
  Description: Gives info on the users ban status.<br>
  Usage: ``/baninfo <player>`` <br>
  Permission: ``SKEssentials.baninfo``<br>

_________________


Name: warn<br>
  Description: Warns the player. Sends a webhook if enabled.<br>
  Usage: ``/warn <player> <reason>`` <br>
  Permission: ``SKEssentials.warn``<br>

_________________

Name: warnings<br>
  aliases: /warns
  Description: Gives the amount of warnings the player has.<br>
  Usage: ``/warnings <player>`` <br>
  Permission: ``SKEssentials.warnings``<br>

_________________

Name: deletewarn<br>
  aliases: /delwarn
  Description: Deletes a warning.. Sends discord webhook if enabled. <br>
  Usage: ``/deletewarn <player> <reason>`` <br>
  Permission: ``SKEssentials.deletewarn``<br>

_________________

Name: speed<br>
  Description: Sets player speed. <br>
  Usage: ``/speed <player> <number>`` <br>
  Permission: ``SKEssentials.speed``<br>

_________________

Name: ci<br>
  Description: Clears yours or the specified players inventory. <br>
  Usage: ``/ci or /ci <player> `` <br>
  Permission: ``SKEssentials.clearinventory``<br>

_________________

Name: repair<br>
  Description: Repairs your held item. <br>
  Usage: ``/repair`` <br>
  Permission: ``SKEssentials.repair``<br>

_________________

Name: sudo<br>
  Description: Forces the specified player to run a command. <br>
  Usage: ``/sudo <player> <command>`` <br>
  Permission: ``SKEssentials.sudo``<br>

_________________

Name: broadcast<br>
  Description: Broadcast an Anonymous message. <br>
  Usage: ``/broadcast <text>`` <br>
  Permission: ``SKEssentials.broadcast``<br>

_________________

Name: afk<br>
  Description: Sets you to AFK. <br>
  Usage: ``/afk`` <br>
  Permission: ``SKEssentials.afk``<br>

_________________

Name: heal<br>
  Description: Heals you / the specified player. <br>
  Usage: ``/heal or /heal <player>`` <br>
  Permission: ``SKEssentials.heal``<br>

_________________

Name: feed<br>
  Description: Feeds you / the specified player. <br>
  Usage: ``/feed or /feed <player>`` <br>
  Permission: ``SKEssentials.feed``<br>

_________________

Name: discord<br>
  Description: Sends a embeded discord link (Config at line 384). <br>
  Usage: ``/discord>`` <br>
  Permission: ``N/A``br>

_________________

Name: setspawn<br>
  Description: Sets the spawn location to your current location. <br>
  Usage: ``/setspawn>`` <br>
  Permission: ``SKEssentials.setspawn``br>

_________________

Name: spawn<br>
  Description: Teleports the player to spawn. <br>
  Usage: ``/spawn>`` <br>
  Permission: ``SKEssentials.spawn``br>

_________________

Name: setwarp<br>
  Description: Sets a warp. <br>
  Usage: ``/setwarp <name>`` <br>
  Permission: ``SKEssentials.setwarp``br>

_________________

Name: delwarp<br>
  Description: Deletes a warp. <br>
  Usage: ``/delwarp <name>`` <br>
  Permission: ``SKEssentials.delwarp``br>

_________________

Name: warp<br>
  Description: Telports you to the specified warp. <br>
  Usage: ``/warp <name>`` <br>
  Permission: ``SKEssentials.warp``br>

_________________

Name: tpa<br>
  Description: Sends a tpa to specified player. <br>
  Usage: ``/tpa <player>`` <br>
  Permission: ``SKEssentials.tpa``br>

_________________

Name: tpaccept<br>
  Description: Accepts the tpa request. <br>
  Usage: ``/tpaccept`` <br>
  Permission: ``SKEssentials.tpaccept``br>

_________________

Name: tpdeny<br>
  Description: Denies the tpa request. <br>
  Usage: ``/tpdeny`` <br>
  Permission: ``SKEssentials.tpadeny``br>

_________________

Name: vanish<br>
  Description: Hides you from other players. <br>
  Usage: ``/vanish`` <br>
  Permission: ``SKEssentials.vanish``br>

_________________

Name: itemrename<br>
  Description: Renames your item. Does support colours <br>
  Usage: ``/itemrename <text>`` <br>
  aliases: /irename
  Permission: ``SKEssentials.itemrename``br>

_________________

Name: itemlore<br>
  Description: Sets the lore of your item. Does support colours <br>
  Usage: ``/itemlore <text>`` <br>
  aliases: /ilore
  Permission: ``SKEssentials.itemlore``br>

_________________

Name: weather<br>
  Description: Sets the weather in the players current world.<br>
  Usage: ``/weather <type>`` <br>
  Permission: ``SKEssentials.weather``br>

_________________

Name: suicide<br>
  Description: Causes you to die.<br>
  Usage: ``/suicide`` <br>
  Permission: ``SKEssentials.suicide``br>

_________________

Name: SKEssentials Reload<br>
  Description: Reloads the Skript.<br>
  Usage: ``/SKEssentials reload`` <br>
  Permission: ``SKEssentials.admin``br>

_________________

Name: EditSign<br>
  Description: Edits signs.<br>
  Usage: ``/editsign <line> <text>`` <br>
  aliases: ``/modifysign /modsign``
  Permission: ``SKEssentials.editsign``br>

_________________

Name: enderchest<br>
  Description: Opens your enderchest.<br>
  Usage: ``/enderchest`` <br>
  aliases: ``/ec``
  Permission: ``SKEssentials.enderchest``br>

_________________

Name: teleportall<br>
  Description: Teleports all players to you.<br>
  Usage: ``/teleportall`` <br>
  aliases: ``/tpall``
  Permission: ``SKEssentials.teleportall``br>

_________________

Name: kickall<br>
  Description: Kicks all players from the server..<br>
  Usage: ``/kickall`` <br>
  Permission: ``SKEssentials.kickall``br>

_________________

Name: time<br>
  Description: Sets the time in the players current world.<br>
  Usage: ``/time <time>`` <br>
  Permission: ``SKEssentials.time``br>

_________________

Name: offline tp<br>
  Description: Teleports you to the logout location of the player.<br>
  Usage: ``/offlinetp <player>`` <br>
  Permission: ``SKEssentials.offlinetp``<br>

_________________

Name: destroyblock<br>
  Description: Destroys the block a player is looking at.<br>
  Usage: ``/destroyblock`` <br>
  Permission: ``SKEssentials.destroyblock``<br>

_________________

Name: clearchat<br>
  Description: Clears chat.<br>
  Usage: ``/clearchat`` <br>
  Permission: ``SKEssentials.clearchat``<br>

_________________

Name: mutechat<br>
  Description: Mutes the chat. (Disables talking for anyone without the bypass permission)<br>
  Usage: ``/mutechat`` <br>
  Permission: ``SKEssentials.mutechat``<br>
  Bypass Permission: ``SKEssentials.mutechat.bypass``<br>

_________________

Name: workbench<br>
  Description: Opens a portable workbench<br>
  Usage: ``/workbench`` <br>
 <li> Permission: ``SKEssentials.workbench``<br></li>

_________________
