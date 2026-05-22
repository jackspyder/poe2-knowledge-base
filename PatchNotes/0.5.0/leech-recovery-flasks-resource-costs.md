# PoE2 0.5.0 Leech, Recovery, Flasks, and Resource Costs

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Global Leech and Resource Rules

- Only one Leech instance per resource can recover at once; the highest recovery rate applies until it expires, then the next highest takes over. [L262](../poe2-0.5.0-return-of-the-ancients.md#L262)
- Leech calculations now cap hit damage at 40,000 for purposes of leech amount, so very large hits stop scaling leech past that point. [L263](../poe2-0.5.0-return-of-the-ancients.md#L263)
- Monster Leech resistance starts later, has lower values, and is normalized across monster rarities. [L649](../poe2-0.5.0-return-of-the-ancients.md#L649)
- Desecrated Instant Leech modifiers can no longer roll, but existing items are not changed. [L637](../poe2-0.5.0-return-of-the-ancients.md#L637)

## Life Leech and Life Recovery

- Into the Breach now grants 20% maximum Life leech from Red Flames of Chayula. [L353](../poe2-0.5.0-return-of-the-ancients.md#L353)
- Vitality Siphon now grants 20% of Spell Damage leeched as Life. [L358](../poe2-0.5.0-return-of-the-ancients.md#L358)
- Vaal Pact now gives 50% more Life Leeched amount, 67% less Life Leech speed, Life recovery only from leech, and persistent Life Leech effects at full unreserved Life. It no longer gives instant leech. [L388](../poe2-0.5.0-return-of-the-ancients.md#L388)
- Fast Metabolism now gives damage while leeching instead of preserving Life Leech at full Life. [L412](../poe2-0.5.0-return-of-the-ancients.md#L412)
- Fortifying Blood and Goring retune Life Leech amount and maximum Life interactions. [L413-L414](../poe2-0.5.0-return-of-the-ancients.md#L413-L414)
- Voracious no longer grants partial instant Life Leech and now grants attack speed while leeching. [L427](../poe2-0.5.0-return-of-the-ancients.md#L427)
- Small Life Leech amount passives are reduced to 8%. [L433](../poe2-0.5.0-return-of-the-ancients.md#L433)
- Unsavored Feast changes from instant leech at high tribute to faster Life Leech at lower tribute. [L436](../poe2-0.5.0-return-of-the-ancients.md#L436)
- Shattering Spite loses instant Life Leech from explosions with enough Bloodstone Lances. [L477](../poe2-0.5.0-return-of-the-ancients.md#L477)

## Energy Shield Recharge and Recovery

- Many passive tree Energy Shield Recharge Rate stats were reduced, removed, or converted into lower faster-start-of-recharge values. [L393-L421](../poe2-0.5.0-return-of-the-ancients.md#L393-L421)
- Small faster-start Energy Shield Recharge passives are reduced to 6%, and small recharge-rate passives are replaced by lower faster-start passives. [L431-L432](../poe2-0.5.0-return-of-the-ancients.md#L431-L432)
- Ghost Dance now regenerates Energy Shield equal to 2% of Evasion Rating per second after losing a Ghost Shroud recently. [L459](../poe2-0.5.0-return-of-the-ancients.md#L459), [L841](../poe2-0.5.0-return-of-the-ancients.md#L841)
- Apep's Supremacy loses faster Energy Shield recharge start, while Sierran Inheritance switches from faster start to Energy Shield Recharge Rate. [L526-L528](../poe2-0.5.0-return-of-the-ancients.md#L526-L528)
- Essence of Hysteria, Rebirth Runes, Craiceann's Rune of Recovery, Arcane Raiment/Sacramental Robe implicits, and recharge suffixes all received Energy Shield recharge pool/value changes. [L584](../poe2-0.5.0-return-of-the-ancients.md#L584), [L598-L601](../poe2-0.5.0-return-of-the-ancients.md#L598-L601), [L627-L634](../poe2-0.5.0-return-of-the-ancients.md#L627-L634)
- Bug fixes: skills costing a percentage of maximum Energy Shield now work at zero maximum Energy Shield, and Energy Shield depletion audio now plays for damage over time. [L729](../poe2-0.5.0-return-of-the-ancients.md#L729), [L801](../poe2-0.5.0-return-of-the-ancients.md#L801)

## Flasks, Guard, and Recovery Items

- Arcane Mixtures now grants cast speed after using a Mana Flask instead of Energy Shield Recharge Rate. [L393](../poe2-0.5.0-return-of-the-ancients.md#L393)
- Glowswarm gives Guard equal to Mana Flask recovery for 4 seconds. [L537](../poe2-0.5.0-return-of-the-ancients.md#L537)
- Reverie makes non-unique Life Flasks apply constantly, prevents Life Flask use, prevents instant Life Flask recovery, and reduces Life Flask recovery. [L539](../poe2-0.5.0-return-of-the-ancients.md#L539)
- Zerphi's Genesis converts Life Flask charges into Charm charges and gives corrupted-gem skill cost efficiency during flask effects. [L554](../poe2-0.5.0-return-of-the-ancients.md#L554)
- Martial Weapons and Flasks in the campaign are more likely to be highest available base types. [L563](../poe2-0.5.0-return-of-the-ancients.md#L563)
- Vision Runes improve Life and Mana Flask Recovery on armour items. [L590](../poe2-0.5.0-return-of-the-ancients.md#L590)
- Idol of Maxarius gives Flask Charges per second from Sceptres. [L609](../poe2-0.5.0-return-of-the-ancients.md#L609)
- Viper Napuatzi's arena constriction now refills some Flask charges. [L653](../poe2-0.5.0-return-of-the-ancients.md#L653)
- Bug fixes: Life Flasks can be used correctly at full life with Enduring Elixirs, and Melting Maelstrom can hit enemies. [L705](../poe2-0.5.0-return-of-the-ancients.md#L705), [L727](../poe2-0.5.0-return-of-the-ancients.md#L727), [L741](../poe2-0.5.0-return-of-the-ancients.md#L741)

## Resource Costs and Cost Efficiency

- Vaal Cultivation outcomes for Life Cost Efficiency were reduced on Atziri's Rule, The Covenant, and Rathpith Globe. [L193](../poe2-0.5.0-return-of-the-ancients.md#L193), [L195](../poe2-0.5.0-return-of-the-ancients.md#L195), [L197](../poe2-0.5.0-return-of-the-ancients.md#L197)
- Skills with 0 Mana cost now display it, and Crossbow Ammunition Skills now have base cost 0 rather than disabled cost. This matters for added-cost mechanics. [L440-L441](../poe2-0.5.0-return-of-the-ancients.md#L440-L441)
- Oil Barrage has lower mana cost, and Empowered Oil Barrage now uses cost-per-second based on the initial cost. [L468](../poe2-0.5.0-return-of-the-ancients.md#L468)
- Paquate's Pact changes from Life loss per Corrupted Blood to a supported-skill maximum-Life cost based on recent use. [L513](../poe2-0.5.0-return-of-the-ancients.md#L513)
- Svalinn's Cast on Block makes supported skills cost nothing. [L552](../poe2-0.5.0-return-of-the-ancients.md#L552)
- Idol of Eeshta grants Cost Efficiency from helmets and Mana Recovery Rate while a companion is in your presence from Sceptres. [L607](../poe2-0.5.0-return-of-the-ancients.md#L607)

## Practical Read

- Instant leech is much more constrained, and the global one-instance rule makes leech rate quality more important than stacking many small leech sources.
- Energy Shield recovery is less about raw Recharge Rate spam on the passive tree and more about specific item/passive exceptions, faster-start values, and Ghost Dance-style conversion.
- Flask builds gained several explicit hooks, but Reverie and Zerphi's Genesis are highly conditional and should be documented as engine pieces rather than generic recovery buffs.
