# PoE2 0.5.0 Critical Hit Changes

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

This is an extracted working view of critical hit chance, critical damage, and closely related critical-hit bug-fix entries. The source capture is unchanged; links point back to the relevant source lines.

## Critical Hit Chance

- Deadly Force now grants 15% increased Critical Hit Chance, up from 10%, but its recent-critical damage bonus is reduced. [L404](../poe2-0.5.0-return-of-the-ancients.md#L404)
- Stormcharged no longer grants 15% increased Critical Hit Chance or 40% increased Elemental Damage after recently dealing a critical hit. [L425](../poe2-0.5.0-return-of-the-ancients.md#L425)
- Volcano now has 8% base Critical Hit Chance, up from 5%. [L488](../poe2-0.5.0-return-of-the-ancients.md#L488)
- Stag Idol loses its previous 50% increased Thorns Critical Hit Chance helmet modifier. [L622](../poe2-0.5.0-return-of-the-ancients.md#L622)

## Critical Hit Damage

- Critical Overload now grants 15% increased Critical Spell Damage Bonus instead of conditional Spell Damage after a recent critical hit. [L402](../poe2-0.5.0-return-of-the-ancients.md#L402)
- Shatter Palm now grants 20% increased Critical Damage Bonus instead of chance to Daze. [L422](../poe2-0.5.0-return-of-the-ancients.md#L422)
- Staggering Palm loses its 20% increased Critical Damage Bonus and instead grants chance to Daze. [L424](../poe2-0.5.0-return-of-the-ancients.md#L424)
- Tempered Mind now improves Fully Broken Armour effect instead of granting 20% increased Critical Damage Bonus. [L426](../poe2-0.5.0-return-of-the-ancients.md#L426)
- Seed of Cataclysm loses 30-50% increased Critical Spell Damage Bonus and gains reduced Critical Spell Damage Bonus per recent spell critical hit plus Lucky spell critical damage chance. [L548](../poe2-0.5.0-return-of-the-ancients.md#L548)
- Wolf Idol now grants allies in your presence 20% increased Critical Damage Bonus from Sceptres, up from 14%. [L623](../poe2-0.5.0-return-of-the-ancients.md#L623)

## Critical Hit Bug Fixes

- Unarmed critical hit chance modifiers now apply correctly to the displayed skill information value. [L714](../poe2-0.5.0-return-of-the-ancients.md#L714)
- Infernal Legion is no longer always treated as a critical hit whenever it has any critical hit chance. [L743](../poe2-0.5.0-return-of-the-ancients.md#L743)
- His Winnowing Flame no longer incorrectly applies Critical Weakness on hit, and its triggered ignite-consuming explosions now deal damage. [L751](../poe2-0.5.0-return-of-the-ancients.md#L751)
- Atsak's Sight's Poison on Critical Hit modifier now applies to Thorns critical hits. [L767](../poe2-0.5.0-return-of-the-ancients.md#L767)
