# PoE2 0.5.0 Leech, Recovery, Flasks, and Resource Costs

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Global Leech and Resource Rules

- Only one Leech instance per resource can recover at once; the highest recovery rate applies until it expires, then the next highest takes over. [L273](../poe2-0.5.0-return-of-the-ancients.md#L273)
- Leech calculations now cap hit damage at 40,000 for purposes of leech amount, so very large hits stop scaling leech past that point. [L274](../poe2-0.5.0-return-of-the-ancients.md#L274)
- Monster Leech resistance starts later, has lower values, and is normalized across monster rarities. [L682](../poe2-0.5.0-return-of-the-ancients.md#L682)
- Desecrated Instant Leech modifiers can no longer roll, but existing items are not changed. [L670](../poe2-0.5.0-return-of-the-ancients.md#L670)
- Physical Attack Damage leeched as Life/Mana affixes on gloves and rings now roll at lower levels, lose their first tiers, and have several remaining suffix tiers shifted to lower item levels; Vampire and Desperate can also roll on bows and crossbows. [L965-L975](../poe2-0.5.0-return-of-the-ancients.md#L965-L975)

## Life Leech and Life Recovery

- Into the Breach now grants 20% maximum Life leech from Red Flames of Chayula. [L368](../poe2-0.5.0-return-of-the-ancients.md#L368)
- Vitality Siphon now grants 20% of Spell Damage leeched as Life. [L373](../poe2-0.5.0-return-of-the-ancients.md#L373)
- Vaal Pact now gives 50% more Life Leeched amount, 67% less Life Leech speed, Life recovery only from leech, and persistent Life Leech effects at full unreserved Life. It no longer gives instant leech. [L407](../poe2-0.5.0-return-of-the-ancients.md#L407)
- Fast Metabolism now gives damage while leeching instead of preserving Life Leech at full Life. [L433](../poe2-0.5.0-return-of-the-ancients.md#L433)
- Fortifying Blood and Goring retune Life Leech amount and maximum Life interactions. [L434-L435](../poe2-0.5.0-return-of-the-ancients.md#L434-L435)
- Voracious no longer grants partial instant Life Leech and now grants attack speed while leeching. [L452](../poe2-0.5.0-return-of-the-ancients.md#L452)
- Small Life Leech amount passives are reduced to 8%. [L460](../poe2-0.5.0-return-of-the-ancients.md#L460)
- Unsavored Feast changes from instant leech at high tribute to faster Life Leech at lower tribute. [L463](../poe2-0.5.0-return-of-the-ancients.md#L463)
- Mark of Siphoning adds Mana Leech from Physical Attack Damage, and Mark of Siphoning II adds both Mana and Life Leech from Physical Attack Damage. [L538](../poe2-0.5.0-return-of-the-ancients.md#L538), [L539](../poe2-0.5.0-return-of-the-ancients.md#L539)
- Shattering Spite loses instant Life Leech from explosions with enough Bloodstone Lances. [L505](../poe2-0.5.0-return-of-the-ancients.md#L505)

## Energy Shield Recharge and Recovery

- Many passive tree Energy Shield Recharge Rate stats were reduced, removed, or converted into lower faster-start-of-recharge values. [L412-L444](../poe2-0.5.0-return-of-the-ancients.md#L412-L444)
- Small faster-start Energy Shield Recharge passives are reduced to 6%, and small recharge-rate passives are replaced by lower faster-start passives. [L458-L459](../poe2-0.5.0-return-of-the-ancients.md#L458-L459)
- Ghost Dance now regenerates Energy Shield equal to 2% of Evasion Rating per second after losing a Ghost Shroud recently. [L487](../poe2-0.5.0-return-of-the-ancients.md#L487), [L991](../poe2-0.5.0-return-of-the-ancients.md#L991)
- Apep's Supremacy loses faster Energy Shield recharge start, while Sierran Inheritance switches from faster start to Energy Shield Recharge Rate. [L556-L558](../poe2-0.5.0-return-of-the-ancients.md#L556-L558)
- Quipolatl's Thesis now starts Energy Shield Recharge when minions are reformed if socketed into gloves. [L963](../poe2-0.5.0-return-of-the-ancients.md#L963)
- Essence of Hysteria, Rebirth Runes, Craiceann's Rune of Recovery, Arcane Raiment/Sacramental Robe implicits, and recharge suffixes all received Energy Shield recharge pool/value changes. [L617](../poe2-0.5.0-return-of-the-ancients.md#L617), [L631-L634](../poe2-0.5.0-return-of-the-ancients.md#L631-L634), [L660-L667](../poe2-0.5.0-return-of-the-ancients.md#L660-L667)
- Bug fixes: skills costing a percentage of maximum Energy Shield now work at zero maximum Energy Shield, Eternal Youth no longer lets zero-Energy-Shield characters bypass the Energy Shield regeneration delay for Life Regeneration, and Energy Shield depletion audio now plays for damage over time. [L780](../poe2-0.5.0-return-of-the-ancients.md#L780), [L766](../poe2-0.5.0-return-of-the-ancients.md#L766), [L853](../poe2-0.5.0-return-of-the-ancients.md#L853)

## Flasks, Guard, and Recovery Items

- Arcane Mixtures now grants cast speed after using a Mana Flask instead of Energy Shield Recharge Rate. [L412](../poe2-0.5.0-return-of-the-ancients.md#L412)
- Glowswarm gives Guard equal to Mana Flask recovery for 4 seconds. [L567](../poe2-0.5.0-return-of-the-ancients.md#L567)
- Reverie makes non-unique Life Flasks apply constantly, prevents Life Flask use, prevents instant Life Flask recovery, and reduces Life Flask recovery. [L570](../poe2-0.5.0-return-of-the-ancients.md#L570)
- Zerphi's Genesis converts Life Flask charges into Charm charges and gives corrupted-gem skill cost efficiency during flask effects. [L585](../poe2-0.5.0-return-of-the-ancients.md#L585)
- Martial Weapons and Flasks in the campaign are more likely to be highest available base types. [L596](../poe2-0.5.0-return-of-the-ancients.md#L596)
- Vision Runes improve Life and Mana Flask Recovery on armour items. [L623](../poe2-0.5.0-return-of-the-ancients.md#L623)
- Idol of Maxarius gives Flask Charges per second from Sceptres. [L642](../poe2-0.5.0-return-of-the-ancients.md#L642)
- Viper Napuatzi's arena constriction now refills some Flask charges. [L686](../poe2-0.5.0-return-of-the-ancients.md#L686)
- Bug fixes: Life Flasks can be used correctly at full life with Enduring Elixirs, disabled flasks can no longer still be used by some effects, and Melting Maelstrom can hit enemies. [L741](../poe2-0.5.0-return-of-the-ancients.md#L741), [L758](../poe2-0.5.0-return-of-the-ancients.md#L758), [L778](../poe2-0.5.0-return-of-the-ancients.md#L778)

## Resource Costs and Cost Efficiency

- Vaal Cultivation outcomes for Life Cost Efficiency were reduced on Atziri's Rule, The Covenant, and Rathpith Globe. [L193](../poe2-0.5.0-return-of-the-ancients.md#L193), [L195](../poe2-0.5.0-return-of-the-ancients.md#L195), [L197](../poe2-0.5.0-return-of-the-ancients.md#L197)
- Skills with 0 Mana cost now display it, and Crossbow Ammunition Skills now have base cost 0 rather than disabled cost. This matters for added-cost mechanics. [L467-L468](../poe2-0.5.0-return-of-the-ancients.md#L467-L468)
- Oil Barrage has lower mana cost, and Empowered Oil Barrage now uses cost-per-second based on the initial cost. [L496](../poe2-0.5.0-return-of-the-ancients.md#L496)
- Unborn Lich granted skills had several Mana Costs reduced to 0, while His Foul Emergence now has an 8 second cooldown at all levels. [L958-L961](../poe2-0.5.0-return-of-the-ancients.md#L958-L961)
- Paquate's Pact changes from Life loss per Corrupted Blood to a supported-skill maximum-Life cost based on recent use. [L543](../poe2-0.5.0-return-of-the-ancients.md#L543)
- Svalinn's Cast on Block makes supported skills cost nothing. [L583](../poe2-0.5.0-return-of-the-ancients.md#L583)
- Idol of Eeshta grants Cost Efficiency from helmets and Mana Recovery Rate while a companion is in your presence from Sceptres. [L640](../poe2-0.5.0-return-of-the-ancients.md#L640)

## Practical Read

- Instant leech is much more constrained, and the global one-instance rule makes leech rate quality more important than stacking many small leech sources.
- Energy Shield recovery is less about raw Recharge Rate spam on the passive tree and more about specific item/passive exceptions, faster-start values, and Ghost Dance-style conversion.
- Flask builds gained several explicit hooks, but Reverie and Zerphi's Genesis are highly conditional and should be documented as engine pieces rather than generic recovery buffs.
