# PoE2 0.5.0 Projectile, Chain, Fork, and Extra Projectile Mechanics

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Global Projectile Rules

- Skills with fixed projectile counts can now benefit from effects that redirect projectile-count modifiers to another value, such as Ricochet III Support. [L468](../poe2-0.5.0-return-of-the-ancients.md#L468)
- Eye of Winter now describes its shard projectiles per second while in flight, and that count can be modified by additional projectiles. [L484](../poe2-0.5.0-return-of-the-ancients.md#L484)
- Several bug fixes target projectile-count conversion and stats that should apply to rain-of-arrows-like skills. [L759-L760](../poe2-0.5.0-return-of-the-ancients.md#L759-L760)

## Chain and Beam Mechanics

- Lightning Arrow beams can no longer chain multiple times onto the same target. [L495](../poe2-0.5.0-return-of-the-ancients.md#L495)
- Rolling Magma now chains more at all gem levels. [L507](../poe2-0.5.0-return-of-the-ancients.md#L507)
- Levinstone now grants Lightning Skills Chain +1 instead of +1 to all Lightning Skills. [L577](../poe2-0.5.0-return-of-the-ancients.md#L577)
- Warden and Guardian Bow implicits now grant 25-35% chance to chain an additional time. [L609](../poe2-0.5.0-return-of-the-ancients.md#L609)
- Beam skills now correctly receive some additional-chain stats. [L761](../poe2-0.5.0-return-of-the-ancients.md#L761)
- Terrain-chain tracking was fixed to prevent some projectiles from chaining forever from terrain. [L789](../poe2-0.5.0-return-of-the-ancients.md#L789)
- Arc no longer gets extra chains regardless of Lightning Infusion consumption. [L826](../poe2-0.5.0-return-of-the-ancients.md#L826)
- Volt Support no longer incorrectly has the Chaining tag. [L833](../poe2-0.5.0-return-of-the-ancients.md#L833)

## Fork and Additional Projectile Mechanics

- Stag Idol now grants projectiles a chance to Fork from helmets, and its bonded modifier grants chance for an additional projectile when forking. [L659](../poe2-0.5.0-return-of-the-ancients.md#L659)
- Death's Harp changes from Bow Attacks Fire 3 Additional Arrows to high Surpassing chance to fire an additional arrow. [L568](../poe2-0.5.0-return-of-the-ancients.md#L568)
- Quivers gain Surpassing chance to fire an additional Arrow modifiers. [L619](../poe2-0.5.0-return-of-the-ancients.md#L619)
- The Waystone modifier that granted Extra Projectiles to Monsters has been disabled. [L968](../poe2-0.5.0-return-of-the-ancients.md#L968)
- Surpassing chance to fire an additional Arrow no longer causes Lightning Rod arrow to fire to an incorrect location. [L838](../poe2-0.5.0-return-of-the-ancients.md#L838)

## Salvo, Seals, and Projectile Supports

- Unleash, Expand, Salvo, and Freezing Salvo now share standardized Seal mechanics, and Seal-granting supports consistently have the Seal category. [L525](../poe2-0.5.0-return-of-the-ancients.md#L525)
- Freezing Salvo and Salvo Support can now gain Seals while the relevant skill is being performed. [L526](../poe2-0.5.0-return-of-the-ancients.md#L526)
- Salvo Support now gains a Seal every 1 second up to 6, with one projectile per Seal, rather than every 2 seconds up to 3 with two projectiles per Seal. [L527](../poe2-0.5.0-return-of-the-ancients.md#L527)
- Freezing Salvo has lower Chill and Freeze Buildup scaling. [L489](../poe2-0.5.0-return-of-the-ancients.md#L489)

## Crossbow, Bolt, and Bow Skill Changes

- Fragmentation Rounds quality now grants extra Fragments per Shot rather than more Physical Damage. [L488](../poe2-0.5.0-return-of-the-ancients.md#L488)
- Snipe has adjusted damage and explosion values, lower unique-enemy explosion scaling, and a slightly smaller Icy Blast explosion radius. [L512](../poe2-0.5.0-return-of-the-ancients.md#L512)
- Arjun's Medal now has a lower chance to load a bolt on supported-skill killing blow. [L529](../poe2-0.5.0-return-of-the-ancients.md#L529)
- Ratha's Assault loads fewer bolts on dodge and grants lower attack speed. [L549](../poe2-0.5.0-return-of-the-ancients.md#L549)
- Projectile Skill level modifiers on attack weapons and quivers were reduced. [L614-L617](../poe2-0.5.0-return-of-the-ancients.md#L614-L617)

## Projectile and Targeting Bug Fixes

- Glacial Bolt ice crystal damage calculations were fixed in some cases, and projectiles no longer ignore Ice Crystals from Frozen Locus. [L783](../poe2-0.5.0-return-of-the-ancients.md#L783), [L808](../poe2-0.5.0-return-of-the-ancients.md#L808)
- Tactician's Cannons, Ready! now works with Molten Blast, Rolling Magma, Oil Barrage, and Power Charged Falling Thunder. [L785](../poe2-0.5.0-return-of-the-ancients.md#L785)
- Ice Nova can no longer originate from Frostbolt while cascading sideways. [L975](../poe2-0.5.0-return-of-the-ancients.md#L975)
- Lightning Warp target priority was fixed. [L835](../poe2-0.5.0-return-of-the-ancients.md#L835)
- Arbiter of Ash projectiles no longer turn invisible when created too far from the player. [L814](../poe2-0.5.0-return-of-the-ancients.md#L814)
- Summoning Circles no longer block projectiles after the boss is defeated and they crumble. [L846](../poe2-0.5.0-return-of-the-ancients.md#L846)
- Parry now says all hits can be parried rather than only strikes and projectiles. [L857](../poe2-0.5.0-return-of-the-ancients.md#L857)

## Practical Read

- Projectile builds need to retest all "fixed projectile count" and "projectile modifiers apply to another value" interactions; several bug fixes suggest prior behavior was inconsistent.
- Chain has both buffs and constraints: Rolling Magma and some items improve chain access, but Lightning Arrow and terrain-chain behavior are tightened.
- Extra-arrow scaling shifts toward Surpassing chance rather than guaranteed flat extra arrows in some item slots.
