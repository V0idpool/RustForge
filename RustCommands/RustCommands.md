# RustBind Rust Console Commands Reference
![Tool](https://img.shields.io/badge/Utility-RustBind-blue)
![Last Updated](https://img.shields.io/badge/Updated-March%202026-brightgreen)

This is a comprehensive, alphabetized reference for Rust console commands (F1) used for player optimization, server administration, and cinematic tools.
If you notice anything missing, please let me know what it is on the Discord and I will add it to the list.

### **Join the RustForge Discord for Support:**
[https://discord.gg/tfwf9Qr7rG](https://discord.gg/tfwf9Qr7rG)

---

## 🛠 How to Use manually or with RustBind

### RustBind Instructions
1. Open RustBind and choose from presets, or manually type in the command options (For Power Users)
2. Click the **"Capture Hotkey..." button and press your desired key bind and click the "Save & Apply" button.

Use **Ctrl + F** on this page to find specific functions if manually adding, or when using the "Command Pack Manager" to create command pack presets (e.g., "FPS" or "Teleport").

### Manual Instructions
1. Press **F1** in-game to open the console.
2. Type the command & key bind(some require a value like `0` or `1`).

Use **Ctrl + F** on this page to find specific functions (e.g., "FPS" or "Teleport").

---

## 📜 Full Command List (Alphabetized)

| Command | Description |
| :--- | :--- |
| **admintime <0-24>** | Overrides game time for your client only (Admin only). |
| **analytics.pending_analytics** | Shows how many analytics events are pending upload. |
| **analytics.resetstats** | Resets local analytic data. |
| **analytics.stats** | Displays current session analytics. |
| **analytics.tablestats** | Shows database table statistics for analytics. |
| **analytics.uploaderstats** | Shows status of the analytic data uploader. |
| **audio.voices <0-1>** | Adjusts the volume of other players' microphones. |
| **ban <name/ID> <reason>** | Permanently bans a player from the server. |
| **banlistex** | Prints a detailed list of all banned users. |
| **bind <key> <command>** | Maps a console command to a specific keyboard key. |
| **client.connect <ip:port>** | Directly connect to a server via IP address. |
| **combatlog** | Shows the last 30 instances of damage dealt and received. |
| **crosshair.generate_code** | Generates a shareable code for your current crosshair. |
| **crosshair.load_code <code>** | Applies crosshair settings from a shared code. |
| **crosshair.reset_to_default** | Reverts crosshair to factory settings. |
| **debugcamera** | Detaches camera for free-cam movement (Admin only). |
| **demo.play <name>** | Plays back a recorded `.dem` file. |
| **demo.timescale <0-10>** | Changes the speed of demo playback. |
| **disconnect** | Disconnects you from the current server. |
| **electricbattery.battery** | Debugs battery state (charge/deplete). |
| **ent kill** | Destroys the entity you are looking at (Admin only). |
| **ent who** | Shows the Steam64ID of the player who placed the entity. |
| **env.time <0-24>** | Sets the server-wide time of day (Admin only). |
| **fps.limit <value>** | Sets a maximum FPS cap. Use `-1` for unlimited. |
| **gametip.hidegametip** | Removes the current on-screen game tip. |
| **gametip.listgametips** | Lists all possible game tips in the console. |
| **gametip.showgametip** | Forces a specific game tip to appear. |
| **gametip.showtoast <text>** | Displays a custom notification toast on screen. |
| **gametip.showtoast_translated** | Displays a translated notification toast. |
| **global.dump** | Dumps global state information to the console. |
| **global.steamrelayinit** | Initializes the Steam networking relay. |
| **global.steamstatus** | Shows connection status to Steam services. |
| **god <true/false>** | Toggles invincibility/no-hunger (Admin only). |
| **graphics.fov <70-90>** | Changes your Field of View. |
| **graphics.vm_fov_scale <0/1>** | Toggles viewmodel (weapon) scaling. |
| **input.clearbinds** | Wipes all custom keybindings. |
| **input.printbinds** | Lists all current keybindings in the console. |
| **instruments.clearautoplayoverride** | Clears the overridden autoplay recording. |
| **instruments.clearmidibinds** | Clears MIDI binds for the current instrument. |
| **instruments.midiinfo** | Prints MIDI input notes for the current instrument. |
| **instruments.overrideautoplay** | Overrides autoplay recording. |
| **instruments.playnote <note>** | Plays a specific musical note (e.g., `playnote c#7`). |
| **instruments.playrecording** | Plays a saved instrument recording file. |
| **instruments.printmidibinds** | Prints current MIDI rebinds. |
| **instruments.printrecording** | Prints debug readout of a recording. |
| **instruments.printrecordingpath** | Prints the file path for instrument recordings. |
| **instruments.rebindmidi** | Rebinds one MIDI signal to another. |
| **instruments.startrecording** | Begins recording instrument notes to a file. |
| **instruments.stoprecording** | Stops the current instrument recording. |
| **inventory.defs** | Prints inventory definition data. |
| **inventory.examineheld** | Triggers the inspect animation for your held item. |
| **inventory.give <item> <qty>** | Spawns an item into your inventory (Admin only). |
| **inventory.giveall <item>** | Gives an item to every player (Admin only). |
| **inventory.givebp <item>** | Unlocks a specific blueprint (Admin only). |
| **inventory.giveto <name> <item>** | Gives an item to a specific player (Admin only). |
| **inventory.lighttoggle** | Toggles weapon flashlights or laser sights. |
| **inventory.listcraftcounts** | Shows how many items are being crafted. |
| **inventory.pipette** | Selects and gives the item you are looking at. |
| **inventory.reloaddefs** | Reloads inventory definitions from the server. |
| **inventory.resetcraftcounts** | Resets the crafting counters. |
| **inventory.selectitem** | Selects the item you are looking at if in inventory. |
| **inventory.toggle** | Toggles the inventory UI. |
| **inventory.togglecrafting** | Toggles the crafting menu UI. |
| **keyboardmidi.reload** | Reloads MIDI keyboard mappings. |
| **kick <name> <reason>** | Kicks a player from the server. |
| **kill** | Commits suicide to respawn. |
| **laserbeam.printqueue** | Prints the current render queue for laser beams. |
| **layer.culling** | Toggles culling for specific render layers. |
| **layer.hide <name>** | Hides a specific world render layer. |
| **layer.show <name>** | Shows a specific world render layer. |
| **layer.toggle <name>** | Toggles visibility of world layers (debug). |
| **log.level <0-3>** | Sets the verbosity of the console log. |
| **manifest.printmanifest** | Prints the game build manifest. |
| **manifest.printmanifestraw** | Prints the raw manifest data. |
| **memsnap.full** | Takes a full snapshot of memory usage. |
| **memsnap.managed** | Takes a snapshot of managed memory usage. |
| **memsnap.native** | Takes a snapshot of native memory usage. |
| **menubackgroundvideo.emulateerror** | Emulates a video error for the menu background. |
| **menubackgroundvideo.forcenextvideo** | Skips to the next menu background video. |
| **meta.add <cvar> <amount>** | Adds a specific amount to a console variable. |
| **meta.exec <commands>** | Runs multiple commands passed as arguments. |
| **meta.if_false <cmd> <cond>** | Runs a command if the condition is false. |
| **meta.if_true <cmd> <cond>** | Runs a command if the condition is true. |
| **meta.reset_cycle <key>** | Resets a cycled bind to the beginning. |
| **midiconvar.bindkeyoff** | Binds a MIDI note release to a command. |
| **midiconvar.bindkeyon** | Binds a MIDI note press to a command. |
| **midiconvar.bindknob** | Binds a MIDI knob to a command with min/max. |
| **midiconvar.bindknobrelative** | Binds a MIDI knob with relative rate (scrolling). |
| **midiconvar.clearallbindings** | Wipes all MIDI console variable bindings. |
| **midiconvar.printbindings** | Lists all current MIDI-CVar bindings. |
| **midiconvar.reloadbindings** | Reloads MIDI bindings from disk. |
| **moderatorid <ID>** | Adds a player as a Moderator (Auth Level 1). |
| **music.info** | Displays information about the current music. |
| **mutechat** | Silences a player in text chat. |
| **mutevoice** | Silences a player's microphone. |
| **networkprofiler.profile** | Starts a network profiling session for X seconds. |
| **nexus.redirect <ip>** | Redirects player to a linked Nexus server. |
| **nobuildzonematerialcontroller.setheight** | Sets height for no-build zone visuals. |
| **nobuildzonematerialcontroller.setstrengthday** | Sets daytime strength for no-build visuals. |
| **nobuildzonematerialcontroller.setstrengthnight** | Sets nighttime strength for no-build visuals. |
| **note.craft_add** | Debugs adding a note to crafting. |
| **note.craft_done** | Debugs completion of crafting a note. |
| **note.craft_fasttracked** | Debugs fast-tracking a note craft. |
| **note.craft_start** | Debugs starting a note craft. |
| **note.inv** | Debugs note inventory state. |
| **notifications.addfakenotices** | Adds test notifications to the UI. |
| **notifications.dumpnotifications** | Dumps all active notifications to console. |
| **notifications.forceprocess** | Forces processing of the notification queue. |
| **notifications.refresh** | Refreshes the notification system. |
| **ownerid <ID>** | Adds a player as a Server Owner (Auth Level 2). |
| **party.connectparty** | Connects to an existing party. |
| **party.createparty** | Creates a new in-game team/party. |
| **party.fakepartyinvite** | Simulates receiving a party invite. |
| **party.inviteparty** | Invites a player to your party. |
| **party.joinparty** | Joins an invited party. |
| **party.kickparty** | Kicks a member from the party. |
| **party.leaveparty** | Leaves your current party. |
| **party.printparty** | Prints current party members to console. |
| **perf <1-6>** | Overlays performance data (1: FPS, 2: Latency, etc.). |
| **playermodel.debugheadbug** | Debugs player head rendering issues. |
| **player.cinematic_list** | Lists available cinematic animations. |
| **player.cinematic_play** | Plays a cinematic animation. |
| **player.cinematic_stop** | Stops cinematic animations. |
| **player.gesture** | Forces the player to perform a gesture. |
| **player.list_cinematic_gestures** | Lists gestures usable in cinematics. |
| **player.petcmd** | Sends a command to a player-owned pet. |
| **pool.clear_assets** | Clears the asset pool from memory. |
| **pool.clear_memory** | Clears all pooling memory. |
| **pool.clear_prefabs** | Clears prefab pooling. |
| **pool.export_prefabs** | Exports a list of pooled prefabs. |
| **pool.fill_prefabs** | Pre-fills the prefab pool. |
| **pool.print_arraypool** | Prints stats for the array pool. |
| **pool.print_assets** | Prints stats for the asset pool. |
| **pool.print_memory** | Shows memory usage of the asset pooling system. |
| **pool.print_prefabs** | Prints stats for the prefab pool. |
| **pool.reset_max_pool_counter** | Resets the maximum pool size tracker. |
| **profile.dump_profile_recorders** | Dumps performance recorder data. |
| **profile.flush_analytics** | Forces an immediate upload of analytics. |
| **profile.start** | Starts a performance profiling session. |
| **profile.stop** | Stops a performance profiling session. |
| **quit** | Closes the game to the desktop. |
| **record <name>** | Begins recording a game demo file. |
| **render.expand_instancing** | Expands the instanced rendering system. |
| **render.print_global_entities** | Prints count of global building entities. |
| **render.print_instanced_cell** | Prints mesh counts in a single grid cell. |
| **render.print_instanced_debug** | Prints memory/leak data for instanced rendering. |
| **render.print_instanced_renderers** | Prints mesh counts for the instancing system. |
| **render.print_tree_counts** | Prints total trees rendered on the client. |
| **render.test_instancing_culling** | Spawns test prefabs to check rendering culling. |
| **rgbeffects.pulse** | Triggers a pulsing effect on RGB hardware. |
| **rgbeffects.static** | Sets a static color on RGB hardware. |
| **safemode.applysafemodeconfig** | Applies safe settings for troubleshooting. |
| **screenshot.takehiresscreenshot** | Captures a high-resolution screenshot. |
| **screenshot.takehirestransparentscreenshot** | Captures a high-res transparent screenshot. |
| **screenshot.takescreenshot** | Captures a standard screenshot. |
| **screenshot.taketransparentscreenshot** | Captures a transparent background screenshot. |
| **server.hostname <name>** | Changes the server name. |
| **server.writecfg** | **Saves all server changes to the config file.** |
| **skinviewer2.printsupporteditems** | Lists items supported by the skin viewer. |
| **spawn.shielddummy** | Spawns a test dummy with a shield. |
| **steam.achievements** | Lists your current Steam achievement status. |
| **steam.refresh_nickname_cache** | Refreshes names from Steam friends/servers. |
| **steam.resetstats** | Resets Steam statistics. |
| **stop** | Stops a demo recording or playback. |
| **store.addtocart** | Adds an item to the in-game store cart. |
| **store.clearcart** | Empties the store cart. |
| **store.printgeneralstore** | Prints current store items to console. |
| **store.printweeklyitems** | Prints weekly rotating store items. |
| **store.refresh** | Refreshes the in-game store. |
| **streamermode <0/1>** | Toggles hiding of sensitive server/player names. |
| **stringlights.refreshlines** | Refreshes the rendering of string lights. |
| **system.cpu_affinity** | Shows/sets CPU core affinity. |
| **system.cpu_priority** | Adjusts the CPU priority of the game. |
| **teleport <name>** | Teleports you to the specified player. |
| **teleport2me <name>** | Teleports a player to you. |
| **teleportpos <x,y,z>** | Teleports to specific map coordinates. |
| **terrain.debug** | Toggles terrain debug/wireframe views. |
| **texture.stats** | Shows VRAM and texture streaming data. |
| **tincanalarm.wiredistanceculling** | Toggles culling for tin can alarm wires. |
| **translate.printcultureinfo** | Prints current localization/language info. |
| **ui.loadsign <file>** | Loads an image from disk into a sign (Admin only). |
| **ui.printcanvases** | Prints all active UI canvases to console. |
| **ui.printmaskupdategroups** | Debugs UI mask update groups. |
| **ui.printshadowupdategroups** | Debugs UI shadow update groups. |
| **ui.printtexts** | Reports all non-static TMP text objects. |
| **ui.savesign <name>** | Saves the sign image you are editing to disk. |
| **uicontacts.togglecontacts** | Toggles the contacts list UI. |
| **ui_dropscontroller.testdropcrash** | Simulates a crash in the Twitch drops UI. |
| **ui_interactiontoast.testerrormodal** | Displays a test error modal. |
| **ui_interactiontoast.testmodal** | Displays a test UI modal. |
| **ui_menumanager.navigate** | Forces UI navigation to a specific menu. |
| **ui_notifications.addtestnotification** | Adds a test notification to the UI. |
| **ui_steaminventorycrafting.resetwarning** | Resets Steam inventory crafting warnings. |
| **unban <ID>** | Removes a ban from a Steam64ID. |
| **unmutechat** | Restores a player's ability to text chat. |
| **unmutevoice** | Restores a player's microphone usage. |
| **weather.debug_cloud_position** | Debugs the position of clouds. |
| **weather.list_cloud_configs** | Lists available cloud configurations. |
| **weather.load <name>** | Loads a specific weather preset. |
| **weather.load_cloud_config** | Loads a specific cloud configuration. |
| **weather.rain <0-1>** | Adjusts rain intensity (Admin only). |
| **weather.report** | Prints current weather status. |
| **weather.reset** | Resets weather to server defaults. |
| **weather.reset_cloud_config** | Resets cloud configuration. |
| **workshop.print_loaded_skins** | Lists all Steam Workshop skins currently loaded. |
| **world.monuments** | Lists all monuments and their locations. |
| **world.renderlabs** | Renders a PNG of the Underwater Labs floor. |
| **world.rendermap** | Renders a high-resolution PNG of the map. |
| **world.rendertunnels** | Renders a PNG of the tunnel network. |

---
© 2026 VoidLabs.
