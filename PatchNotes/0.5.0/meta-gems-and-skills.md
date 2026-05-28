# PoE2 0.5.0 Meta Gems and Skills

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

This is an extracted working view of meta gem, skill, support, and skill-related bug-fix entries. The source capture is unchanged; links point back to the relevant source lines.

## New Skills, Supports, and Build Tooling

- Runes of Aldur now lists 23 Kalguuran Skills craftable from Remnants; the update log explicitly adds Rain of Blades and Wardbound Minions to the skill list. [L60](../poe2-0.5.0-return-of-the-ancients.md#L60), [L959](../poe2-0.5.0-return-of-the-ancients.md#L959)
- Runes of Aldur adds 7 Kalguuran Supports craftable from Remnants, with Kalguuran Conviction removed from the support list. [L61](../poe2-0.5.0-return-of-the-ancients.md#L61), [L915](../poe2-0.5.0-return-of-the-ancients.md#L915)
- 23 new Lineage Supports were added, including Olroth's Conviction and Olroth's Hubris. [L290-L312](../poe2-0.5.0-return-of-the-ancients.md#L290-L312)
- Minion Splash and Minion Splash II Strength Support Gems were added. [L356](../poe2-0.5.0-return-of-the-ancients.md#L356)
- Build Guide support was added, including downloadable `.build` files with passive, ascendancy, skill gem, and support gem recommendations. [L358](../poe2-0.5.0-return-of-the-ancients.md#L358)

## Ascendancy Skill and Gem Interactions

- Into the Breach wording and remnant pickup-range visuals were clarified. [L370](../poe2-0.5.0-return-of-the-ancients.md#L370), [L371](../poe2-0.5.0-return-of-the-ancients.md#L371)
- Chronomancer changes replace Rapid River with Now and Again, rework Now and Again around Echo/Repeat chance, move Unbound Encore, and update Ultimate Command requirements. [L378-L381](../poe2-0.5.0-return-of-the-ancients.md#L378-L381)
- Temporal Rift has a shorter cast time and removes delayed damage from Phased Form. [L383](../poe2-0.5.0-return-of-the-ancients.md#L383)
- Inevitable Agony is reworked from a Curse into a cooldown skill with a Life Loss debuff, cull behavior, longer duration, new quality stat, and new visuals. [L384](../poe2-0.5.0-return-of-the-ancients.md#L384)
- Sands of Time now grants Skill Speed rather than Cast Speed. [L385](../poe2-0.5.0-return-of-the-ancients.md#L385)
- Gemling Legionnaire gains Virtuous Barrier, and Advanced Thaumaturgy now gives socketed skills extra quality effects rather than granting Thaumaturgical Dynamism. [L389](../poe2-0.5.0-return-of-the-ancients.md#L389), [L390](../poe2-0.5.0-return-of-the-ancients.md#L390)
- Pathfinder's Running Assault now has a smaller movement-speed-while-using-skills benefit. [L394](../poe2-0.5.0-return-of-the-ancients.md#L394)
- Ancestral Bond now states doubled Totem Limit, no charge requirement for placing Totems, and 75 Spirit reserved per Totem; it also clarifies that summoning a Spell Totem is not a spell, so added spell costs do not apply to the summoning action. [L407](../poe2-0.5.0-return-of-the-ancients.md#L407)
- Trusted Kinship now focuses on Companion Skill reservation efficiency versus non-Companion Skill reservation efficiency. [L408](../poe2-0.5.0-return-of-the-ancients.md#L408)

## System-Wide Skill and Gem Rules

- Skills with fixed projectile counts can benefit from effects that redirect projectile-count modifiers. [L468](../poe2-0.5.0-return-of-the-ancients.md#L468)
- Skills with 0 Mana cost now display that cost, which clarifies interactions with added-cost effects. [L469](../poe2-0.5.0-return-of-the-ancients.md#L469)
- Crossbow Ammunition Skills now have a base cost of 0 instead of a disabled cost, so added costs can apply. [L470](../poe2-0.5.0-return-of-the-ancients.md#L470)
- Many skills that previously had no cost now cost 0 Mana, including default weapon attacks, item-inherent skills, and triggered skills from support gems and other sources. This makes them eligible for additional costs. [L471](../poe2-0.5.0-return-of-the-ancients.md#L471)
- Oil Ground ignites can no longer compound with themselves or with other ignites from the same skill use. [L472](../poe2-0.5.0-return-of-the-ancients.md#L472)
- Command Skills now have a 50% movement speed penalty during use instead of 70%. [L473](../poe2-0.5.0-return-of-the-ancients.md#L473)
- Seal supports are standardized across Unleash, Expand, Salvo, and Freezing Salvo. [L525](../poe2-0.5.0-return-of-the-ancients.md#L525)
- Freezing Salvo and Salvo Support can now gain Seals while the relevant skill is being performed. [L526](../poe2-0.5.0-return-of-the-ancients.md#L526)
- Salvo Support now gains Seals faster, has a higher Seal cap, and grants one projectile per Seal. [L527](../poe2-0.5.0-return-of-the-ancients.md#L527)
- Plus-to-level modifiers for melee, projectile, and attack skill gems on weapons and quivers are lowered or gated to higher item levels. [L613-L618](../poe2-0.5.0-return-of-the-ancients.md#L613-L618)
- Perfect Essence of Battle now grants lower attack skill levels on attack weapons. [L620](../poe2-0.5.0-return-of-the-ancients.md#L620)
- Jeweller's Orbs can now add sockets to item-granted skills, and using one on an item with multiple granted skills affects all of those skills. [L592](../poe2-0.5.0-return-of-the-ancients.md#L592)
- Fox Idol changes body-armour bonded effects from global skill quality to idol-bonded-modifier behavior, while still offering +5% skill quality as the bonded modifier. [L653](../poe2-0.5.0-return-of-the-ancients.md#L653)

## Meta, Trigger, and Energy Mechanics

- Feral Invocation no longer bypasses socketed skill cooldowns. [L485](../poe2-0.5.0-return-of-the-ancients.md#L485)
- Flame Breath now has an Energy Gain penalty similar to Incinerate. [L486](../poe2-0.5.0-return-of-the-ancients.md#L486)
- Corrupting Cry I/II and Decaying Hex now trigger separate scaled skills instead of directly applying Corrupted Blood or Decay through the supported skill. [L534](../poe2-0.5.0-return-of-the-ancients.md#L534), [L535](../poe2-0.5.0-return-of-the-ancients.md#L535)
- Static Shocks received a trigger-condition description clarification. [L553](../poe2-0.5.0-return-of-the-ancients.md#L553)
- Svalinn's Cast on Block Skill now makes supported skills cost nothing. [L587](../poe2-0.5.0-return-of-the-ancients.md#L587)
- Zerphi's Genesis gives skills from Corrupted Gems cost efficiency during flask effects. [L589](../poe2-0.5.0-return-of-the-ancients.md#L589)
- Bug fixes cover Feral Invocation and Devour, triggered-skill classification, triggered skills generating energy, Dialla's Desire quality for Meta Skill and item-granted Skill Gems, Pounce gem art as a Meta Gem, and channelled skill interruption. [L754](../poe2-0.5.0-return-of-the-ancients.md#L754), [L795](../poe2-0.5.0-return-of-the-ancients.md#L795), [L806](../poe2-0.5.0-return-of-the-ancients.md#L806), [L811](../poe2-0.5.0-return-of-the-ancients.md#L811), [L830](../poe2-0.5.0-return-of-the-ancients.md#L830), [L887](../poe2-0.5.0-return-of-the-ancients.md#L887)

## Skill Changes

- Align Fate now lets Cooldown Recovery Rate affect visage appearance frequency. [L474](../poe2-0.5.0-return-of-the-ancients.md#L474)
- Ancestral Warrior Totem loses a hidden delay and now describes delay as half the skill attack time. [L475](../poe2-0.5.0-return-of-the-ancients.md#L475)
- Bonestorm loses the Sustained tag. [L477](../poe2-0.5.0-return-of-the-ancients.md#L477)
- Boneshatter, Ice Strike, Shred, and Whirling Assault have adjusted attack-speed quality values. [L478](../poe2-0.5.0-return-of-the-ancients.md#L478), [L494](../poe2-0.5.0-return-of-the-ancients.md#L494), [L511](../poe2-0.5.0-return-of-the-ancients.md#L511), [L521](../poe2-0.5.0-return-of-the-ancients.md#L521)
- Comet and Fire-Infused Comet have lower listed damage values. [L479](../poe2-0.5.0-return-of-the-ancients.md#L479)
- Cull the Weak gets Can't be Evaded, higher damage, faster attack speed, lower mana costs, and longer dash range. [L480](../poe2-0.5.0-return-of-the-ancients.md#L480)
- Defiance Banner, Dread Banner, and War Banner lose movement penalties and gain larger base aura radius. [L481](../poe2-0.5.0-return-of-the-ancients.md#L481)
- Earthquake aftershock damage is increased. [L482](../poe2-0.5.0-return-of-the-ancients.md#L482)
- Eternal Rage must be active in both weapon sets and cannot be activated in only specific sets. [L483](../poe2-0.5.0-return-of-the-ancients.md#L483)
- Eye of Winter now describes its shard projectiles per second while in flight, and that count can be modified by additional projectiles. [L484](../poe2-0.5.0-return-of-the-ancients.md#L484)
- Fortifying Cry only consumes one stack for shield-wall detonation and has lower shield Armour damage scaling. [L487](../poe2-0.5.0-return-of-the-ancients.md#L487)
- Fragmentation Rounds quality changes from more Physical Damage to extra Fragments per Shot. [L488](../poe2-0.5.0-return-of-the-ancients.md#L488)
- Freezing Salvo has lower Chill and Freeze Buildup scaling. [L489](../poe2-0.5.0-return-of-the-ancients.md#L489)
- Gathering Storm now detonates Tempest Bell with Perfectly Timed dash, adds shockwave rules, and changes quality. [L490](../poe2-0.5.0-return-of-the-ancients.md#L490)
- Ghost Dance is reworked around cooldown recovery, shroud loss on hit, and Energy Shield regeneration from Evasion. [L491](../poe2-0.5.0-return-of-the-ancients.md#L491), [L1014](../poe2-0.5.0-return-of-the-ancients.md#L1014)
- Grim Feast's Grim Resurrection now has a 1 second cooldown. [L492](../poe2-0.5.0-return-of-the-ancients.md#L492)
- Ice Shot's Ice Shards lose their extra Freeze Buildup. [L493](../poe2-0.5.0-return-of-the-ancients.md#L493)
- Ice Nova can no longer originate from Frostbolt while cascading sideways. [L975](../poe2-0.5.0-return-of-the-ancients.md#L975)
- Lightning Arrow beams can no longer chain multiple times onto the same target. [L495](../poe2-0.5.0-return-of-the-ancients.md#L495)
- Lunar Blessing's triggered Moonbeams are no longer melee skills. [L496](../poe2-0.5.0-return-of-the-ancients.md#L496)
- Magma Barrier, Resonating Shield, and Shield Wall have lower shield-stat damage scaling. [L497](../poe2-0.5.0-return-of-the-ancients.md#L497), [L506](../poe2-0.5.0-return-of-the-ancients.md#L506), [L510](../poe2-0.5.0-return-of-the-ancients.md#L510)
- Mirage Archer and Mirage Deadeye can now be used with channelled skills. [L498](../poe2-0.5.0-return-of-the-ancients.md#L498)
- Mirror of Refraction now lets Cooldown Recovery Rate affect mirror appearance frequency. [L499](../poe2-0.5.0-return-of-the-ancients.md#L499)
- Oil Barrage has lower mana cost, adjusted Empowered channel costs, damage changes, and faster power-charge consumption. [L500](../poe2-0.5.0-return-of-the-ancients.md#L500)
- Parry has animation-matched area changes and loses bonus attack distance. [L501](../poe2-0.5.0-return-of-the-ancients.md#L501)
- Poisonburst Arrow has fixed poison duration and lower quality magnitude scaling. [L502](../poe2-0.5.0-return-of-the-ancients.md#L502)
- Pounce has a longer cooldown. [L503](../poe2-0.5.0-return-of-the-ancients.md#L503)
- Ravenous Swarm now lets Cooldown Recovery Rate affect swarm spawning frequency. [L504](../poe2-0.5.0-return-of-the-ancients.md#L504)
- Rend fixes Lightning-Charged double scaling and adjusts damage to compensate. [L505](../poe2-0.5.0-return-of-the-ancients.md#L505)
- Rolling Magma chains more at all gem levels. [L507](../poe2-0.5.0-return-of-the-ancients.md#L507)
- Rolling Slam has shorter total attack time and lower slam damage values. [L508](../poe2-0.5.0-return-of-the-ancients.md#L508)
- Shattering Spite has lower damaging ailment magnitude and loses instant Life Leech from explosions. [L509](../poe2-0.5.0-return-of-the-ancients.md#L509)
- Snipe has adjusted attack and explosion damage values and a smaller Icy Blast explosion radius. [L512](../poe2-0.5.0-return-of-the-ancients.md#L512)
- Spell Totem can be used while moving and has updated animation. [L513](../poe2-0.5.0-return-of-the-ancients.md#L513)
- Supercharged Slam's fixed attack time text is clarified. [L514](../poe2-0.5.0-return-of-the-ancients.md#L514)
- Primal Strikes now has a higher minimum gem level, while Tame Beast has a lower minimum gem level, immediately summons newly tamed beasts when you have enough Spirit, and increases summoned beast damage. [L515](../poe2-0.5.0-return-of-the-ancients.md#L515), [L976](../poe2-0.5.0-return-of-the-ancients.md#L976)
- Tempest Bell can be Ancestrally Boosted like a Strike, can have 3 active bells, and has adjusted shockwave damage and trigger frequency. [L516](../poe2-0.5.0-return-of-the-ancients.md#L516)
- Toxic Growth fires more Pustules but has a much lower Pustule limit and different quality scaling. [L517](../poe2-0.5.0-return-of-the-ancients.md#L517)
- Thrashing Vines frequency text is clarified. [L518](../poe2-0.5.0-return-of-the-ancients.md#L518)
- Time of Need now lets Cooldown Recovery Rate affect blessing frequency and has a shorter interval. [L519](../poe2-0.5.0-return-of-the-ancients.md#L519)
- Volcano has higher base Critical Hit Chance. [L520](../poe2-0.5.0-return-of-the-ancients.md#L520)
- Wing Blast shockwave damage is increased. [L522](../poe2-0.5.0-return-of-the-ancients.md#L522)

## Support Changes

- Advancing Storm and Morgana's Tempest can support any Storm Skill under any conditions. [L528](../poe2-0.5.0-return-of-the-ancients.md#L528), [L544](../poe2-0.5.0-return-of-the-ancients.md#L544)
- Arjun's Medal has a lower chance to load a bolt on killing blow. [L529](../poe2-0.5.0-return-of-the-ancients.md#L529)
- Atziri's Impatience can no longer support Persistent Skills. [L530](../poe2-0.5.0-return-of-the-ancients.md#L530)
- Bhatair's Vengeance now grants cold damage based on Rage at a lower rate but longer duration. [L531](../poe2-0.5.0-return-of-the-ancients.md#L531)
- Brink I can be cut as a level 1 Support Gem. [L532](../poe2-0.5.0-return-of-the-ancients.md#L532)
- Culmination II changes Combo loss timing, max Combo, and damage per Combo. [L533](../poe2-0.5.0-return-of-the-ancients.md#L533)
- Dialla's Desire support quality bonus is reduced to +5%. [L536](../poe2-0.5.0-return-of-the-ancients.md#L536)
- Doedre's Undoing now spawns exploding Witchtoads from Cursed Ground instead of making it a Hazard. [L537](../poe2-0.5.0-return-of-the-ancients.md#L537)
- Infernal Legion I/II reduce minion maximum-Life self-damage and ignite scaling; Infernal Legion II also grants Fire Resistance. Infernal Legion III can no longer be obtained. [L538](../poe2-0.5.0-return-of-the-ancients.md#L538), [L539](../poe2-0.5.0-return-of-the-ancients.md#L539), [L540](../poe2-0.5.0-return-of-the-ancients.md#L540)
- Living Lightning no longer replaces minions when already at the minion cap. [L541](../poe2-0.5.0-return-of-the-ancients.md#L541)
- Mark of Siphoning adds Mana Leech from Physical Attack Damage, and Mark of Siphoning II adds both Mana and Life Leech from Physical Attack Damage. [L542](../poe2-0.5.0-return-of-the-ancients.md#L542), [L543](../poe2-0.5.0-return-of-the-ancients.md#L543)
- Spell Cascade is no longer limited to spells you use yourself. [L977](../poe2-0.5.0-return-of-the-ancients.md#L977)
- Overabundance III now describes its Persistent Skill restriction correctly. [L545](../poe2-0.5.0-return-of-the-ancients.md#L545)
- Overextend can no longer be obtained. [L546](../poe2-0.5.0-return-of-the-ancients.md#L546)
- Paquate's Pact now triggers a scaled Corrupted Blood skill and changes its Life-cost behavior. [L547](../poe2-0.5.0-return-of-the-ancients.md#L547)
- Rage I/II/III can support Minion Skills. [L548](../poe2-0.5.0-return-of-the-ancients.md#L548)
- Ratha's Assault grants fewer loaded bolts and lower attack speed. [L549](../poe2-0.5.0-return-of-the-ancients.md#L549)
- Refraction I/II adds Deflection Rating from Evasion Rating to supported Banner skills. [L550](../poe2-0.5.0-return-of-the-ancients.md#L550), [L551](../poe2-0.5.0-return-of-the-ancients.md#L551)
- Shock Conduction II can no longer be obtained. [L552](../poe2-0.5.0-return-of-the-ancients.md#L552)
- Uhtred's Augury and Uhtred's Omen grant +2 supported skill levels instead of +3. [L554](../poe2-0.5.0-return-of-the-ancients.md#L554), [L555](../poe2-0.5.0-return-of-the-ancients.md#L555)
- Volt grants fewer Voltaic Charges per metre and changes extra Lightning Damage scaling per charge consumed. [L556](../poe2-0.5.0-return-of-the-ancients.md#L556)

## Item-Granted and Item-Related Skill Changes

- The Vertex now rolls Curse Skill Gem levels instead of all Skill Gem levels. [L200](../poe2-0.5.0-return-of-the-ancients.md#L200)
- Chober Chaber now grants +2-3 to all Minion Skills. [L567](../poe2-0.5.0-return-of-the-ancients.md#L567)
- Collapsing Horizon now grants increased Elemental Damage generally rather than only Elemental Damage with Attacks. [L978](../poe2-0.5.0-return-of-the-ancients.md#L978)
- The Hollow Mask now grants Wildwood's Gifts and improves Remnant Skill reservation efficiency. [L573](../poe2-0.5.0-return-of-the-ancients.md#L573)
- Levinstone replaces +1 all Lightning Skills with Lightning Skills Chain +1 times. [L577](../poe2-0.5.0-return-of-the-ancients.md#L577)
- Unborn Lich granted skills were broadly retuned: several mana costs were reduced to zero, His Foul Emergence now has a fixed 8 second cooldown, His Vile Intrusion gains much higher Impale Magnitude and more impales at high gem levels, and His Winnowing Flame casts faster with stronger Grisly Pyres. [L981-L984](../poe2-0.5.0-return-of-the-ancients.md#L981-L984)
- Skill level modifiers on attack weapons, quivers, and Perfect Essence of Battle were reduced. [L613-L620](../poe2-0.5.0-return-of-the-ancients.md#L613-L620)

## Skill and Gem Bug Fixes

- The minion damage bonus against non-unique enemies introduced in 0.3 now functions correctly, increasing late-game minion damage while removing that bonus from displayed minion skill damage. [L748](../poe2-0.5.0-return-of-the-ancients.md#L748)
- Ritual Sacrifice, Pounce/Marks, Mirage Archer/Mirage Deadeye, Devour/Feral Invocation, clone/minion handling for "skills you use yourself" supports, and Hollow Palm Technique all received skill-function bug fixes. [L750-L754](../poe2-0.5.0-return-of-the-ancients.md#L750-L754), [L764](../poe2-0.5.0-return-of-the-ancients.md#L764), [L757](../poe2-0.5.0-return-of-the-ancients.md#L757)
- Projectile-count and chain modifier fixes affect rain-of-arrows-like skills and beam skills, and Arc no longer gains Lightning Infused stats without spending a Lightning Infusion. [L759-L763](../poe2-0.5.0-return-of-the-ancients.md#L759-L763)
- Unearth supportability, Unearth Bone Constructs from totems, Spell Totem/Align Fate Raging Spirit generation, and disabled Dialla's Desire support behavior were fixed. [L765](../poe2-0.5.0-return-of-the-ancients.md#L765), [L768-L771](../poe2-0.5.0-return-of-the-ancients.md#L768-L771), [L769](../poe2-0.5.0-return-of-the-ancients.md#L769)
- Comet quality, Devour/Lightning Warp corpse interactions, Poison Spores Support prices, Burning Inscription Support ground placement, Low Tolerance description, and Arctic Howl/Echoing Cry were fixed. [L762-L782](../poe2-0.5.0-return-of-the-ancients.md#L762-L782)
- Tactician's Cannons, Ready! now works with listed player skills; dual-wield simultaneous strikes now use intended average weapon attack time; Forge Hammer and Heightened Charges tracking/support interactions were fixed. [L785](../poe2-0.5.0-return-of-the-ancients.md#L785), [L787](../poe2-0.5.0-return-of-the-ancients.md#L787), [L790](../poe2-0.5.0-return-of-the-ancients.md#L790), [L791](../poe2-0.5.0-return-of-the-ancients.md#L791)
- Living Lightning II, Into the Breach with Selfless Remnants, Azmeri Spirit Possession player versions, Dialla's Desire with Meta Skill and item-granted Skill Gems, and Hayoxi's Fulmination supportability were fixed. [L792-L796](../poe2-0.5.0-return-of-the-ancients.md#L792-L796)
- Shockwave Totem, Echoing Cry, Mirage Archer/Deadeye supportability, Empower stacking, triggered-skill classification, Grim Feast minion revival, Ice Nova repeats, His Winnowing Flame, and channelled skill interruption were fixed. [L798-L811](../poe2-0.5.0-return-of-the-ancients.md#L798-L811)
- Arc, triggered skill energy generation, Stoicism Support, Volt Support, Iron Ward/Astral Projection, Lightning Warp targeting, Ancestrally Boosted attack area, and Blink/Parry/Raise Shield skill-use tracking were fixed. [L826](../poe2-0.5.0-return-of-the-ancients.md#L826), [L830-L837](../poe2-0.5.0-return-of-the-ancients.md#L830-L837)
- Queued skills can update targets correctly again, and additional dashes from Killing Palm and Staggering Palm should now hit their target. [L776-L777](../poe2-0.5.0-return-of-the-ancients.md#L776-L777)
- Varashta's Blessing Lineage Support, Totem skill-panel prompts, hidden Ascendancy-granted Skills when cutting Support Gems, Always Attack Without Moving selection, and Pounce Meta Gem art were fixed or clarified. [L858](../poe2-0.5.0-return-of-the-ancients.md#L858), [L862](../poe2-0.5.0-return-of-the-ancients.md#L862), [L870](../poe2-0.5.0-return-of-the-ancients.md#L870), [L875](../poe2-0.5.0-return-of-the-ancients.md#L875), [L887](../poe2-0.5.0-return-of-the-ancients.md#L887)
