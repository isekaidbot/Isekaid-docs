# Items and Pets

## Weapons and Armor

* `$inventory` - open the inventory, the numbers shown on the left are the ids
    - you can add filters to the inventory to filter by name, rarity, rank or filter out certain stats
      - Example: `$inventory --rarity common --rank 1 --name mithril --nostat dexterity,intelligence`
* `$view item [id]` - view a weapon or armor's details
* `$equip item [id]` - equip a weapon or armor
* `$sell equipment [id]` - sell an individual item
    - you can also do `$sell equipment all [rarity]` or `$sell equipment [id1,1d2,1d3]` to sell multiple items at once
* `$fuse [id1] [id2] ` - fuse two items together to create a stronger item, both items must have the same rank, rarity and name. Items may be fused up to rank 5
* `$upgrade [id]` - upgrade an item, you can only upgrade rank 5 items

## Pets
Pets can be obtained by doing `` $buy summon`` 

* `$view pet [pet id]` - view a pet's information
* `$equip pet [pet id]` - equip a pet to help you in battles
* `$feed [pet id] [item name] [item amount]` - feed a pet meat or fish to level it up and increase its damage
* `$sell pet [pet id]` - sell a pet to get some meat
  * `$sell pet all [rarity]` - sell all pets of a certain rarity
* `$petfuse [pet id 1] [pet id 2]` - fuse two pets together, both pets must be the same rarity, rank and reach level 50

## Artifacts
Artifacts can be obtained by clearing dungeons and grant different bonuses

* `$view artifact [artifact id]` - view an artifact's information
* `$equip artifact [artifact id]` - equip an artifact
* `$sell artifact [artifact id]` - sell an artifact
    - * `$sell artifact [id1,id2,id3]` - sell multiple artifacts

## Materials
Materials include ores, meat, and fish

* `$sell material [material name] [amount]` - sell materials for gold
