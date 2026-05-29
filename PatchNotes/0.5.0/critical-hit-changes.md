# PoE2 0.5.0 Critical Hit Changes

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

This is an extracted working view of critical hit chance, critical damage, and closely related critical-hit bug-fix entries. The source capture is unchanged; links point back to the relevant source lines.

## Critical Hit Chance

- Deadly Force now grants 15% increased Critical Hit Chance, up from 10%, but its recent-critical damage bonus is reduced. [L426](../poe2-0.5.0-return-of-the-ancients.md#L426)
- Stormcharged no longer grants 15% increased Critical Hit Chance or 40% increased Elemental Damage after recently dealing a critical hit. [L450](../poe2-0.5.0-return-of-the-ancients.md#L450)
- Volcano now has 8% base Critical Hit Chance, up from 5%. [L520](../poe2-0.5.0-return-of-the-ancients.md#L520)
- Stag Idol loses its previous 50% increased Thorns Critical Hit Chance helmet modifier. [L659](../poe2-0.5.0-return-of-the-ancients.md#L659)

## Critical Hit Damage

- Critical Overload now grants 15% increased Critical Spell Damage Bonus instead of conditional Spell Damage after a recent critical hit. [L424](../poe2-0.5.0-return-of-the-ancients.md#L424)
- Shatter Palm now grants 20% increased Critical Damage Bonus instead of chance to Daze. [L447](../poe2-0.5.0-return-of-the-ancients.md#L447)
- Staggering Palm loses its 20% increased Critical Damage Bonus and instead grants chance to Daze. [L449](../poe2-0.5.0-return-of-the-ancients.md#L449)
- Tempered Mind now improves Fully Broken Armour effect instead of granting 20% increased Critical Damage Bonus. [L452](../poe2-0.5.0-return-of-the-ancients.md#L452)
- Seed of Cataclysm loses 30-50% increased Critical Spell Damage Bonus and gains reduced Critical Spell Damage Bonus per recent spell critical hit plus Lucky spell critical damage chance. [L583](../poe2-0.5.0-return-of-the-ancients.md#L583)
- Wolf Idol now grants allies in your presence 20% increased Critical Damage Bonus from Sceptres, up from 14%. [L660](../poe2-0.5.0-return-of-the-ancients.md#L660)

## Critical Hit Bug Fixes

- Unarmed critical hit chance modifiers now apply correctly to the displayed skill information value. [L759](../poe2-0.5.0-return-of-the-ancients.md#L759)
- Infernal Legion is no longer always treated as a critical hit whenever it has any critical hit chance. [L803](../poe2-0.5.0-return-of-the-ancients.md#L803)
- His Winnowing Flame no longer incorrectly applies Critical Weakness on hit, and its triggered ignite-consuming explosions now deal damage. [L811](../poe2-0.5.0-return-of-the-ancients.md#L811)
- Atsak's Sight's Poison on Critical Hit modifier now applies to Thorns critical hits. [L828](../poe2-0.5.0-return-of-the-ancients.md#L828)
- Gore Spike's Critical Damage Bonus increase now displays correctly in the skill stats panel. [L776](../poe2-0.5.0-return-of-the-ancients.md#L776)
