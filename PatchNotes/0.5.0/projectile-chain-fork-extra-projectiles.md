# PoE2 0.5.0 Projectile, Chain, Fork, and Extra Projectile Mechanics

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Global Projectile Rules

- Skills with fixed projectile counts can now benefit from effects that redirect projectile-count modifiers to another value, such as Ricochet III Support. [L466](../poe2-0.5.0-return-of-the-ancients.md#L466)
- Several bug fixes target projectile-count conversion and stats that should apply to rain-of-arrows-like skills. [L751-L752](../poe2-0.5.0-return-of-the-ancients.md#L751-L752)

## Chain and Beam Mechanics

- Lightning Arrow beams can no longer chain multiple times onto the same target. [L491](../poe2-0.5.0-return-of-the-ancients.md#L491)
- Rolling Magma now chains more at all gem levels. [L503](../poe2-0.5.0-return-of-the-ancients.md#L503)
- Levinstone now grants Lightning Skills Chain +1 instead of +1 to all Lightning Skills. [L573](../poe2-0.5.0-return-of-the-ancients.md#L573)
- Warden and Guardian Bow implicits now grant 25-35% chance to chain an additional time. [L605](../poe2-0.5.0-return-of-the-ancients.md#L605)
- Beam skills now correctly receive some additional-chain stats. [L753](../poe2-0.5.0-return-of-the-ancients.md#L753)
- Terrain-chain tracking was fixed to prevent some projectiles from chaining forever from terrain. [L781](../poe2-0.5.0-return-of-the-ancients.md#L781)
- Arc no longer gets extra chains regardless of Lightning Infusion consumption. [L818](../poe2-0.5.0-return-of-the-ancients.md#L818)
- Volt Support no longer incorrectly has the Chaining tag. [L825](../poe2-0.5.0-return-of-the-ancients.md#L825)

## Fork and Additional Projectile Mechanics

- Stag Idol now grants projectiles a chance to Fork from helmets, and its bonded modifier grants chance for an additional projectile when forking. [L655](../poe2-0.5.0-return-of-the-ancients.md#L655)
- Death's Harp changes from Bow Attacks Fire 3 Additional Arrows to high Surpassing chance to fire an additional arrow. [L564](../poe2-0.5.0-return-of-the-ancients.md#L564)
- Quivers gain Surpassing chance to fire an additional Arrow modifiers. [L615](../poe2-0.5.0-return-of-the-ancients.md#L615)
- The Waystone modifier that granted Extra Projectiles to Monsters has been disabled. [L945](../poe2-0.5.0-return-of-the-ancients.md#L945)
- Surpassing chance to fire an additional Arrow no longer causes Lightning Rod arrow to fire to an incorrect location. [L830](../poe2-0.5.0-return-of-the-ancients.md#L830)

## Salvo, Seals, and Projectile Supports

- Unleash, Expand, Salvo, and Freezing Salvo now share standardized Seal mechanics, and Seal-granting supports consistently have the Seal category. [L521](../poe2-0.5.0-return-of-the-ancients.md#L521)
- Freezing Salvo and Salvo Support can now gain Seals while the relevant skill is being performed. [L522](../poe2-0.5.0-return-of-the-ancients.md#L522)
- Salvo Support now gains a Seal every 1 second up to 6, with one projectile per Seal, rather than every 2 seconds up to 3 with two projectiles per Seal. [L523](../poe2-0.5.0-return-of-the-ancients.md#L523)
- Freezing Salvo has lower Chill and Freeze Buildup scaling. [L485](../poe2-0.5.0-return-of-the-ancients.md#L485)

## Crossbow, Bolt, and Bow Skill Changes

- Fragmentation Rounds quality now grants extra Fragments per Shot rather than more Physical Damage. [L484](../poe2-0.5.0-return-of-the-ancients.md#L484)
- Snipe has adjusted damage and explosion values, lower unique-enemy explosion scaling, and a slightly smaller Icy Blast explosion radius. [L508](../poe2-0.5.0-return-of-the-ancients.md#L508)
- Arjun's Medal now has a lower chance to load a bolt on supported-skill killing blow. [L525](../poe2-0.5.0-return-of-the-ancients.md#L525)
- Ratha's Assault loads fewer bolts on dodge and grants lower attack speed. [L545](../poe2-0.5.0-return-of-the-ancients.md#L545)
- Projectile Skill level modifiers on attack weapons and quivers were reduced. [L610-L613](../poe2-0.5.0-return-of-the-ancients.md#L610-L613)

## Projectile and Targeting Bug Fixes

- Glacial Bolt ice crystal damage calculations were fixed in some cases, and projectiles no longer ignore Ice Crystals from Frozen Locus. [L775](../poe2-0.5.0-return-of-the-ancients.md#L775), [L800](../poe2-0.5.0-return-of-the-ancients.md#L800)
- Tactician's Cannons, Ready! now works with Molten Blast, Rolling Magma, Oil Barrage, and Power Charged Falling Thunder. [L777](../poe2-0.5.0-return-of-the-ancients.md#L777)
- Ice Nova can no longer originate from Frostbolt while cascading sideways. [L952](../poe2-0.5.0-return-of-the-ancients.md#L952)
- Lightning Warp target priority was fixed. [L827](../poe2-0.5.0-return-of-the-ancients.md#L827)
- Arbiter of Ash projectiles no longer turn invisible when created too far from the player. [L806](../poe2-0.5.0-return-of-the-ancients.md#L806)
- Summoning Circles no longer block projectiles after the boss is defeated and they crumble. [L838](../poe2-0.5.0-return-of-the-ancients.md#L838)
- Parry now says all hits can be parried rather than only strikes and projectiles. [L849](../poe2-0.5.0-return-of-the-ancients.md#L849)

## Practical Read

- Projectile builds need to retest all "fixed projectile count" and "projectile modifiers apply to another value" interactions; several bug fixes suggest prior behavior was inconsistent.
- Chain has both buffs and constraints: Rolling Magma and some items improve chain access, but Lightning Arrow and terrain-chain behavior are tightened.
- Extra-arrow scaling shifts toward Surpassing chance rather than guaranteed flat extra arrows in some item slots.
