# Getting Started - Installation
___
## 1. Obtaining the server Jar
Firstly we need to obtain the server Jar file to execute it, there are currently two ways
of doing this:

### a) Download
  * i) Downloading the latest version from [GitHub Releases here](https://github.com/GraphiteMC/Graphite/releases/tag/latest).

### Or

### b) Manual Compile
  * i) Clone the repository to your machine via:
    ```
    git clone https://github.com/GraphiteMC/Graphite.git
    ```
  * ii) Do not open in an IDE or anything else other than a command window and then run:
    ```
    ./gradlew applyPatches && ./gradlew createReobfBundlerJar
    ```
    The final Jar will be located in `build/libs`.
___
## 2. Running the server
To run the server you simply run it like any other Java application. 
In a terminal or script add the following line:

`java -Xms2G -Xmx2G -jar graphite.jar --nogui` 

Ensure that you replace "graphite.jar" with the appropriate Jar name.
The amount of RAM can be changed by editing the numbers in the `-Xms` and `-Xmx` arguments.

We suggest using [Aikar's Flags](https://docs.papermc.io/paper/aikars-flags) as well for optimised performance.
___
## 3. Configure your server
Graphite comes with multiple configuration files that you can edit to your liking.
  * Vanilla: [Vanilla configuration files (server.properties)](https://minecraft.fandom.com/wiki/Server.properties)
  * Bukkit: [Bukkit configuration files (bukkit.yml)](https://bukkit.fandom.com/wiki/Bukkit.yml)
  * Spigot: [Spigot configuration files (spigot.yml)](https://www.spigotmc.org/wiki/spigot-configuration/)
  * Paper:
    * [Global configuration file (Located in `config/paper-global.yml`)](https://docs.papermc.io/paper/reference/global-configuration)
    * [Default world configuration file (Located in `config/paper-world-defaults.yml`)](https://docs.papermc.io/paper/reference/world-configuration)
    * [Per-world configuration file (Located in `<world name>/paper-world.yml`)](https://docs.papermc.io/paper/reference/world-configuration)
  * Purpur: [Purpur configuration files (purpur.yml) ](https://purpurmc.org/docs/Configuration/)
  * Graphite
      * Global configuration file (Located in `config/graphite-global.yml`)
      * Default world configuration file (Located in `config/graphite-world-defaults.yml`)
      * Per-world configuration file (Located in `<world name>/graphite-world.yml`)