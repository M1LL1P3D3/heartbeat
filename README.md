~ heartbeat 
=========

Welcome to the heartbeat project!
This is a very handy bot for Bukkit servers, powered by the Skript engine (see http://dev.bukkit.org/server-mods/skript/).
I aim to provide a plugin that suits all general player and admin needs, including background processes...
so YOU don't have to do the bulk work.
heartbeat automates Bukkit servers just how you want them.
Try it, you'll like it! :3

Explanation of files:

heartbeat.jar: Skript Core plugin file, bridge between heartbeat and the Java interface + Bukkit API.
SQLibrary.jar: Handles data storage and retreival.
Skript/:
	variables.csv: (generated on first load) Doesn't actually do anything, but if you delete it, Skript will sh** bricks.
	skdata.db: (generated on first load) SQLite database that contains all of heartbeat's data, DO NOT MANUALLY MODIFY.
	config.sk: Global Skript settings, no need to change anything, it's all set for you. heartbeat-specific config is in scripts/hbconf.sk.
	aliases.sk: Contains support for shorthand names in the code (Don't touch this!).
	logs/: (generated on fist load) Self-explanitory. :P
	backups/: Well... backups. :)
	scripts/:
		hbconf.sk: Config file!
		hbmain.sk: Main heartbeat code.
		hbgoto.sk: GOTO code
		hbpvp.sk: PVP mode code
		hbconnect.sk: Events that occur on connections.
		hbab.sk: Auto-Broadcast code.
		hbchat.sk: heartbeat's chat handler.
		hbadmin.sk: Admin tools
		hbgg.sk: Grief protection
		hbspy.sk: Spy mode code.
		hbinfo.sk: Commands with server info.
