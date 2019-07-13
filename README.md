# spigot-minecraft-plugin-commons
A collection of files used in the development process of plugins for Minecraft Spigot 1.14.3


https://www.spigotmc.org/wiki/spigot-plugin-development/

Build Tools: https://hub.spigotmc.org/jenkins/job/BuildTools/101/
Spigot API Reference: https://hub.spigotmc.org/javadocs/spigot/overview-summary.html

https://www.spigotmc.org/wiki/spigot-installation/#windows


# Development


In Eclipse add external jar to your projects build path (properties -> build path -> library -> add external jar). The name of this file is spigot-api-1.14.3-R0.1-SNAPSHOT-shaded.
After that, all classes from spigot and bukkit can be used for development.

For overview and good intro tutorial, see https://www.justdave.net/dave/2015/05/04/how-to-write-a-minecraftbukkit-plugin-for-spigot-1-8/

Once you decide to test your plugin, go to File -> Export -> JAR and export your plugin to SpigotServer/plugins directory. After that you can skip step 1 in "Run and test plugin locally".

# Run and test plugin locally


1. Add plugins .jar file to plugins directory in SpigotServer/plugins
2. Start Spigot server by running SpigotServer/start.bat
3. Start minecraft and connect to local server 
4. Run plugins functionality and see if it works :)!