# Description

## Bow and Quiver mod. Some tweaks available for archery. 50% chance to return arrows on hit (configurable). This mod is a work in progress with more quivers and features to come.

`Version checks with itself. If installed on the server, it will kick clients who do not have it installed.`

`This mod uses ServerSync, if installed on the server and all clients, it will sync all configs to client`

`This mod uses a file watcher. If the configuration file is not changed with BepInEx Configuration manager, but changed in the file directly on the server, upon file save, it will sync the changes to all clients.`

If you need more information you can find more info on the mod as more questions are asked on this mod's wiki page (
found on the wiki tab).
Link to wiki page if you're
lazy [BowsBeforeHoes Wiki](https://valheim.thunderstore.io/package/Azumatt/BowsBeforeHoes/wiki/)

---

### Compatible Mods

* Auga
* AzuExtendedPlayerInventory
* BowPlugin
* FirstPersonMode

### Additional Information

`Quivers do not take up a Utility slot!`

Quivers start out having 3 slots, and can be upgraded to have 6 slots. Each level of the item increases the amount of
slots by 1.

Storage for the quivers comes from having the
mod [Backpacks](https://valheim.thunderstore.io/package/Smoothbrain/Backpacks/) installed, if the mod is not installed,
the quiver are
essentially a visual indicator of your ammo and not really much more. By default, when using Thunderstore Mod Manager or
r2modman, Backpacks will be installed automatically.

#### Prefabs this mod adds, and their names:

* BBH_BlackForest_Quiver
* BBH_BlackForest_Bow
* BBH_Seeker_Quiver
* BBH_Seeker_Bow
* SeekerArrow
* BBH_Surtling_Bow
* BBH_OdinPlus_Quiver
* BBH_PlainsLox_Quiver
* TorchArrow
* MistTorchArrow

---

<details>
<summary><b>Installation Instructions</b></summary>

***You must have BepInEx installed correctly! I can not stress this enough.***

### Manual Installation

`Note: (Manual installation is likely how you have to do this on a server, make sure BepInEx is installed on the server correctly)`

1. **Download the latest release of BepInEx.**
2. **Extract the contents of the zip file to your game's root folder.**
3. **Download the latest release of BowsBeforeHoes from Thunderstore.io.**
4. **Extract the contents of the zip file to the `BepInEx/plugins` folder.**
5. **Launch the game.**

### Installation through r2modman or Thunderstore Mod Manager

1. **Install [r2modman](https://valheim.thunderstore.io/package/ebkr/r2modman/)
   or [Thunderstore Mod Manager](https://www.overwolf.com/app/Thunderstore-Thunderstore_Mod_Manager).**

   > For r2modman, you can also install it through the Thunderstore site.
   ![](https://i.imgur.com/s4X4rEs.png "r2modman Download")

   > For Thunderstore Mod Manager, you can also install it through the Overwolf app store
   ![](https://i.imgur.com/HQLZFp4.png "Thunderstore Mod Manager Download")
2. **Open the Mod Manager and search for "BowsBeforeHoes" under the Online
   tab. `Note: You can also search for "Azumatt" to find all my mods.`**

   `The image below shows VikingShip as an example, but it was easier to reuse the image.`

   ![](https://i.imgur.com/5CR5XKu.png)

3. **Click the Download button to install the mod.**
4. **Launch the game.**

</details>

<details><summary><b>Mod Images</b></summary>


![https://i.imgur.com/q0ZGfd5.png](https://i.imgur.com/q0ZGfd5.png)
![https://i.imgur.com/t9R43vm.png](https://i.imgur.com/t9R43vm.png)
![https://i.imgur.com/3KFiqb8.png](https://i.imgur.com/3KFiqb8.png)
![https://i.imgur.com/PFvfMeg.png](https://i.imgur.com/PFvfMeg.png)

</details>

<details><summary><b>Configuration Options</b></summary>

`1 - General`

Lock Configuration [Synced with Server]

* If on, the configuration is locked and can be changed by server admins only.
    * Default Value: On

`2 - Bow Zoom`

Enable Bow Zoom [Synced with Server]

* Enable the zooming with bow.
    * Default Value: On

Automatic Bow Zoom [Synced with Server]

* Zoom while drawing bow automatically.
    * Default Value: Off

Zoom Factor [Synced with Server]

* Max zoom.
    * Default Value: 2

Bow Zoom Constant Time [Synced with Server]

* Constant time while zooming. '1' is default and recommended. All values less than or equal to 0 are ignored and
  default value is used.
    * Default Value: 1

Stay In-Zoom Time [Synced with Server]

* Set the max time of staying on zoom while holding RMB after releasing an arrow.
    * Default Value: 2

`3 - Keyboard Shortcuts`

Bow Zoom Hotkey [Synced with Server]

* Mouse0: Left Click, Mouse1: Right Click, Mouse2: Middle Click. For the other
  inputs: https://docs.unity3d.com/ScriptReference/KeyCode.html
    * Default Value: Mouse1

Bow Draw Cancel Hotkey [Synced with Server]

* Mouse0: Left Click, Mouse1: Right Click, Mouse2: Middle Click. For the other
  inputs: https://docs.unity3d.com/ScriptReference/KeyCode.html
    * Default Value: E

`4 - Other`

Enable Crosshair [Synced with Server]

* If off, hide the crosshair from view when not drawing a bow.
    * Default Value: On

Enable Bow Crosshair [Synced with Server]

* If off, hide the crosshair from view while drawing a bow.
    * Default Value: On

Spawn Arrow Chance [Synced with Server]

* The chance, per shot arrow, that you will return that arrow after shooting it. 0.5 is 50% chance.
    * Default Value: 0.5

Enable Bow Draw Movement Speed Reduction [Synced with Server]

* Set walk speed while drawing bow.
    * Default Value: On

`5 - Quiver`

Quiver Scale [Not Synced with Server]

* Scale of the quiver on the player's back.
    * Default Value: {"x":1.0,"y":1.0,"z":1.0}

Quiver Position [Not Synced with Server]

* Position of the quiver on the player's back. Uses local position.
    * Default Value: {"x":1.0,"y":1.0,"z":1.0}

Quiver Rotation [Not Synced with Server]

* Rotation of the quiver on the player's back.
    * Default Value: {"x":0.0,"y":180.0,"z":-20.0}

Quiver Attach Point [Synced with Server]

* Attach point of the quiver. This will have more functionality in the future by working in unison with scaling.
    * Default Value: BackShield_attach

`6 - Quiver Bar`

Scale [Synced with Server]

* Adjusts the hotkey's bar size.
    * Default Value: 80

OffsetX [Synced with Server]

* Adjust the hotkey's bar horizontal position (left/right).
    * Default Value: -600

OffsetY [Synced with Server]

* Adjust the hotkey's bar vertical position (down/up).
    * Default Value: 80

Modifier [Synced with Server]

* Key modifier to use the quivers.
    * Default Value: LeftShift

`Black Forest Quiver`

Add To Trader [Synced with Server]

* Enable/Disable Black Forest Quiver in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Black Forest Quiver in the trader
    * Default Value: 300

Stack [Synced with Server]

* Stack size of Black Forest Quiver in the trader. Also known as the number of items sold by a trader in one
  transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Black Forest Quiver in the trader
    * Default Value: defeated_eikthyr

`Black Forest Bow`

Add To Trader [Synced with Server]

* Enable/Disable Black Forest Bow in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Black Forest Bow in the trader
    * Default Value: 400

Stack [Synced with Server]

* Stack size of Black Forest Bow in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Black Forest Bow in the trader
    * Default Value: defeated_eikthyr

Crafting Station [Synced with Server]

* Crafting station where Black Forest Bow is available.
    * Default Value: Workbench

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Black Forest Bow.
    * Default Value: 2

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair Black Forest Bow.
    * Default Value: 5

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Black Forest Bow
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Black Forest Bow. Only works, if
  Require Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Black Forest Bow
    * Default Value: RoundLog:2,DeerHide:1,TrollHide:1

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade Black Forest Bow
    * Default Value: DeerHide:2,TrollHide:1

Drops from [Synced with Server]

* Black Forest Bow drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Black Forest Bow.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of Black Forest Bow.
    * Default Value: 0

Durability [Synced with Server]

* Durability of Black Forest Bow.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of Black Forest Bow.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of Black Forest Bow.
    * Default Value: -0.05

Block Armor [Synced with Server]

* Block armor of Black Forest Bow.
    * Default Value: 3

Block Armor per Level [Synced with Server]

* Block armor per level for Black Forest Bow.
    * Default Value: 0

Block Force [Synced with Server]

* Block force of Black Forest Bow.
    * Default Value: 0

Block Force per Level [Synced with Server]

* Block force per level for Black Forest Bow.
    * Default Value: 0

Parry Bonus [Synced with Server]

* Parry bonus of Black Forest Bow.
    * Default Value: 1.5

Knockback [Synced with Server]

* Knockback of Black Forest Bow.
    * Default Value: 20

Backstab Bonus [Synced with Server]

* Backstab bonus of Black Forest Bow.
    * Default Value: 3

Attack Stamina [Synced with Server]

* Attack stamina of Black Forest Bow.
    * Default Value: 0

True Damage [Synced with Server]

* True damage dealt by Black Forest Bow.
    * Default Value: 0

True Damage Per Level [Synced with Server]

* True damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Slash Damage [Synced with Server]

* Slash damage dealt by Black Forest Bow.
    * Default Value: 0

Slash Damage Per Level [Synced with Server]

* Slash damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Pierce Damage [Synced with Server]

* Pierce damage dealt by Black Forest Bow.
    * Default Value: 47

Pierce Damage Per Level [Synced with Server]

* Pierce damage dealt increase per level for Black Forest Bow.
    * Default Value: 3

Blunt Damage [Synced with Server]

* Blunt damage dealt by Black Forest Bow.
    * Default Value: 0

Blunt Damage Per Level [Synced with Server]

* Blunt damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Chop Damage [Synced with Server]

* Chop damage dealt by Black Forest Bow.
    * Default Value: 0

Chop Damage Per Level [Synced with Server]

* Chop damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Pickaxe Damage [Synced with Server]

* Pickaxe damage dealt by Black Forest Bow.
    * Default Value: 0

Pickaxe Damage Per Level [Synced with Server]

* Pickaxe damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Fire Damage [Synced with Server]

* Fire damage dealt by Black Forest Bow.
    * Default Value: 0

Fire Damage Per Level [Synced with Server]

* Fire damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Poison Damage [Synced with Server]

* Poison damage dealt by Black Forest Bow.
    * Default Value: 5

Poison Damage Per Level [Synced with Server]

* Poison damage dealt increase per level for Black Forest Bow.
    * Default Value: 5

Frost Damage [Synced with Server]

* Frost damage dealt by Black Forest Bow.
    * Default Value: 0

Frost Damage Per Level [Synced with Server]

* Frost damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Lightning Damage [Synced with Server]

* Lightning damage dealt by Black Forest Bow.
    * Default Value: 0

Lightning Damage Per Level [Synced with Server]

* Lightning damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Spirit Damage [Synced with Server]

* Spirit damage dealt by Black Forest Bow.
    * Default Value: 0

Spirit Damage Per Level [Synced with Server]

* Spirit damage dealt increase per level for Black Forest Bow.
    * Default Value: 0

Projectiles [Synced with Server]

* Number of projectiles that Black Forest Bow shoots at once.
    * Default Value: 1

Burst Interval [Synced with Server]

* Time between the projectiles Black Forest Bow shoots at once.
    * Default Value: 0

Minimum Accuracy [Synced with Server]

* Minimum accuracy for Black Forest Bow.
    * Default Value: 20

Accuracy [Synced with Server]

* Accuracy for Black Forest Bow.
    * Default Value: 0

Minimum Velocity [Synced with Server]

* Minimum velocity for Black Forest Bow.
    * Default Value: 2

Velocity [Synced with Server]

* Velocity for Black Forest Bow.
    * Default Value: 60

Maximum Draw Time [Synced with Server]

* Time until Black Forest Bow is fully drawn at skill level 0.
    * Default Value: 2.5

Stamina Drain [Synced with Server]

* Stamina drain per second while drawing Black Forest Bow.
    * Default Value: 10

`Seeker Quiver`

Add To Trader [Synced with Server]

* Enable/Disable Seeker Quiver in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Seeker Quiver in the trader
    * Default Value: 1000

Stack [Synced with Server]

* Stack size of Seeker Quiver in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Seeker Quiver in the trader
    * Default Value: defeated_goblinking

Crafting Station [Synced with Server]

* Crafting station where Seeker Quiver is available.
    * Default Value: BlackForge

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Seeker Quiver.
    * Default Value: 1

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair Seeker Quiver.
    * Default Value: 4

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Seeker Quiver
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Seeker Quiver. Only works, if
  Require Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Seeker Quiver
    * Default Value: YggdrasilWood:1,Carapace:1,Mandible:4

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade Seeker Quiver
    * Default Value: YggdrasilWood:1,Carapace:1,Mandible:1

Drops from [Synced with Server]

* Seeker Quiver drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Seeker Quiver.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of Seeker Quiver.
    * Default Value: 0

Durability [Synced with Server]

* Durability of Seeker Quiver.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of Seeker Quiver.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of Seeker Quiver.
    * Default Value: -0.05

Armor [Synced with Server]

* Armor of Seeker Quiver.
    * Default Value: 15

Armor per Level [Synced with Server]

* Armor per level for Seeker Quiver.
    * Default Value: 1

Blunt Resistance [Synced with Server]

* Blunt resistance of Seeker Quiver.
    * Default Value: None

Slash Resistance [Synced with Server]

* Slash resistance of Seeker Quiver.
    * Default Value: None

Pierce Resistance [Synced with Server]

* Pierce resistance of Seeker Quiver.
    * Default Value: None

Fire Resistance [Synced with Server]

* Fire resistance of Seeker Quiver.
    * Default Value: None

Frost Resistance [Synced with Server]

* Frost resistance of Seeker Quiver.
    * Default Value: None

Lightning Resistance [Synced with Server]

* Lightning resistance of Seeker Quiver.
    * Default Value: None

Poison Resistance [Synced with Server]

* Poison resistance of Seeker Quiver.
    * Default Value: None

`Seeker Bow`

Add To Trader [Synced with Server]

* Enable/Disable Seeker Bow in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Seeker Bow in the trader
    * Default Value: 1100

Stack [Synced with Server]

* Stack size of Seeker Bow in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Seeker Bow in the trader
    * Default Value: defeated_goblinking

Crafting Station [Synced with Server]

* Crafting station where Seeker Bow is available.
    * Default Value: Workbench

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Seeker Bow.
    * Default Value: 2

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair Seeker Bow.
    * Default Value: 5

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Seeker Bow
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Seeker Bow. Only works, if Require
  Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Seeker Bow
    * Default Value: YggdrasilWood:3,Carapace:3,Wisp:1

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade Seeker Bow
    * Default Value: YggdrasilWood:1,Carapace:1

Drops from [Synced with Server]

* Seeker Bow drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Seeker Bow.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of Seeker Bow.
    * Default Value: 0

Durability [Synced with Server]

* Durability of Seeker Bow.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of Seeker Bow.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of Seeker Bow.
    * Default Value: -0.05

Block Armor [Synced with Server]

* Block armor of Seeker Bow.
    * Default Value: 3

Block Armor per Level [Synced with Server]

* Block armor per level for Seeker Bow.
    * Default Value: 0

Block Force [Synced with Server]

* Block force of Seeker Bow.
    * Default Value: 0

Block Force per Level [Synced with Server]

* Block force per level for Seeker Bow.
    * Default Value: 0

Parry Bonus [Synced with Server]

* Parry bonus of Seeker Bow.
    * Default Value: 1.5

Knockback [Synced with Server]

* Knockback of Seeker Bow.
    * Default Value: 20

Backstab Bonus [Synced with Server]

* Backstab bonus of Seeker Bow.
    * Default Value: 3

Attack Stamina [Synced with Server]

* Attack stamina of Seeker Bow.
    * Default Value: 0

True Damage [Synced with Server]

* True damage dealt by Seeker Bow.
    * Default Value: 0

True Damage Per Level [Synced with Server]

* True damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Slash Damage [Synced with Server]

* Slash damage dealt by Seeker Bow.
    * Default Value: 0

Slash Damage Per Level [Synced with Server]

* Slash damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Pierce Damage [Synced with Server]

* Pierce damage dealt by Seeker Bow.
    * Default Value: 47

Pierce Damage Per Level [Synced with Server]

* Pierce damage dealt increase per level for Seeker Bow.
    * Default Value: 3

Blunt Damage [Synced with Server]

* Blunt damage dealt by Seeker Bow.
    * Default Value: 0

Blunt Damage Per Level [Synced with Server]

* Blunt damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Chop Damage [Synced with Server]

* Chop damage dealt by Seeker Bow.
    * Default Value: 0

Chop Damage Per Level [Synced with Server]

* Chop damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Pickaxe Damage [Synced with Server]

* Pickaxe damage dealt by Seeker Bow.
    * Default Value: 0

Pickaxe Damage Per Level [Synced with Server]

* Pickaxe damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Fire Damage [Synced with Server]

* Fire damage dealt by Seeker Bow.
    * Default Value: 0

Fire Damage Per Level [Synced with Server]

* Fire damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Poison Damage [Synced with Server]

* Poison damage dealt by Seeker Bow.
    * Default Value: 5

Poison Damage Per Level [Synced with Server]

* Poison damage dealt increase per level for Seeker Bow.
    * Default Value: 5

Frost Damage [Synced with Server]

* Frost damage dealt by Seeker Bow.
    * Default Value: 0

Frost Damage Per Level [Synced with Server]

* Frost damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Lightning Damage [Synced with Server]

* Lightning damage dealt by Seeker Bow.
    * Default Value: 0

Lightning Damage Per Level [Synced with Server]

* Lightning damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Spirit Damage [Synced with Server]

* Spirit damage dealt by Seeker Bow.
    * Default Value: 0

Spirit Damage Per Level [Synced with Server]

* Spirit damage dealt increase per level for Seeker Bow.
    * Default Value: 0

Projectiles [Synced with Server]

* Number of projectiles that Seeker Bow shoots at once.
    * Default Value: 1

Burst Interval [Synced with Server]

* Time between the projectiles Seeker Bow shoots at once.
    * Default Value: 0

Minimum Accuracy [Synced with Server]

* Minimum accuracy for Seeker Bow.
    * Default Value: 20

Accuracy [Synced with Server]

* Accuracy for Seeker Bow.
    * Default Value: 0

Minimum Velocity [Synced with Server]

* Minimum velocity for Seeker Bow.
    * Default Value: 2

Velocity [Synced with Server]

* Velocity for Seeker Bow.
    * Default Value: 60

Maximum Draw Time [Synced with Server]

* Time until Seeker Bow is fully drawn at skill level 0.
    * Default Value: 2.5

Stamina Drain [Synced with Server]

* Stamina drain per second while drawing Seeker Bow.
    * Default Value: 10

`Seeker Arrow`

Add To Trader [Synced with Server]

* Enable/Disable Seeker Arrow in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Seeker Arrow in the trader
    * Default Value: 500

Stack [Synced with Server]

* Stack size of Seeker Arrow in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Seeker Arrow in the trader
    * Default Value: defeated_goblinking

Crafting Station [Synced with Server]

* Crafting station where Seeker Arrow is available.
    * Default Value: BlackForge

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Seeker Arrow.
    * Default Value: 1

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Seeker Arrow
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Seeker Arrow. Only works, if Require
  Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Seeker Arrow
    * Default Value: Wood:1,Mandible:1

Drops from [Synced with Server]

* Seeker Arrow drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Seeker Arrow.
    * Default Value: 0.1

Trader Value [Synced with Server]

* Trader value of Seeker Arrow.
    * Default Value: 0

`Surtling Bow`

Add To Trader [Synced with Server]

* Enable/Disable Surtling Bow in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Surtling Bow in the trader
    * Default Value: 300

Stack [Synced with Server]

* Stack size of Surtling Bow in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Surtling Bow in the trader
    * Default Value: defeated_gdking

Crafting Station [Synced with Server]

* Crafting station where Surtling Bow is available.
    * Default Value: Workbench

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Surtling Bow.
    * Default Value: 2

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair Surtling Bow.
    * Default Value: 5

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Surtling Bow
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Surtling Bow. Only works, if Require
  Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Surtling Bow
    * Default Value: TrophyTheElder:1,SurtlingCore:10,Eitr:25

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade Surtling Bow
    * Default Value: Flametal:1,Eitr:5

Drops from [Synced with Server]

* Surtling Bow drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Surtling Bow.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of Surtling Bow.
    * Default Value: 0

Durability [Synced with Server]

* Durability of Surtling Bow.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of Surtling Bow.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of Surtling Bow.
    * Default Value: -0.05

Block Armor [Synced with Server]

* Block armor of Surtling Bow.
    * Default Value: 3

Block Armor per Level [Synced with Server]

* Block armor per level for Surtling Bow.
    * Default Value: 0

Block Force [Synced with Server]

* Block force of Surtling Bow.
    * Default Value: 0

Block Force per Level [Synced with Server]

* Block force per level for Surtling Bow.
    * Default Value: 0

Parry Bonus [Synced with Server]

* Parry bonus of Surtling Bow.
    * Default Value: 1.5

Knockback [Synced with Server]

* Knockback of Surtling Bow.
    * Default Value: 20

Backstab Bonus [Synced with Server]

* Backstab bonus of Surtling Bow.
    * Default Value: 3

Attack Stamina [Synced with Server]

* Attack stamina of Surtling Bow.
    * Default Value: 0

True Damage [Synced with Server]

* True damage dealt by Surtling Bow.
    * Default Value: 0

True Damage Per Level [Synced with Server]

* True damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Slash Damage [Synced with Server]

* Slash damage dealt by Surtling Bow.
    * Default Value: 0

Slash Damage Per Level [Synced with Server]

* Slash damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Pierce Damage [Synced with Server]

* Pierce damage dealt by Surtling Bow.
    * Default Value: 47

Pierce Damage Per Level [Synced with Server]

* Pierce damage dealt increase per level for Surtling Bow.
    * Default Value: 3

Blunt Damage [Synced with Server]

* Blunt damage dealt by Surtling Bow.
    * Default Value: 0

Blunt Damage Per Level [Synced with Server]

* Blunt damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Chop Damage [Synced with Server]

* Chop damage dealt by Surtling Bow.
    * Default Value: 0

Chop Damage Per Level [Synced with Server]

* Chop damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Pickaxe Damage [Synced with Server]

* Pickaxe damage dealt by Surtling Bow.
    * Default Value: 0

Pickaxe Damage Per Level [Synced with Server]

* Pickaxe damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Fire Damage [Synced with Server]

* Fire damage dealt by Surtling Bow.
    * Default Value: 0

Fire Damage Per Level [Synced with Server]

* Fire damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Poison Damage [Synced with Server]

* Poison damage dealt by Surtling Bow.
    * Default Value: 5

Poison Damage Per Level [Synced with Server]

* Poison damage dealt increase per level for Surtling Bow.
    * Default Value: 5

Frost Damage [Synced with Server]

* Frost damage dealt by Surtling Bow.
    * Default Value: 0

Frost Damage Per Level [Synced with Server]

* Frost damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Lightning Damage [Synced with Server]

* Lightning damage dealt by Surtling Bow.
    * Default Value: 0

Lightning Damage Per Level [Synced with Server]

* Lightning damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Spirit Damage [Synced with Server]

* Spirit damage dealt by Surtling Bow.
    * Default Value: 0

Spirit Damage Per Level [Synced with Server]

* Spirit damage dealt increase per level for Surtling Bow.
    * Default Value: 0

Projectiles [Synced with Server]

* Number of projectiles that Surtling Bow shoots at once.
    * Default Value: 1

Burst Interval [Synced with Server]

* Time between the projectiles Surtling Bow shoots at once.
    * Default Value: 0

Minimum Accuracy [Synced with Server]

* Minimum accuracy for Surtling Bow.
    * Default Value: 20

Accuracy [Synced with Server]

* Accuracy for Surtling Bow.
    * Default Value: 0

Minimum Velocity [Synced with Server]

* Minimum velocity for Surtling Bow.
    * Default Value: 2

Velocity [Synced with Server]

* Velocity for Surtling Bow.
    * Default Value: 60

Maximum Draw Time [Synced with Server]

* Time until Surtling Bow is fully drawn at skill level 0.
    * Default Value: 2.5

Stamina Drain [Synced with Server]

* Stamina drain per second while drawing Surtling Bow.
    * Default Value: 10

`OdinPlus Quiver`

Add To Trader [Synced with Server]

* Enable/Disable OdinPlus Quiver in the trader
    * Default Value: On

Price [Synced with Server]

* Price of OdinPlus Quiver in the trader
    * Default Value: 200

Stack [Synced with Server]

* Stack size of OdinPlus Quiver in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock OdinPlus Quiver in the trader
    * Default Value: defeated_gdking

Crafting Station [Synced with Server]

* Crafting station where OdinPlus Quiver is available.
    * Default Value: BlackForge

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft OdinPlus Quiver.
    * Default Value: 1

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair OdinPlus Quiver.
    * Default Value: 4

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft OdinPlus Quiver
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting OdinPlus Quiver. Only works, if
  Require Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft OdinPlus Quiver
    * Default Value: Thunderstone:10,YggdrasilWood:3,Flametal:2

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade OdinPlus Quiver
    * Default Value: Thunderstone:1,Carapace:1,Eitr:5

Drops from [Synced with Server]

* OdinPlus Quiver drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of OdinPlus Quiver.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of OdinPlus Quiver.
    * Default Value: 0

Durability [Synced with Server]

* Durability of OdinPlus Quiver.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of OdinPlus Quiver.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of OdinPlus Quiver.
    * Default Value: -0.05

Armor [Synced with Server]

* Armor of OdinPlus Quiver.
    * Default Value: 15

Armor per Level [Synced with Server]

* Armor per level for OdinPlus Quiver.
    * Default Value: 1

Blunt Resistance [Synced with Server]

* Blunt resistance of OdinPlus Quiver.
    * Default Value: None

Slash Resistance [Synced with Server]

* Slash resistance of OdinPlus Quiver.
    * Default Value: None

Pierce Resistance [Synced with Server]

* Pierce resistance of OdinPlus Quiver.
    * Default Value: None

Fire Resistance [Synced with Server]

* Fire resistance of OdinPlus Quiver.
    * Default Value: None

Frost Resistance [Synced with Server]

* Frost resistance of OdinPlus Quiver.
    * Default Value: None

Lightning Resistance [Synced with Server]

* Lightning resistance of OdinPlus Quiver.
    * Default Value: None

Poison Resistance [Synced with Server]

* Poison resistance of OdinPlus Quiver.
    * Default Value: None

`Lox Quiver`

Add To Trader [Synced with Server]

* Enable/Disable Lox Quiver in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Lox Quiver in the trader
    * Default Value: 400

Stack [Synced with Server]

* Stack size of Lox Quiver in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 1

Trader Required Global Key [Synced with Server]

* Required global key to unlock Lox Quiver in the trader
    * Default Value: defeated_bonemass

Crafting Station [Synced with Server]

* Crafting station where Lox Quiver is available.
    * Default Value: Forge

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Lox Quiver.
    * Default Value: 2

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair Lox Quiver.
    * Default Value: 5

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Lox Quiver
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Lox Quiver. Only works, if Require
  Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Lox Quiver
    * Default Value: FineWood:15,SerpentScale:5,LoxPelt:3

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade Lox Quiver
    * Default Value: SerpentScale:2,LoxPelt:1

Drops from [Synced with Server]

* Lox Quiver drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Lox Quiver.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of Lox Quiver.
    * Default Value: 0

Durability [Synced with Server]

* Durability of Lox Quiver.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of Lox Quiver.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of Lox Quiver.
    * Default Value: -0.05

Armor [Synced with Server]

* Armor of Lox Quiver.
    * Default Value: 15

Armor per Level [Synced with Server]

* Armor per level for Lox Quiver.
    * Default Value: 1

Blunt Resistance [Synced with Server]

* Blunt resistance of Lox Quiver.
    * Default Value: None

Slash Resistance [Synced with Server]

* Slash resistance of Lox Quiver.
    * Default Value: None

Pierce Resistance [Synced with Server]

* Pierce resistance of Lox Quiver.
    * Default Value: None

Fire Resistance [Synced with Server]

* Fire resistance of Lox Quiver.
    * Default Value: None

Frost Resistance [Synced with Server]

* Frost resistance of Lox Quiver.
    * Default Value: None

Lightning Resistance [Synced with Server]

* Lightning resistance of Lox Quiver.
    * Default Value: None

Poison Resistance [Synced with Server]

* Poison resistance of Lox Quiver.
    * Default Value: None

`Torch Arrow`

Add To Trader [Synced with Server]

* Enable/Disable Torch Arrow in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Torch Arrow in the trader
    * Default Value: 100

Stack [Synced with Server]

* Stack size of Torch Arrow in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 100

Trader Required Global Key [Synced with Server]

* Required global key to unlock Torch Arrow in the trader
    * Default Value: defeated_eikthyr

Crafting Station [Synced with Server]

* Crafting station where Torch Arrow is available.
    * Default Value: Workbench

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Torch Arrow.
    * Default Value: 2

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Torch Arrow
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Torch Arrow. Only works, if Require
  Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Torch Arrow
    * Default Value: Wood:1,DeerHide:2

Drops from [Synced with Server]

* Torch Arrow drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Torch Arrow.
    * Default Value: 0.1

Trader Value [Synced with Server]

* Trader value of Torch Arrow.
    * Default Value: 0

`Mist Torch Arrow`

Add To Trader [Synced with Server]

* Enable/Disable Mist Torch Arrow in the trader
    * Default Value: On

Price [Synced with Server]

* Price of Mist Torch Arrow in the trader
    * Default Value: 100

Stack [Synced with Server]

* Stack size of Mist Torch Arrow in the trader. Also known as the number of items sold by a trader in one transaction.
    * Default Value: 100

Trader Required Global Key [Synced with Server]

* Required global key to unlock Mist Torch Arrow in the trader
    * Default Value: defeated_goblinking

Crafting Station [Synced with Server]

* Crafting station where Mist Torch Arrow is available.
    * Default Value: Workbench

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Mist Torch Arrow.
    * Default Value: 2

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Mist Torch Arrow
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Mist Torch Arrow. Only works, if
  Require Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Mist Torch Arrow
    * Default Value: Wood:1,Eitr:2

Drops from [Synced with Server]

* Mist Torch Arrow drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Mist Torch Arrow.
    * Default Value: 0.1

Trader Value [Synced with Server]

* Trader value of Mist Torch Arrow.
    * Default Value: 0

`Black Forest Quiver`

Crafting Station [Synced with Server]

* Crafting station where Black Forest Quiver is available.
    * Default Value: Workbench

Custom Crafting Station [Synced with Server]

*
    * Default Value:

Crafting Station Level [Synced with Server]

* Required crafting station level to craft Black Forest Quiver.
    * Default Value: 2

Maximum Crafting Station Level [Synced with Server]

* Maximum crafting station level to upgrade and repair Black Forest Quiver.
    * Default Value: 5

Require only one resource [Synced with Server]

* Whether only one of the ingredients is needed to craft Black Forest Quiver
    * Default Value: Off

Quality Multiplier [Synced with Server]

* Multiplies the crafted amount based on the quality of the resources when crafting Black Forest Quiver. Only works, if
  Require Only One Resource is true.
    * Default Value: 1

Crafting Costs [Synced with Server]

* Item costs to craft Black Forest Quiver
    * Default Value: HardAntler:1,DeerHide:3

Upgrading Costs [Synced with Server]

* Item costs per level to upgrade Black Forest Quiver
    * Default Value: RoundLog:2,LeatherScraps:5,DeerHide:3

Drops from [Synced with Server]

* Black Forest Quiver drops from this creature.
    * Default Value:

Weight [Synced with Server]

* Weight of Black Forest Quiver.
    * Default Value: 1.5

Trader Value [Synced with Server]

* Trader value of Black Forest Quiver.
    * Default Value: 0

Durability [Synced with Server]

* Durability of Black Forest Quiver.
    * Default Value: 100

Durability per Level [Synced with Server]

* Durability gain per level of Black Forest Quiver.
    * Default Value: 50

Movement Speed Modifier [Synced with Server]

* Movement speed modifier of Black Forest Quiver.
    * Default Value: -0.05

Armor [Synced with Server]

* Armor of Black Forest Quiver.
    * Default Value: 15

Armor per Level [Synced with Server]

* Armor per level for Black Forest Quiver.
    * Default Value: 1

Blunt Resistance [Synced with Server]

* Blunt resistance of Black Forest Quiver.
    * Default Value: None

Slash Resistance [Synced with Server]

* Slash resistance of Black Forest Quiver.
    * Default Value: None

Pierce Resistance [Synced with Server]

* Pierce resistance of Black Forest Quiver.
    * Default Value: None

Fire Resistance [Synced with Server]

* Fire resistance of Black Forest Quiver.
    * Default Value: None

Frost Resistance [Synced with Server]

* Frost resistance of Black Forest Quiver.
    * Default Value: None

Lightning Resistance [Synced with Server]

* Lightning resistance of Black Forest Quiver.
    * Default Value: None

Poison Resistance [Synced with Server]

* Poison resistance of Black Forest Quiver.
    * Default Value: None

</details>

<br><br><br>

`Feel free to reach out to me on discord if you need manual download assistance.`

# Author Information

### Azumatt

`DISCORD:` Azumatt#2625

`STEAM:` https://steamcommunity.com/id/azumatt/

For Questions or Comments, find me in the Odin Plus Team Discord or in mine:

[![https://i.imgur.com/XXP6HCU.png](https://i.imgur.com/XXP6HCU.png)](https://discord.gg/Pb6bVMnFb2)
<a href="https://discord.gg/pdHgy6Bsng"><img src="https://i.imgur.com/Xlcbmm9.png" href="https://discord.gg/pdHgy6Bsng" width="175" height="175"></a>