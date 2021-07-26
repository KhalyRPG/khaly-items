# Items
> Repository where the default and customized server items are stored.
### Item types
There are different types of items, you can find them here and in the archive.
> Types:
```
WEAPON = Arma
ARMOR = Armadura
WAND = Varita
BOW = Arco
SHIELD = Escudo
FOOD = Comida
ACCESSORY = Accesorio
ELEMENT = Elemento
GEM = Gema
MINERAL = Mineral
ELYTRA = Elitros
ORB = Orbe
OTHER = Otro
```
### Rarities
Rarities define how rare the item is, so here I will leave the list for you.
```
COMMON = Comun
UNCOMMON = No comun
RARE = Raro
EPIC = Epico
FABLED = Legendario
MYTHIC = Mitico
SPECIAL = Especial
```
### Materials
The material defines what the object is, such as a block of iron or a gold ingot, you can find the [list of all items here](https://helpch.at/docs/1.12.2/index.html?org/bukkit/Material.html)
### Attributes
We have a list of attributes that apply to the item, such as damage, strength, intelligence, etc. This is the list of all the current ones:
```
intelligence = gives intelligence to the wearer, intelligence defines the mana.
strength = gives strength to the wearer, increases the damage caused.
damage = damage caused by the item.
luck = the luck of the item.
defense = the defense offered by the item (only works on armor)
health = health provided by the item (only works on armor)
healthRegen = the amount of health the item will regenerate
manaRegen = the amount of mana the item will regenerate
ability = The ability of the item (must be text and an existing ability)
```
### Extra data
The "extra" in the itemstack section is the item in base64, this is saved to save the items that have custom tags excluding "khaly", if the item is a textured head, the item in base64 will be initialized in code and so it does not lose the texture that you already have.
<br>
In the "default-items" file the default items will be saved, if there is an item without data and it is saved in that file, it will be updated, to achieve this, the name of the section must be the same as the [Material](https://helpch.at/docs/1.12.2/index.html?org/bukkit/Material.html), and the rest, there are already examples. You can add attributes to the items.
### Contribute
You can contribute by making a [pull request](https://github.com/KhalyRPG/khaly-items/pulls) in [this repository](https://github.com/KhalyRPG/khaly-items/).