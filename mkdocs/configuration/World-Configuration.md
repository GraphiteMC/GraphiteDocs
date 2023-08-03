# World Configuration (graphite-world-defaults.yml)
___
### _version
* **Do not change this for any reason! Graphite uses this internally to help keep your config updated**
___
### misc
* #### fix-m-c31819
    - **default**: true
    - **description**: Fix Minecraft bug [MC-31819](https://bugs.mojang.com/browse/MC-31819)
* #### fix-m-c93018
    - **default**: true
    - **description**: Fix Minecraft bug [MC-93018](https://bugs.mojang.com/browse/MC-93018)
* #### recipes
    * #### raw-ore-block-smelting
        * #### raw-copper
             * ##### allow-blasting
                 - **default**: true
                 - **description**: Allow raw copper blocks to be smelted in a blast furnace 
             * ##### allow-furnace
                 - **default**: true
                 - **description**: Allow raw copper blocks to be smelted in a furnace
        * #### raw-gold
             * ##### allow-blasting
                 - **default**: true
                 - **description**: Allow raw gold blocks to be smelted in a blast furnace
             * ##### allow-furnace
                - **default**: true
                - **description**: Allow raw gold blocks to be smelted in a furnace
        * #### raw-iron
            * ##### allow-blasting
                - **default**: true
                - **description**: Allow raw iron blocks to be smelted in a blast furnace
            * ##### allow-furnace
                - **default**: true
                - **description**: Allow raw iron blocks to be smelted in a furnace
___
### mob-settings
* #### iron-golem-options
    * #### attack-creepers
        - **default**: false
        - **description**: Allow iron golems to attack Creepers. Very overpowered...