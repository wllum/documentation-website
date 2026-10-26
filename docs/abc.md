`Bananas
*`This is a test line` - banana fish	
**Attribute Arguments**

* `<argument>` - Required Argument
* `{optional}` - Optional Argument

Tool Attribute         | Description                                               | Applies | Usage
-----------------------|-----------------------------------------------------------|:---------:|:-----------------------------------------------------:
`AUTO_COLLECT`         | automatically teleports items into the player's inventory | GLOBAL  | `AUTO_COLLECT`
`AUTO_SELL`            | automatically sells item in tool inventory(requires vault)     | GLOBAL  | `AUTO_SELL`
`DROP_BOOST`           | increases the amount of items dropped                     | GLOBAL  | `AUTO_COLLECT`
`DROP_ITEM`            | drops an item when activated                              | GLOBAL  | `DROP_ITEM`
`EXPERIENCE_MULTIPLIER`| makes the tool gain experience faster                     | GLOBAL  | `EXPERIENCE_MULTIPLIER:<multiplier>`
`MESSAGE`              | messages the player                                       | GLOBAL  | 
`POTION_EFFECT`        | gives the player a potion effect while holding the item   | GLOBAL  |
`UNBREAKABLE`          | prevents the item from losing durability                  | GLOBAL  | `AUTO_COLLECT`
`BLACKSMITH`           | restores durability while mining                          | PICKAXE |
`BLASTING`             | destroys all blocks in a radius                           | PICKAXE | `BLASTING:<radius>:{radius}`
`DESTROY_ORES`         | when true, the blasting tools will break ores             | PICKAXE | 
`FORGE`                | restores durability to all items in inventory             | PICKAXE |
`GEOLOGIST`            | chance to discover bonus minerals when mining stone       | PICKAXE |
`OBSIDIAN_DESTROYER`   | chance to instantly break obsidian                        | PICKAXE |
`ORE_SENSE`            | creates a path to nearby ores                             | PICKAXE |
`SMELT_ORES`           | automatically smelts ores when broken                     | PICKAXE |
`VEIN_MINER`           | mines all ores in a vein                                  | PICKAXE |
`AREA_HARVEST`         | Harvests crops in an area                                 | PICKAXE | `AREA_HARVEST:<radius>:<chance>`
`BOUNTIFUL_HARVEST`    | generates extra crops                                     | PICKAXE | `BOUNTIFUL_HARVEST:<multiplier>:<chance>`
`CHAIN_HARVEST`        | destroys crops in a snake like manner                     | PICKAXE | `CHAIN_HARVEST:<max_blocks>:<chance>`
`CROP_FORTUNE`         | increases the amount of crops dropped by crops            | PICKAXE | `CROP_FORTUNE:<amount>`
`FERTILE_TOUCH`        | upon harvesting a crop, nearby crops have a chance to advance in growth | PICKAXE | `FERITLE_TOUCH:<power>:<radius>:<max_crops>:<chance>`
`INSTANT_HARVEST`      | harvests any crop type instantly
`INSTANT_REGROWTH`     | chance to instantly regrow a broken crop                  | PICKAXE | `INSTANT_REGROWTH:<chance>`
`REJUVENATING_PULSE`   | creates a circle that grows nearby crops when activated   | PICKAXE | `REJUVINATING_PULSE:<power>:<radius>:<duration>:<chance>:<cooldown>`
`REPLANT_SEEDS`        | Automatically replant seeds if they are in the player's inventory | PICKAXE | `REPLANT_SEEDS:<chance>`
`REQUIRE_MATURE`       | when true, allows a harvester tool to only break fully grown crops | PICKAXE | `REQUIRE_MATURE:<true/false>`