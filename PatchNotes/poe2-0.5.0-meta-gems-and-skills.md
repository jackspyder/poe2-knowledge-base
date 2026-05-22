# PoE2 0.5.0 Meta Gems and Skills

Source: [Content Update 0.5.0 captured patch notes](./poe2-0.5.0-return-of-the-ancients.md)

This is an extracted working view of meta gem, skill, support, and skill-related bug-fix entries. The source capture is unchanged; links point back to the relevant source lines.

## New Skills, Supports, and Build Tooling

- Runes of Aldur adds 21 Kalguuran Skills craftable from Remnants. [L60](./poe2-0.5.0-return-of-the-ancients.md#L60)
- Runes of Aldur adds 8 Kalguuran Supports craftable from Remnants. [L61](./poe2-0.5.0-return-of-the-ancients.md#L61)
- 21 new Lineage Supports were added. [L277-L297](./poe2-0.5.0-return-of-the-ancients.md#L277)
- Minion Splash and Minion Splash II Strength Support Gems were added. [L341](./poe2-0.5.0-return-of-the-ancients.md#L341)
- Build Guide support was added, including downloadable `.build` files with passive, ascendancy, skill gem, and support gem recommendations. [L343](./poe2-0.5.0-return-of-the-ancients.md#L343)

## Ascendancy Skill and Gem Interactions

- Into the Breach wording and remnant pickup-range visuals were clarified. [L354](./poe2-0.5.0-return-of-the-ancients.md#L354), [L355](./poe2-0.5.0-return-of-the-ancients.md#L355)
- Chronomancer changes replace Rapid River with Now and Again, rework Now and Again around Echo/Repeat chance, move Unbound Encore, and update Ultimate Command requirements. [L361-L364](./poe2-0.5.0-return-of-the-ancients.md#L361)
- Temporal Rift has a shorter cast time and removes delayed damage from Phased Form. [L366](./poe2-0.5.0-return-of-the-ancients.md#L366)
- Inevitable Agony is reworked from a Curse into a cooldown skill with a Life Loss debuff, cull behavior, longer duration, new quality stat, and new visuals. [L367](./poe2-0.5.0-return-of-the-ancients.md#L367)
- Sands of Time now grants Skill Speed rather than Cast Speed. [L368](./poe2-0.5.0-return-of-the-ancients.md#L368)
- Gemling Legionnaire gains Virtuous Barrier, and Advanced Thaumaturgy now gives socketed skills extra quality effects rather than granting Thaumaturgical Dynamism. [L372](./poe2-0.5.0-return-of-the-ancients.md#L372), [L373](./poe2-0.5.0-return-of-the-ancients.md#L373)
- Pathfinder's Running Assault now has a smaller movement-speed-while-using-skills benefit. [L377](./poe2-0.5.0-return-of-the-ancients.md#L377)
- Ancestral Bond makes totem placement costless and charge-free, keeps Spirit reservation, and doubles totem limit. [L386](./poe2-0.5.0-return-of-the-ancients.md#L386)
- Trusted Kinship now focuses on Companion Skill reservation efficiency versus non-Companion Skill reservation efficiency. [L387](./poe2-0.5.0-return-of-the-ancients.md#L387)

## System-Wide Skill and Gem Rules

- Skills with fixed projectile counts can benefit from effects that redirect projectile-count modifiers. [L439](./poe2-0.5.0-return-of-the-ancients.md#L439)
- Skills with 0 Mana cost now display that cost, which clarifies interactions with added-cost effects. [L440](./poe2-0.5.0-return-of-the-ancients.md#L440)
- Crossbow Ammunition Skills now have a base cost of 0 instead of a disabled cost, so added costs can apply. [L441](./poe2-0.5.0-return-of-the-ancients.md#L441)
- Oil Ground ignites can no longer compound with themselves or with other ignites from the same skill use. [L442](./poe2-0.5.0-return-of-the-ancients.md#L442)
- Command Skills now have a 50% movement speed penalty during use instead of 70%. [L443](./poe2-0.5.0-return-of-the-ancients.md#L443)
- Seal supports are standardized across Unleash, Expand, Salvo, and Freezing Salvo. [L493](./poe2-0.5.0-return-of-the-ancients.md#L493)
- Freezing Salvo and Salvo Support can now gain Seals while the relevant skill is being performed. [L494](./poe2-0.5.0-return-of-the-ancients.md#L494)
- Salvo Support now gains Seals faster, has a higher Seal cap, and grants one projectile per Seal. [L495](./poe2-0.5.0-return-of-the-ancients.md#L495)
- Plus-to-level modifiers for melee, projectile, and attack skill gems on weapons and quivers are lowered or gated to higher item levels. [L576-L581](./poe2-0.5.0-return-of-the-ancients.md#L576)
- Perfect Essence of Battle now grants lower attack skill levels on attack weapons. [L583](./poe2-0.5.0-return-of-the-ancients.md#L583)
- Fox Idol changes body-armour bonded effects from global skill quality to idol-bonded-modifier behavior, while still offering +5% skill quality as the bonded modifier. [L616](./poe2-0.5.0-return-of-the-ancients.md#L616)

## Meta, Trigger, and Energy Mechanics

- Feral Invocation no longer bypasses socketed skill cooldowns. [L453](./poe2-0.5.0-return-of-the-ancients.md#L453)
- Flame Breath now has an Energy Gain penalty similar to Incinerate. [L454](./poe2-0.5.0-return-of-the-ancients.md#L454)
- Corrupting Cry I/II and Decaying Hex now trigger separate scaled skills instead of directly applying Corrupted Blood or Decay through the supported skill. [L502](./poe2-0.5.0-return-of-the-ancients.md#L502), [L503](./poe2-0.5.0-return-of-the-ancients.md#L503)
- Static Shocks received a trigger-condition description clarification. [L519](./poe2-0.5.0-return-of-the-ancients.md#L519)
- Svalinn's Cast on Block Skill now makes supported skills cost nothing. [L552](./poe2-0.5.0-return-of-the-ancients.md#L552)
- Zerphi's Genesis gives skills from Corrupted Gems cost efficiency during flask effects. [L554](./poe2-0.5.0-return-of-the-ancients.md#L554)
- Bug fixes cover Feral Invocation and Devour, triggered-skill classification, triggered skills generating energy, Dialla's Desire quality for Meta Skill and item-granted Skill Gems, Pounce gem art as a Meta Gem, and channelled skill interruption. [L710](./poe2-0.5.0-return-of-the-ancients.md#L710), [L736](./poe2-0.5.0-return-of-the-ancients.md#L736), [L747](./poe2-0.5.0-return-of-the-ancients.md#L747), [L752](./poe2-0.5.0-return-of-the-ancients.md#L752), [L770](./poe2-0.5.0-return-of-the-ancients.md#L770), [L827](./poe2-0.5.0-return-of-the-ancients.md#L827)

## Skill Changes

- Align Fate now lets Cooldown Recovery Rate affect visage appearance frequency. [L444](./poe2-0.5.0-return-of-the-ancients.md#L444)
- Ancestral Warrior Totem loses a hidden delay and now describes delay as half the skill attack time. [L445](./poe2-0.5.0-return-of-the-ancients.md#L445)
- Bonestorm loses the Sustained tag. [L446](./poe2-0.5.0-return-of-the-ancients.md#L446)
- Boneshatter, Ice Strike, Shred, and Whirling Assault have adjusted attack-speed quality values. [L447](./poe2-0.5.0-return-of-the-ancients.md#L447), [L462](./poe2-0.5.0-return-of-the-ancients.md#L462), [L479](./poe2-0.5.0-return-of-the-ancients.md#L479), [L489](./poe2-0.5.0-return-of-the-ancients.md#L489)
- Comet and Fire-Infused Comet have lower listed damage values. [L448](./poe2-0.5.0-return-of-the-ancients.md#L448)
- Cull the Weak gets Can't be Evaded, higher damage, faster attack speed, lower mana costs, and longer dash range. [L449](./poe2-0.5.0-return-of-the-ancients.md#L449)
- Defiance Banner, Dread Banner, and War Banner lose movement penalties and gain larger base aura radius. [L450](./poe2-0.5.0-return-of-the-ancients.md#L450)
- Earthquake aftershock damage is increased. [L451](./poe2-0.5.0-return-of-the-ancients.md#L451)
- Eternal Rage must be active in both weapon sets and cannot be activated in only specific sets. [L452](./poe2-0.5.0-return-of-the-ancients.md#L452)
- Fortifying Cry only consumes one stack for shield-wall detonation and has lower shield Armour damage scaling. [L455](./poe2-0.5.0-return-of-the-ancients.md#L455)
- Fragmentation Rounds quality changes from more Physical Damage to extra Fragments per Shot. [L456](./poe2-0.5.0-return-of-the-ancients.md#L456)
- Freezing Salvo has lower Chill and Freeze Buildup scaling. [L457](./poe2-0.5.0-return-of-the-ancients.md#L457)
- Gathering Storm now detonates Tempest Bell with Perfectly Timed dash, adds shockwave rules, and changes quality. [L458](./poe2-0.5.0-return-of-the-ancients.md#L458)
- Ghost Dance is reworked around cooldown recovery, shroud loss on hit, and Energy Shield regeneration from Evasion. [L459](./poe2-0.5.0-return-of-the-ancients.md#L459), [L841](./poe2-0.5.0-return-of-the-ancients.md#L841)
- Grim Feast's Grim Resurrection now has a 1 second cooldown. [L460](./poe2-0.5.0-return-of-the-ancients.md#L460)
- Ice Shot's Ice Shards lose their extra Freeze Buildup. [L461](./poe2-0.5.0-return-of-the-ancients.md#L461)
- Lightning Arrow beams can no longer chain multiple times onto the same target. [L463](./poe2-0.5.0-return-of-the-ancients.md#L463)
- Lunar Blessing's triggered Moonbeams are no longer melee skills. [L464](./poe2-0.5.0-return-of-the-ancients.md#L464)
- Magma Barrier, Resonating Shield, and Shield Wall have lower shield-stat damage scaling. [L465](./poe2-0.5.0-return-of-the-ancients.md#L465), [L474](./poe2-0.5.0-return-of-the-ancients.md#L474), [L478](./poe2-0.5.0-return-of-the-ancients.md#L478)
- Mirage Archer and Mirage Deadeye can now be used with channelled skills. [L466](./poe2-0.5.0-return-of-the-ancients.md#L466)
- Mirror of Refraction now lets Cooldown Recovery Rate affect mirror appearance frequency. [L467](./poe2-0.5.0-return-of-the-ancients.md#L467)
- Oil Barrage has lower mana cost, adjusted Empowered channel costs, damage changes, and faster power-charge consumption. [L468](./poe2-0.5.0-return-of-the-ancients.md#L468)
- Parry has animation-matched area changes and loses bonus attack distance. [L469](./poe2-0.5.0-return-of-the-ancients.md#L469)
- Poisonburst Arrow has fixed poison duration and lower quality magnitude scaling. [L470](./poe2-0.5.0-return-of-the-ancients.md#L470)
- Pounce has a longer cooldown. [L471](./poe2-0.5.0-return-of-the-ancients.md#L471)
- Ravenous Swarm now lets Cooldown Recovery Rate affect swarm spawning frequency. [L472](./poe2-0.5.0-return-of-the-ancients.md#L472)
- Rend fixes Lightning-Charged double scaling and adjusts damage to compensate. [L473](./poe2-0.5.0-return-of-the-ancients.md#L473)
- Rolling Magma chains more at all gem levels. [L475](./poe2-0.5.0-return-of-the-ancients.md#L475)
- Rolling Slam has shorter total attack time and lower slam damage values. [L476](./poe2-0.5.0-return-of-the-ancients.md#L476)
- Shattering Spite has lower damaging ailment magnitude and loses instant Life Leech from explosions. [L477](./poe2-0.5.0-return-of-the-ancients.md#L477)
- Snipe has adjusted attack and explosion damage values and a smaller Icy Blast explosion radius. [L480](./poe2-0.5.0-return-of-the-ancients.md#L480)
- Spell Totem can be used while moving and has updated animation. [L481](./poe2-0.5.0-return-of-the-ancients.md#L481)
- Supercharged Slam's fixed attack time text is clarified. [L482](./poe2-0.5.0-return-of-the-ancients.md#L482)
- Tame Beast summons newly tamed beasts immediately when you have enough Spirit and increases summoned beast damage. [L483](./poe2-0.5.0-return-of-the-ancients.md#L483)
- Tempest Bell can be Ancestrally Boosted like a Strike, can have 3 active bells, and has adjusted shockwave damage and trigger frequency. [L484](./poe2-0.5.0-return-of-the-ancients.md#L484)
- Toxic Growth fires more Pustules but has a much lower Pustule limit and different quality scaling. [L485](./poe2-0.5.0-return-of-the-ancients.md#L485)
- Thrashing Vines frequency text is clarified. [L486](./poe2-0.5.0-return-of-the-ancients.md#L486)
- Time of Need now lets Cooldown Recovery Rate affect blessing frequency and has a shorter interval. [L487](./poe2-0.5.0-return-of-the-ancients.md#L487)
- Volcano has higher base Critical Hit Chance. [L488](./poe2-0.5.0-return-of-the-ancients.md#L488)
- Wing Blast shockwave damage is increased. [L490](./poe2-0.5.0-return-of-the-ancients.md#L490)

## Support Changes

- Advancing Storm and Morgana's Tempest can support any Storm Skill under any conditions. [L496](./poe2-0.5.0-return-of-the-ancients.md#L496), [L510](./poe2-0.5.0-return-of-the-ancients.md#L510)
- Arjun's Medal has a lower chance to load a bolt on killing blow. [L497](./poe2-0.5.0-return-of-the-ancients.md#L497)
- Atziri's Impatience can no longer support Persistent Skills. [L498](./poe2-0.5.0-return-of-the-ancients.md#L498)
- Bhatair's Vengeance now grants cold damage based on Rage at a lower rate but longer duration. [L499](./poe2-0.5.0-return-of-the-ancients.md#L499)
- Brink I can be cut as a level 1 Support Gem. [L500](./poe2-0.5.0-return-of-the-ancients.md#L500)
- Culmination II changes Combo loss timing, max Combo, and damage per Combo. [L501](./poe2-0.5.0-return-of-the-ancients.md#L501)
- Dialla's Desire support quality bonus is reduced to +5%. [L504](./poe2-0.5.0-return-of-the-ancients.md#L504)
- Doedre's Undoing now spawns exploding Witchtoads from Cursed Ground instead of making it a Hazard. [L505](./poe2-0.5.0-return-of-the-ancients.md#L505)
- Infernal Legion I/II reduce minion maximum-Life self-damage and ignite scaling; Infernal Legion II also grants Fire Resistance. Infernal Legion III can no longer be obtained. [L506](./poe2-0.5.0-return-of-the-ancients.md#L506), [L507](./poe2-0.5.0-return-of-the-ancients.md#L507), [L508](./poe2-0.5.0-return-of-the-ancients.md#L508)
- Living Lightning no longer replaces minions when already at the minion cap. [L509](./poe2-0.5.0-return-of-the-ancients.md#L509)
- Overabundance III now describes its Persistent Skill restriction correctly. [L511](./poe2-0.5.0-return-of-the-ancients.md#L511)
- Overextend can no longer be obtained. [L512](./poe2-0.5.0-return-of-the-ancients.md#L512)
- Paquate's Pact now triggers a scaled Corrupted Blood skill and changes its Life-cost behavior. [L513](./poe2-0.5.0-return-of-the-ancients.md#L513)
- Rage I/II/III can support Minion Skills. [L514](./poe2-0.5.0-return-of-the-ancients.md#L514)
- Ratha's Assault grants fewer loaded bolts and lower attack speed. [L515](./poe2-0.5.0-return-of-the-ancients.md#L515)
- Refraction I/II adds Deflection Rating from Evasion Rating to supported Banner skills. [L516](./poe2-0.5.0-return-of-the-ancients.md#L516), [L517](./poe2-0.5.0-return-of-the-ancients.md#L517)
- Shock Conduction II can no longer be obtained. [L518](./poe2-0.5.0-return-of-the-ancients.md#L518)
- Uhtred's Augury and Uhtred's Omen grant +2 supported skill levels instead of +3. [L520](./poe2-0.5.0-return-of-the-ancients.md#L520), [L521](./poe2-0.5.0-return-of-the-ancients.md#L521)
- Volt grants fewer Voltaic Charges per metre and changes extra Lightning Damage scaling per charge consumed. [L522](./poe2-0.5.0-return-of-the-ancients.md#L522)

## Item-Granted and Item-Related Skill Changes

- The Vertex now rolls Curse Skill Gem levels instead of all Skill Gem levels. [L199](./poe2-0.5.0-return-of-the-ancients.md#L199)
- Chober Chaber now grants +2-3 to all Minion Skills. [L533](./poe2-0.5.0-return-of-the-ancients.md#L533)
- The Hollow Mask now grants Wildwood's Gifts and improves Remnant Skill reservation efficiency. [L538](./poe2-0.5.0-return-of-the-ancients.md#L538)
- Levinstone replaces +1 all Lightning Skills with Lightning Skills Chain +1 times. [L542](./poe2-0.5.0-return-of-the-ancients.md#L542)
- Skill level modifiers on attack weapons, quivers, and Perfect Essence of Battle were reduced. [L576-L583](./poe2-0.5.0-return-of-the-ancients.md#L576)

## Skill and Gem Bug Fixes

- Ritual Sacrifice, Pounce/Marks, Mirage Archer/Mirage Deadeye, Devour/Feral Invocation, and Hollow Palm Technique all received skill-function bug fixes. [L706-L710](./poe2-0.5.0-return-of-the-ancients.md#L706), [L713](./poe2-0.5.0-return-of-the-ancients.md#L713)
- Projectile-count and chain modifier fixes affect rain-of-arrows-like skills and beam skills. [L715-L717](./poe2-0.5.0-return-of-the-ancients.md#L715)
- Comet quality, Devour/Lightning Warp corpse interactions, Poison Spores Support prices, Burning Inscription Support ground placement, Low Tolerance description, and Arctic Howl/Echoing Cry were fixed. [L718-L723](./poe2-0.5.0-return-of-the-ancients.md#L718)
- Tactician's Cannons, Ready! now works with listed player skills; dual-wield simultaneous strikes now use intended average weapon attack time; Forge Hammer and Heightened Charges tracking/support interactions were fixed. [L726](./poe2-0.5.0-return-of-the-ancients.md#L726), [L728](./poe2-0.5.0-return-of-the-ancients.md#L728), [L731](./poe2-0.5.0-return-of-the-ancients.md#L731), [L732](./poe2-0.5.0-return-of-the-ancients.md#L732)
- Living Lightning II, Into the Breach with Selfless Remnants, Azmeri Spirit Possession player versions, Dialla's Desire with Meta Skill and item-granted Skill Gems, and Hayoxi's Fulmination supportability were fixed. [L733-L737](./poe2-0.5.0-return-of-the-ancients.md#L733)
- Shockwave Totem, Echoing Cry, Mirage Archer/Deadeye supportability, Empower stacking, triggered-skill classification, Grim Feast minion revival, Ice Nova repeats, His Winnowing Flame, and channelled skill interruption were fixed. [L739-L752](./poe2-0.5.0-return-of-the-ancients.md#L739)
- Arc, triggered skill energy generation, Stoicism Support, Volt Support, Iron Ward/Astral Projection, Lightning Warp targeting, Ancestrally Boosted attack area, and Blink/Parry/Raise Shield skill-use tracking were fixed. [L766](./poe2-0.5.0-return-of-the-ancients.md#L766), [L770-L777](./poe2-0.5.0-return-of-the-ancients.md#L770)
- Varashta's Blessing Lineage Support, Totem skill-panel prompts, hidden Ascendancy-granted Skills when cutting Support Gems, Always Attack Without Moving selection, and Pounce Meta Gem art were fixed or clarified. [L798](./poe2-0.5.0-return-of-the-ancients.md#L798), [L802](./poe2-0.5.0-return-of-the-ancients.md#L802), [L810](./poe2-0.5.0-return-of-the-ancients.md#L810), [L815](./poe2-0.5.0-return-of-the-ancients.md#L815), [L827](./poe2-0.5.0-return-of-the-ancients.md#L827)
