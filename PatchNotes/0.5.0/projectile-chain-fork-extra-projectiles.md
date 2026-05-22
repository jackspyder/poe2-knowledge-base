# PoE2 0.5.0 Projectile, Chain, Fork, and Extra Projectile Mechanics

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Global Projectile Rules

- Skills with fixed projectile counts can now benefit from effects that redirect projectile-count modifiers to another value, such as Ricochet III Support. [L439](../poe2-0.5.0-return-of-the-ancients.md#L439)
- Several bug fixes target projectile-count conversion and stats that should apply to rain-of-arrows-like skills. [L715-L716](../poe2-0.5.0-return-of-the-ancients.md#L715-L716)

## Chain and Beam Mechanics

- Lightning Arrow beams can no longer chain multiple times onto the same target. [L463](../poe2-0.5.0-return-of-the-ancients.md#L463)
- Rolling Magma now chains more at all gem levels. [L475](../poe2-0.5.0-return-of-the-ancients.md#L475)
- Levinstone now grants Lightning Skills Chain +1 instead of +1 to all Lightning Skills. [L542](../poe2-0.5.0-return-of-the-ancients.md#L542)
- Warden and Guardian Bow implicits now grant 25-35% chance to chain an additional time. [L572](../poe2-0.5.0-return-of-the-ancients.md#L572)
- Beam skills now correctly receive some additional-chain stats. [L717](../poe2-0.5.0-return-of-the-ancients.md#L717)
- Terrain-chain tracking was fixed to prevent some projectiles from chaining forever from terrain. [L730](../poe2-0.5.0-return-of-the-ancients.md#L730)
- Arc no longer gets extra chains regardless of Lightning Infusion consumption. [L766](../poe2-0.5.0-return-of-the-ancients.md#L766)
- Volt Support no longer incorrectly has the Chaining tag. [L773](../poe2-0.5.0-return-of-the-ancients.md#L773)

## Fork and Additional Projectile Mechanics

- Stag Idol now grants projectiles a chance to Fork from helmets, and its bonded modifier grants chance for an additional projectile when forking. [L622](../poe2-0.5.0-return-of-the-ancients.md#L622)
- Death's Harp changes from Bow Attacks Fire 3 Additional Arrows to high Surpassing chance to fire an additional arrow. [L534](../poe2-0.5.0-return-of-the-ancients.md#L534)
- Quivers gain Surpassing chance to fire an additional Arrow modifiers. [L582](../poe2-0.5.0-return-of-the-ancients.md#L582)
- Surpassing chance to fire an additional Arrow no longer causes Lightning Rod arrow to fire to an incorrect location. [L778](../poe2-0.5.0-return-of-the-ancients.md#L778)

## Salvo, Seals, and Projectile Supports

- Unleash, Expand, Salvo, and Freezing Salvo now share standardized Seal mechanics, and Seal-granting supports consistently have the Seal category. [L493](../poe2-0.5.0-return-of-the-ancients.md#L493)
- Freezing Salvo and Salvo Support can now gain Seals while the relevant skill is being performed. [L494](../poe2-0.5.0-return-of-the-ancients.md#L494)
- Salvo Support now gains a Seal every 1 second up to 6, with one projectile per Seal, rather than every 2 seconds up to 3 with two projectiles per Seal. [L495](../poe2-0.5.0-return-of-the-ancients.md#L495)
- Freezing Salvo has lower Chill and Freeze Buildup scaling. [L457](../poe2-0.5.0-return-of-the-ancients.md#L457)

## Crossbow, Bolt, and Bow Skill Changes

- Fragmentation Rounds quality now grants extra Fragments per Shot rather than more Physical Damage. [L456](../poe2-0.5.0-return-of-the-ancients.md#L456)
- Snipe has adjusted damage and explosion values, lower unique-enemy explosion scaling, and a slightly smaller Icy Blast explosion radius. [L480](../poe2-0.5.0-return-of-the-ancients.md#L480)
- Arjun's Medal now has a lower chance to load a bolt on supported-skill killing blow. [L497](../poe2-0.5.0-return-of-the-ancients.md#L497)
- Ratha's Assault loads fewer bolts on dodge and grants lower attack speed. [L515](../poe2-0.5.0-return-of-the-ancients.md#L515)
- Projectile Skill level modifiers on attack weapons and quivers were reduced. [L577-L580](../poe2-0.5.0-return-of-the-ancients.md#L577-L580)

## Projectile and Targeting Bug Fixes

- Glacial Bolt ice crystal damage calculations were fixed in some cases, and projectiles no longer ignore Ice Crystals from Frozen Locus. [L724](../poe2-0.5.0-return-of-the-ancients.md#L724), [L749](../poe2-0.5.0-return-of-the-ancients.md#L749)
- Tactician's Cannons, Ready! now works with Molten Blast, Rolling Magma, Oil Barrage, and Power Charged Falling Thunder. [L726](../poe2-0.5.0-return-of-the-ancients.md#L726)
- Lightning Warp target priority was fixed. [L775](../poe2-0.5.0-return-of-the-ancients.md#L775)
- Summoning Circles no longer block projectiles after the boss is defeated and they crumble. [L786](../poe2-0.5.0-return-of-the-ancients.md#L786)
- Parry now says all hits can be parried rather than only strikes and projectiles. [L797](../poe2-0.5.0-return-of-the-ancients.md#L797)

## Practical Read

- Projectile builds need to retest all "fixed projectile count" and "projectile modifiers apply to another value" interactions; several bug fixes suggest prior behavior was inconsistent.
- Chain has both buffs and constraints: Rolling Magma and some items improve chain access, but Lightning Arrow and terrain-chain behavior are tightened.
- Extra-arrow scaling shifts toward Surpassing chance rather than guaranteed flat extra arrows in some item slots.
