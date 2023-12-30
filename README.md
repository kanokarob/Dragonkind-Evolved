![DRAGONKIND REBORN Logo](https://cdn.modrinth.com/data/yo1bGdBx/images/d7e949cb1f9d6667bd471ddd8e6f8916856a81ae.png)

# End Battle Reborn
Dragonkind Evolved builds upon the vanilla Ender Dragon fight. Rather than recreate the battle from scratch, it adds additional features and mechanics to increase difficulty and complexity while holding true to the general gameplay loop introduced by Vanilla.

Additionally, it incentivizes and rewards respawning the Ender Dragon. While the initial Ender Dragon fight does include changes, each successive battle will feature new Dragon types and End Crystal mechanics, both of which will continue to scale in difficulty as you slay more and more Ender Dragons.

## Ender Dragons
All Ender Dragons have more health than normal, and will have even more health depending on how many times it has been respawned. This corresponds to its difficulty level (Fledgeling, Powerful, Cruel, Immortal).

Whenever an Ender Dragon is respawned, it will gain a random Type, which changes or adds onto its behavior. This is denoted by the boss bar name as well as particles emitted by the Dragon. Some Dragon Types only appear at lower or higher difficulty levels.

<details>
  <summary>Shared Behavior</summary>
 
The Vanilla Ender Dragon has the following abilities at all times. When there are no more End Crystals left, all Dragon Types will begin to utilize these abilities in addition to their type-specific powers.

- **Summon End Rod Spikes.** These work similarly to Evoker Fangs, and are summoned when the Dragon is perching or preparing to perch, or as a last resort.
- **Ground all players.** This gives all players Levitation 128 for 20 seconds, effectively forcing them to (safely) land if flying with Elytra, and preventing them from taking off right away. If there aren't any flying players, it will try something else instead.
- **Summon Shulker Bullets.** This summons a ring of 12 Shulker Bullets around the Dragon, which will begin to target random players after a few moments. If there are already Shulker Bullets in the area, it will summon End Rod Spikes, instead.

</details>

<details>
  <summary>Dragon Types</summary>
  
**Zombified Dragon**
- Breath Clouds spread more and give Hunger + Nausea
- Periodically summons Zombie Servants
- Converts the ground to Mud as it flies

**Warped Dragon**
- Slower flying speed
- Periodically teleports around the arena
- Perches more often
- Breath Clouds give Poison + Slowness
- Breath Clouds don't dissipate until the fight ends

**Sculk Dragon**
- Breath Clouds give Darkness + Instant Damage
- Periodically attacks a player with a Sonic Boom attack
- Converts the ground to various Sculk blocks as it flies

**Frost Dragon**
- Breath Clouds give extreme Slowness + Slow Falling
- Converts the ground to snow and ice as it flies
- Periodically summons igloos
  - They can appear either around the Exit Portal, around up to 3 random players, or around up to 3 random End Crystals
  - They break on their own after 15 seconds
  - When they break, players trapped inside, or directly outside, will be damaged.

**Dragon Tyrant**
- Breath Clouds give Wither + Weakness
- Periodically summons Wither Skeleton Servants
- Converts the ground to Soul Sand and Soul Fires as it flies

**Skeletal Dragon**
- Perches very often
- Periodically summons Skeleton Servants, but at the cost of its health
- Is Invulnerable while Skeleton Servants are alive
- Slowly regenerates health even if there are no more End Crystals

**Blazing Dragon**
- Sets fires all along the ground beneath it
- Shoots fireballs more frequently
- Periodically summons Blaze Servants

**Elder Dragon**
- Has Glowing
- Breath Clouds give Blindness + Instant Damage
- Periodically casts a random spell on up to 3 random players
	- Summons Vex Servants
	- Summons Evoker Fangs
	- Launch into the air

**Dragon Wight**
- Silent, plays different ambient sound effects
- Much faster flying speed
- Shoots fireballs and charges at players more frequently
- Never perches

**The Last Dragon**
- Appears always and only as the 20th Dragon
- Breath Clouds spread more and give Levitation + extreme Weakness
- Converts the ground to Amethyst blocks as it flies
- Frequently force-grounds flying players
- Frequently shoots Amethyst Shard projectiles at up to 5 random players
- You can still summon more Dragons after this one
  
</details>

## End Crystals
Whenever an End Crystal is destroyed, it will regenerate. The maximum number of times each End Crystal can regenerate increases the higher the Ender Dragon difficulty, but for the first battle, the maximum is 2. They can also regenerate fewer than the max, but no less than once.

Whenever an End Crystal regenerates, it has a chance to possess at least 1 ability, up to a maximum of 3. At higher difficulties, End Crystals will be guaranteed to have at least 1 ability, and will start with an ability(s) rather than needing to regenerate first. Some abilities will only appear at higher difficulties, too. Most abilities emit particles to denote what they are.

<details>
  <summary>End Crystal Abilities</summary>
  
**Caged**
- Has a more secure cage around it

**Forcefield**
- Immune to projectiles

**Fiery**
- Burns players who get close

**Laser**
- Periodically shoots a laser at the closest player. Can be dodged by jumping

**Witch**
- Periodically gives a random neutral or negative effect to a player who doesn't have any effects

**Anti-Grav**
- Players nearby the Obsidian Pillar get Levitation

**Cursed**
- No particles. Destroying this crystal will damage the closest player quite a lot
  
</details>


## Rewards
So why would you want to fight such increasingly difficult Ender Dragons? Defeating an Ender Dragon now drops loot near the exit portal, which varies based on the Dragon Type. Additionally, this will always produce 1 custom Dragon-themed item. These items are powerful in their own right, and are more effective when used against Dragons. However, they all have a Curse of Deterioration, which means they all have durability and cannot have the Mending Enchantment applied to them.

<details>
  <summary>Custom Items</summary>
  
**Dragonslayer Sword**
- Deals 15 damage
- When it hits a mob, has a wider and stronger form of Sweeping Edge
- More effective against Dragons

**Dragon-Sinew Crossbow**
- Arrows deal 15 damage
- Arrows hit End Crystals and Ender Dragons from a greater distance (8 blocks)
- More effective against Dragons
- Can't pierce Forcefield End Crystals

**Dragontooth Pickaxe**
- More effective when mining Obsidian
- When a block is mined, the next 3 blocks in a row also get mined. This uses durability.
- Respects Unbreaking, if applied

**Dragonhide Armor (4 separate pieces)**
- Each piece gives more Armor value than Netherite. A full set provides 25 total Armor.
- Each piece gives extra Hearts. A full set provides 10 total hearts.
- While wearing a full set, deals a more powerful Thorns-like effect to Dragons only

**Dragonskull Shield**
- While blocking, causes Dragon breath clouds to instantly dissipate
- When this blocks a mob attack, knocks the mob back and deals them damage
- The above damage is more effective against Dragons

**Dragonscale Wings**
- Provides some Armor
- Gives 3 extra Hearts
- While flying, looking upwards gives a strong levitation effect

**Draconic Scepter**
- Right-click to launch a laser where you are looking, reaching up to 48 blocks away. It damages mobs near where it hits.
- The laser can pierce Forcefield End Crystals, and has a wider range to damage End Crystals and Dragons
- Right-click while Sneaking to charge up an area-of-effect spell around you, damaging nearby mobs when it finishes. This uses more durability than the laser.
- Both attacks are more effective against Dragons

**Dragon Eyes**
- Right click to equip as a helmet
- While wearing, hidden ores will be highlighted in the direction you're looking
- Slowly loses durability while wearing
  
</details>

If you already have one of the above items, you're less likely to get it again.

There are also advancements for killing each Type and each Difficulty of Dragon.
