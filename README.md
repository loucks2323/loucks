27.02 23:18:37 [Server] Server thread/INFO 57hz issued server command: /modmode
27.02 23:18:37 [Server] Server thread/ERROR null
27.02 23:18:37 [Server] INFO org.bukkit.command.CommandException: Unhandled exception executing command 'modmode' in plugin SketchSM v1.9
27.02 23:18:37 [Server] INFO at org.bukkit.command.PluginCommand.execute(PluginCommand.java:47) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at org.bukkit.command.SimpleCommandMap.dispatch(SimpleCommandMap.java:149) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at org.bukkit.craftbukkit.v1_14_R1.CraftServer.dispatchCommand(CraftServer.java:710) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.PlayerConnection.handleCommand(PlayerConnection.java:1641) ~[?:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.PlayerConnection.a(PlayerConnection.java:1481) ~[?:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.PacketPlayInChat.a(PacketPlayInChat.java:47) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.PacketPlayInChat.a(PacketPlayInChat.java:1) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.PlayerConnectionUtils.lambda$0(PlayerConnectionUtils.java:19) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.TickTask.run(SourceFile:18) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.IAsyncTaskHandler.executeTask(SourceFile:144) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.IAsyncTaskHandlerReentrant.executeTask(SourceFile:23) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.IAsyncTaskHandler.executeNext(SourceFile:118) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.MinecraftServer.aX(MinecraftServer.java:910) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.MinecraftServer.executeNext(MinecraftServer.java:903) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.IAsyncTaskHandler.awaitTasks(SourceFile:127) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.MinecraftServer.sleepForTick(MinecraftServer.java:887) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at net.minecraft.server.v1_14_R1.MinecraftServer.run(MinecraftServer.java:820) [spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO at java.lang.Thread.run(Thread.java:748) [?:1.8.0_212]
27.02 23:18:37 [Server] INFO Caused by: java.lang.NoSuchMethodError: org.bukkit.Bukkit.getOnlinePlayers()[Lorg/bukkit/entity/Player;
27.02 23:18:37 [Server] INFO at com.craftingservers.sketch.utils.Utils.vanishPlayer(Utils.java:206) ~[?:?]
27.02 23:18:37 [Server] INFO at com.craftingservers.sketch.utils.Utils.applyModMode(Utils.java:166) ~[?:?]
27.02 23:18:37 [Server] INFO at com.craftingservers.sketch.commands.ModCommand.onCommand(ModCommand.java:31) ~[?:?]
27.02 23:18:37 [Server] INFO at org.bukkit.command.PluginCommand.execute(PluginCommand.java:45) ~[spigot-1.14.4.jar:git-Spigot-9de398a-9c887d4]
27.02 23:18:37 [Server] INFO ... 17 more
