# Global Configuration (graphite-global.yml)
___
### _version
* **Do not change this for any reason! Graphite uses this internally to help keep your config updated**
___
### recipes
* #### raw-ore-block-smelting
    * #### raw-copper
        * ##### blasting-cook-time
            - **default**: 900
            - **description**: The time in ticks for a raw copper block to smelted in a blast furnace
        * ##### blasting-experience
            - **default**: 6.3
            - **description**: Experience given when a raw copper block is smelted in a blast furnace
        * ##### furnace-cook-time
            - **default**: 1800
            - **description**: The time in ticks for a raw copper block to smelted in a furnace
        * ##### furnace-experience
            - **default**: 6.3
            - **description**: Experience given when a raw copper block is smelted in a furnace
    * #### raw-gold
        * ##### blasting-cook-time
            - **default**: 900
            - **description**: The time in ticks for a raw gold block to smelted in a blast furnace
        * ##### blasting-experience
            - **default**: 9.0
            - **description**: Experience given when a raw gold block is smelted in a blast furnace
        * ##### furnace-cook-time
            - **default**: 1800
            - **description**: The time in ticks for a raw gold block to smelted in a furnace
        * ##### furnace-experience
            - **default**: 9.0
            - **description**: Experience given when a raw gold block is smelted in a furnace
    * #### raw-iron
        * ##### blasting-cook-time
            - **default**: 900
            - **description**: The time in ticks for a raw iron block to smelted in a blast furnace
        * ##### blasting-experience
            - **default**: 6.3
            - **description**: Experience given when a raw iron block is smelted in a blast furnace
        * ##### furnace-cook-time
            - **default**: 1800
            - **description**: The time in ticks for a raw iron block to smelted in a furnace
        * ##### furnace-experience
            - **default**: 6.3
            - **description**: Experience given when a raw iron block is smelted in a furnace
___
### server-options
* #### server-reloading
    * ##### disable-commands
        - **default**: true
        - **description**: Disable any kind of reload command from working
    * ##### disabled-message
        - **default**: "&lt;click:open_url:'https://github.com/GraphiteMC/Graphite/wiki'><red>Reload
        commands have been disabled by Graphite. Please check the wiki for more information!&lt;/click>"
        - **description**: Message sent when a reload command is attempted to run
* #### server-security
    * ##### disable-chat-reports
        - **default**: false
        - **description**: Disable players from reporting chat messages to Mojang/Microsoft
    * ##### disable-root-running
        - **default**: true
        - **description**: Disable the server when it is ran as an administrative/root user
___