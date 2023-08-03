# Choices Explain
Why are some configuration options set to what they are?
___
## Global Configuration
* ### server-reloading
    * ##### disable-commands
        - **default**: true
        - **reason**: There has been issues around reloading the server whilst it is running. 
      Graphite does currently disable any server related reload commands in Bukkit[^1] and other flavours.[^2]
      There are plans to allow them back for server flavours but disable `bukkit:reload`.

[^1]: https://github.com/GraphiteMC/Graphite/blob/ver/1.20.1/patches/api/0002-Disable-Reload-Commands.patch
[^2]: https://github.com/GraphiteMC/Graphite/blob/ver/1.20.1/patches/server/0003-Disable-Reload-Commands.patch