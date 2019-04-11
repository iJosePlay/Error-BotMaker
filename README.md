# Error-BotMaker
[17:59:46] [Server thread/INFO]: [BotMaker] Enabling BotMaker v3.5.1
[17:59:46] [Server thread/ERROR]: Error occurred while enabling BotMaker v3.5.1 (Is it up to date?)
java.lang.NoClassDefFoundError: net/minecraft/server/v1_8_R2/World
	at me.minkizz.botmaker.BotMaker.onEnable(BotMaker.java:112) ~[BotMaker.jar:?]
	at org.bukkit.plugin.java.JavaPlugin.setEnabled(JavaPlugin.java:321) ~[spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at org.bukkit.plugin.java.JavaPluginLoader.enablePlugin(JavaPluginLoader.java:340) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at me.incomprehendable.dev.pwp.transparentlisteners.PerWorldPluginLoader.enablePlugin(PerWorldPluginLoader.java:141) [PerWorldPlugins.jar:?]
	at org.bukkit.plugin.SimplePluginManager.enablePlugin(SimplePluginManager.java:405) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at org.bukkit.craftbukkit.v1_8_R3.CraftServer.loadPlugin(CraftServer.java:356) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at org.bukkit.craftbukkit.v1_8_R3.CraftServer.enablePlugins(CraftServer.java:316) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at net.minecraft.server.v1_8_R3.MinecraftServer.s(MinecraftServer.java:414) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at net.minecraft.server.v1_8_R3.MinecraftServer.k(MinecraftServer.java:378) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at net.minecraft.server.v1_8_R3.MinecraftServer.a(MinecraftServer.java:333) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at net.minecraft.server.v1_8_R3.DedicatedServer.init(DedicatedServer.java:263) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at net.minecraft.server.v1_8_R3.MinecraftServer.run(MinecraftServer.java:524) [spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at java.lang.Thread.run(Unknown Source) [?:1.8.0_191]
Caused by: java.lang.ClassNotFoundException: net.minecraft.server.v1_8_R2.World
	at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:91) ~[spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:86) ~[spigot.jar:git-Spigot-6c9b0a1-de5c261]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_191]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_191]
	... 13 more
