# Hello

This is a datapack for the Origins mod that adds a new origin, the Warden.
This is a work in progress, though is completely usable and *probably* balanced.
I plan on adding a third origin, the Sculkling, which will be a weaker impact two version of the Warden, maybe even making that the starting origin of which you evo into the warden.


# Origins

## <img src="./images/yellow.png" height="16" /> Sculkling (just an idea)

Selectable as an impact 2 starting origin

```diff
= Spawn in an ancient city
- Can't sleep, but can set spawn
- Blind
+ Show a glow effect around anything not crouching within a 10-block radius of you, and a 20-block radius around every catalyst within 16 blocks of you
+ Being within 8 blocks of a sculk catalyst will grant you the effects of the sonic pulse ability detailed below
+ Every 20 seconds, can send a "sonic pulse" to unblind self and give night vision for 4 seconds
+ Can dig through sculk and gain a large speed boost, while doing so you are completely invisible
- Very small, 1 block tall
- 50% less attack damage
- 30% less health (7 hearts)
- Being too far from any sort of sculk will give you negative effects depending on the distance
- The sun will burn you
```

## <img src="./images/red.png" height="16"> Warden

Selectable as an impact 3 starting origin

```diff
= Play a variety of sounds related to the warden under different circumstances
= Spawn in an ancient city
- Can't sleep, but can set spawn
- Blind
+ Being within 10 blocks of a sculk catalyst will grant you the effects of the sonic pulse ability detailed below
+ Every 10 seconds, can send a "sonic pulse" to unblind self and give night vision for 2.5 seconds
+ Every 25 seconds, can fire a sonic boom that reaches through blocks with a maximum range of 20 to hit a single entity and deal 20 explosion damage, ignoring armor
+ Show a glow effect around anything not crouching within a 10-block radius
+ 10 more attack damage
+ Full knockback resistance
+ 10 more health (5 hearts)
+ Jump 0.2 higher (??)
+ Move 1.2x faster
- 3 blocks tall
+ No fall damage (if sneaking)
- Carnivorous
+ Extra reach (1 block I think? Whatever the origins mod does in its default ability)
+ Immune to fire
- Can't wear armor (can wear cosmetics/elytra)
+ Don't activate sculk sensors unless standing on them
+ Dig through sculk and gain a 1.5x speed boost, while doing so you are completely invisible
+ While inside a sculk block you regenerate 1 heart every 1.5 seconds
= Mine faster, use 1.5x durability
```

## <img src="./images/red.png" height="16"> Master

Evolution from killing ender dragon as Warden

```diff
+ Show a glow effect around anything not crouching within a 25-block radius
- Get constant hunger effect when not in sunlight (will probably remove, no justification, need something else negative)
+ 18 more attack damage
+ Full knockback resistance
+ 20 more health (20 hearts)
+ Jump 0.3 higher (??)
+ Move 1.35x faster
- 3.5 blocks tall
+ Every 22.5 seconds, can fire a sonic boom that reaches through blocks with a maximum range of 30 to hit a single entity and deal 40 explosion damage, ignoring armor
- Carnivorous
= Ender particles like the Enderian origin
+ Extra reach (1 block I think? Whatever the origins mod does in its default ability)
+ Fire immunity
- Can't wear armor (can wear cosmetics/elytra)
+ Don't activate sculk sensors unless standing on them
+ Dig through sculk and gain a 1.5x speed boost, while doing so you are completely invisible
+ While inside a sculk block you regenerate 1 heart every 1.5 seconds
= Mine faster, use 1.5x durability
```
