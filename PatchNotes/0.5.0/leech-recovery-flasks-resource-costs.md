# PoE2 0.5.0 Leech, Recovery, Flasks, and Resource Costs

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Global Leech and Resource Rules

- Only one Leech instance per resource can recover at once; the highest recovery rate applies until it expires, then the next highest takes over. [L274](../poe2-0.5.0-return-of-the-ancients.md#L274)
- Leech calculations now cap hit damage at 40,000 for purposes of leech amount, so very large hits stop scaling leech past that point. [L275](../poe2-0.5.0-return-of-the-ancients.md#L275)
- Monster Leech resistance starts later, has lower values, and is normalized across monster rarities. [L686](../poe2-0.5.0-return-of-the-ancients.md#L686)
- Desecrated Instant Leech modifiers can no longer roll, but existing items are not changed. [L674](../poe2-0.5.0-return-of-the-ancients.md#L674)
- Physical Attack Damage leeched as Life/Mana affixes on gloves and rings now roll at lower levels, lose their first tiers, and have several remaining suffix tiers shifted to lower item levels; Vampire and Desperate can also roll on bows and crossbows. [L1000-L1010](../poe2-0.5.0-return-of-the-ancients.md#L1000-L1010)

## Life Leech and Life Recovery

- Into the Breach now grants 20% maximum Life leech from Red Flames of Chayula. [L369](../poe2-0.5.0-return-of-the-ancients.md#L369)
- Vitality Siphon now grants 20% of Spell Damage leeched as Life. [L374](../poe2-0.5.0-return-of-the-ancients.md#L374)
- Vaal Pact now gives 50% more Life Leeched amount, 67% less Life Leech speed, Life recovery only from leech, and persistent Life Leech effects at full unreserved Life. It no longer gives instant leech. [L409](../poe2-0.5.0-return-of-the-ancients.md#L409)
- Fast Metabolism now gives damage while leeching instead of preserving Life Leech at full Life. [L435](../poe2-0.5.0-return-of-the-ancients.md#L435)
- Fortifying Blood and Goring retune Life Leech amount and maximum Life interactions. [L436-L437](../poe2-0.5.0-return-of-the-ancients.md#L436-L437)
- Voracious no longer grants partial instant Life Leech and now grants attack speed while leeching. [L454](../poe2-0.5.0-return-of-the-ancients.md#L454)
- Small Life Leech amount passives are reduced to 8%. [L462](../poe2-0.5.0-return-of-the-ancients.md#L462)
- Unsavored Feast changes from instant leech at high tribute to faster Life Leech at lower tribute. [L465](../poe2-0.5.0-return-of-the-ancients.md#L465)
- Mark of Siphoning adds Mana Leech from Physical Attack Damage, and Mark of Siphoning II adds both Mana and Life Leech from Physical Attack Damage. [L542](../poe2-0.5.0-return-of-the-ancients.md#L542), [L543](../poe2-0.5.0-return-of-the-ancients.md#L543)
- Shattering Spite loses instant Life Leech from explosions with enough Bloodstone Lances. [L509](../poe2-0.5.0-return-of-the-ancients.md#L509)

## Energy Shield Recharge and Recovery

- Many passive tree Energy Shield Recharge Rate stats were reduced, removed, or converted into lower faster-start-of-recharge values. [L414-L446](../poe2-0.5.0-return-of-the-ancients.md#L414-L446)
- Small faster-start Energy Shield Recharge passives are reduced to 6%, and small recharge-rate passives are replaced by lower faster-start passives. [L460-L461](../poe2-0.5.0-return-of-the-ancients.md#L460-L461)
- Ghost Dance now regenerates Energy Shield equal to 2% of Evasion Rating per second after losing a Ghost Shroud recently. [L491](../poe2-0.5.0-return-of-the-ancients.md#L491), [L1026](../poe2-0.5.0-return-of-the-ancients.md#L1026)
- Apep's Supremacy loses faster Energy Shield recharge start, while Sierran Inheritance switches from faster start to Energy Shield Recharge Rate. [L560-L562](../poe2-0.5.0-return-of-the-ancients.md#L560-L562)
- Quipolatl's Thesis now starts Energy Shield Recharge when minions are reformed if socketed into gloves. [L998](../poe2-0.5.0-return-of-the-ancients.md#L998)
- Essence of Hysteria, Rebirth Runes, Craiceann's Rune of Recovery, Arcane Raiment/Sacramental Robe implicits, and recharge suffixes all received Energy Shield recharge pool/value changes. [L621](../poe2-0.5.0-return-of-the-ancients.md#L621), [L635-L638](../poe2-0.5.0-return-of-the-ancients.md#L635-L638), [L664-L671](../poe2-0.5.0-return-of-the-ancients.md#L664-L671)
- Bug fixes: skills costing a percentage of maximum Energy Shield now work at zero maximum Energy Shield, Eternal Youth no longer lets zero-Energy-Shield characters bypass the Energy Shield regeneration delay for Life Regeneration, and Energy Shield depletion audio now plays for damage over time. [L789](../poe2-0.5.0-return-of-the-ancients.md#L789), [L775](../poe2-0.5.0-return-of-the-ancients.md#L775), [L862](../poe2-0.5.0-return-of-the-ancients.md#L862)

## Flasks, Guard, and Recovery Items

- Arcane Mixtures now grants cast speed after using a Mana Flask instead of Energy Shield Recharge Rate. [L414](../poe2-0.5.0-return-of-the-ancients.md#L414)
- Blood Mage's Sanguine Tides now grants 1 Life Flask Charge per 2% Life spent, extends the physical-damage gain duration to 5 seconds per consumed charge, and makes flasks not recover Life. [L375](../poe2-0.5.0-return-of-the-ancients.md#L375)
- Glowswarm gives Guard equal to Mana Flask recovery for 4 seconds. [L571](../poe2-0.5.0-return-of-the-ancients.md#L571)
- Reverie makes non-unique Life Flasks apply constantly, prevents Life Flask use, prevents instant Life Flask recovery, and reduces Life Flask recovery. [L574](../poe2-0.5.0-return-of-the-ancients.md#L574)
- Zerphi's Genesis converts Life Flask charges into Charm charges and gives corrupted-gem skill cost efficiency during flask effects. [L589](../poe2-0.5.0-return-of-the-ancients.md#L589)
- Martial Weapons and Flasks in the campaign are more likely to be highest available base types. [L600](../poe2-0.5.0-return-of-the-ancients.md#L600)
- Vision Runes improve Life and Mana Flask Recovery on armour items. [L627](../poe2-0.5.0-return-of-the-ancients.md#L627)
- Idol of Maxarius gives Flask Charges per second from Sceptres. [L646](../poe2-0.5.0-return-of-the-ancients.md#L646)
- Viper Napuatzi's arena constriction now refills some Flask charges. [L690](../poe2-0.5.0-return-of-the-ancients.md#L690)
- Bug fixes: Life Flasks can be used correctly at full life with Enduring Elixirs, disabled flasks can no longer still be used by some effects, and Melting Maelstrom can hit enemies. [L750](../poe2-0.5.0-return-of-the-ancients.md#L750), [L767](../poe2-0.5.0-return-of-the-ancients.md#L767), [L787](../poe2-0.5.0-return-of-the-ancients.md#L787)

## Resource Costs and Cost Efficiency

- Vaal Cultivation outcomes for Life Cost Efficiency were reduced on Atziri's Rule, The Covenant, and Rathpith Globe. [L194](../poe2-0.5.0-return-of-the-ancients.md#L194), [L196](../poe2-0.5.0-return-of-the-ancients.md#L196), [L198](../poe2-0.5.0-return-of-the-ancients.md#L198)
- Skills with 0 Mana cost now display it, and Crossbow Ammunition Skills now have base cost 0 rather than disabled cost. This matters for added-cost mechanics. [L469-L470](../poe2-0.5.0-return-of-the-ancients.md#L469-L470)
- Many skills that previously had no cost now cost 0 Mana, including default weapon attacks, item-inherent skills, and triggered skills from support gems or other sources, so added-cost mechanics can apply to them. [L471](../poe2-0.5.0-return-of-the-ancients.md#L471)
- Oil Barrage has lower mana cost, and Empowered Oil Barrage now uses cost-per-second based on the initial cost. [L500](../poe2-0.5.0-return-of-the-ancients.md#L500)
- Unborn Lich granted skills had several Mana Costs reduced to 0, while His Foul Emergence now has an 8 second cooldown at all levels. [L993-L996](../poe2-0.5.0-return-of-the-ancients.md#L993-L996)
- Paquate's Pact changes from Life loss per Corrupted Blood to a supported-skill maximum-Life cost based on recent use. [L547](../poe2-0.5.0-return-of-the-ancients.md#L547)
- Svalinn's Cast on Block makes supported skills cost nothing. [L587](../poe2-0.5.0-return-of-the-ancients.md#L587)
- Idol of Eeshta grants Cost Efficiency from helmets and Mana Recovery Rate while a companion is in your presence from Sceptres. [L644](../poe2-0.5.0-return-of-the-ancients.md#L644)

## Practical Read

- Instant leech is much more constrained, and the global one-instance rule makes leech rate quality more important than stacking many small leech sources.
- Energy Shield recovery is less about raw Recharge Rate spam on the passive tree and more about specific item/passive exceptions, faster-start values, and Ghost Dance-style conversion.
- Flask builds gained several explicit hooks, but Reverie, Zerphi's Genesis, and Sanguine Tides are highly conditional and should be documented as engine pieces rather than generic recovery buffs.
