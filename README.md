# Minecraft SNAPSHOT .commands script v0.53

Written by YT_Veritas0923             

Twitter: @Veritas_83                  

Web: www.NigelTodman.com              

GitHub: Veritas83                     

BTC 18j2Env7QokhGG5MccS3LPBKnjsko6u4NQ

<img src="https://i.gyazo.com/0ded8799db3daea0f35115225b55a66d.png">


Simply place beside your minecraft_server.jar and run.

<img src="https://i.gyazo.com/574ad295a1a3fec5fe9ae6833f3ead1d.png">

Config:

specify admin player name in config. add mods to mods.csv, 1 player name per line.

<pre>
Lines 29-43:

## Start Config ##
javacmd = 'java -Xms2G -Xmx2G -jar minecraft_server.jar nogui' # Java command line to start Minecraft Server jar, Must use nogui
spawn = "0 64 -3"   																					 # WorldSpawn Coordinates
rtpradius = 35000  																						 # Random Teleport radius (-35000,35000)
useautosave = True 																						 # Use Autosave?
useautoclear = True 																					 # Use Autoclear?
autosaveint = 1776																					   # Autosave Interval in seconds
autoclearint = 3625																					   # Autoclear Interval in seconds
freeshulkerbox = True																					 # Gives new players a shulker box on their first connect
motd = "!## MOTD ##! Welcome to mc.nigeltodman.com, PLAYER_NAME! See our custom commands and their usage with '.help' * April Gamerules: limitedCrafting:Off keepInventory:On mobGriefing:Off Difficulty:Hard"
votemsg = "Vote for this server! Vote #1 adf.ly/1kVCJK #2 adf.ly/1kVCLs #3 adf.ly/1g4VYV"
admin="YT_Veritas0923"
																					   									 # Message of the Day notes:
																					   									 # PLAYER_NAME is replaced with connecting player.
## End Config   ##												   									 # 'Welcome to' is replaced by 'Welcome back to' for returning players.
</pre>

Shop Config, Lines 49,50

itemsdb="torch,coal,iron_ingot,gold_ingot,diamond,enchanting_table"
pricedb="5,10,25,50,500,5000"
User Commands:

.spawn

.sethome

.home

.rtp

.warp

.whois

.ping

.report

.seen

.stats

.staff

.tpa

.tpaccept

.tpdeny

.vote

.uptime

.help

.about

.commands

Mod Commands:

.setwarp

.kick