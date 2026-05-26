# PoE2 0.5.0 Meta Gems and Skills

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

This is an extracted working view of meta gem, skill, support, and skill-related bug-fix entries. The source capture is unchanged; links point back to the relevant source lines.

## New Skills, Supports, and Build Tooling

- Runes of Aldur now lists 23 Kalguuran Skills craftable from Remnants; the update log explicitly adds Rain of Blades and Wardbound Minions to the skill list. [L60](../poe2-0.5.0-return-of-the-ancients.md#L60), [L936](../poe2-0.5.0-return-of-the-ancients.md#L936)
- Runes of Aldur adds 7 Kalguuran Supports craftable from Remnants, with Kalguuran Conviction removed from the support list. [L61](../poe2-0.5.0-return-of-the-ancients.md#L61), [L892](../poe2-0.5.0-return-of-the-ancients.md#L892)
- 23 new Lineage Supports were added, including Olroth's Conviction and Olroth's Hubris. [L289-L311](../poe2-0.5.0-return-of-the-ancients.md#L289-L311)
- Minion Splash and Minion Splash II Strength Support Gems were added. [L355](../poe2-0.5.0-return-of-the-ancients.md#L355)
- Build Guide support was added, including downloadable `.build` files with passive, ascendancy, skill gem, and support gem recommendations. [L357](../poe2-0.5.0-return-of-the-ancients.md#L357)

## Ascendancy Skill and Gem Interactions

- Into the Breach wording and remnant pickup-range visuals were clarified. [L369](../poe2-0.5.0-return-of-the-ancients.md#L369), [L370](../poe2-0.5.0-return-of-the-ancients.md#L370)
- Chronomancer changes replace Rapid River with Now and Again, rework Now and Again around Echo/Repeat chance, move Unbound Encore, and update Ultimate Command requirements. [L376-L379](../poe2-0.5.0-return-of-the-ancients.md#L376-L379)
- Temporal Rift has a shorter cast time and removes delayed damage from Phased Form. [L381](../poe2-0.5.0-return-of-the-ancients.md#L381)
- Inevitable Agony is reworked from a Curse into a cooldown skill with a Life Loss debuff, cull behavior, longer duration, new quality stat, and new visuals. [L382](../poe2-0.5.0-return-of-the-ancients.md#L382)
- Sands of Time now grants Skill Speed rather than Cast Speed. [L383](../poe2-0.5.0-return-of-the-ancients.md#L383)
- Gemling Legionnaire gains Virtuous Barrier, and Advanced Thaumaturgy now gives socketed skills extra quality effects rather than granting Thaumaturgical Dynamism. [L387](../poe2-0.5.0-return-of-the-ancients.md#L387), [L388](../poe2-0.5.0-return-of-the-ancients.md#L388)
- Pathfinder's Running Assault now has a smaller movement-speed-while-using-skills benefit. [L392](../poe2-0.5.0-return-of-the-ancients.md#L392)
- Ancestral Bond makes totem placement costless and charge-free, keeps Spirit reservation, and doubles totem limit. [L405](../poe2-0.5.0-return-of-the-ancients.md#L405)
- Trusted Kinship now focuses on Companion Skill reservation efficiency versus non-Companion Skill reservation efficiency. [L406](../poe2-0.5.0-return-of-the-ancients.md#L406)

## System-Wide Skill and Gem Rules

- Skills with fixed projectile counts can benefit from effects that redirect projectile-count modifiers. [L466](../poe2-0.5.0-return-of-the-ancients.md#L466)
- Skills with 0 Mana cost now display that cost, which clarifies interactions with added-cost effects. [L467](../poe2-0.5.0-return-of-the-ancients.md#L467)
- Crossbow Ammunition Skills now have a base cost of 0 instead of a disabled cost, so added costs can apply. [L468](../poe2-0.5.0-return-of-the-ancients.md#L468)
- Oil Ground ignites can no longer compound with themselves or with other ignites from the same skill use. [L469](../poe2-0.5.0-return-of-the-ancients.md#L469)
- Command Skills now have a 50% movement speed penalty during use instead of 70%. [L470](../poe2-0.5.0-return-of-the-ancients.md#L470)
- Seal supports are standardized across Unleash, Expand, Salvo, and Freezing Salvo. [L521](../poe2-0.5.0-return-of-the-ancients.md#L521)
- Freezing Salvo and Salvo Support can now gain Seals while the relevant skill is being performed. [L522](../poe2-0.5.0-return-of-the-ancients.md#L522)
- Salvo Support now gains Seals faster, has a higher Seal cap, and grants one projectile per Seal. [L523](../poe2-0.5.0-return-of-the-ancients.md#L523)
- Plus-to-level modifiers for melee, projectile, and attack skill gems on weapons and quivers are lowered or gated to higher item levels. [L609-L614](../poe2-0.5.0-return-of-the-ancients.md#L609-L614)
- Perfect Essence of Battle now grants lower attack skill levels on attack weapons. [L616](../poe2-0.5.0-return-of-the-ancients.md#L616)
- Jeweller's Orbs can now add sockets to item-granted skills, and using one on an item with multiple granted skills affects all of those skills. [L588](../poe2-0.5.0-return-of-the-ancients.md#L588)
- Fox Idol changes body-armour bonded effects from global skill quality to idol-bonded-modifier behavior, while still offering +5% skill quality as the bonded modifier. [L649](../poe2-0.5.0-return-of-the-ancients.md#L649)

## Meta, Trigger, and Energy Mechanics

- Feral Invocation no longer bypasses socketed skill cooldowns. [L481](../poe2-0.5.0-return-of-the-ancients.md#L481)
- Flame Breath now has an Energy Gain penalty similar to Incinerate. [L482](../poe2-0.5.0-return-of-the-ancients.md#L482)
- Corrupting Cry I/II and Decaying Hex now trigger separate scaled skills instead of directly applying Corrupted Blood or Decay through the supported skill. [L530](../poe2-0.5.0-return-of-the-ancients.md#L530), [L531](../poe2-0.5.0-return-of-the-ancients.md#L531)
- Static Shocks received a trigger-condition description clarification. [L549](../poe2-0.5.0-return-of-the-ancients.md#L549)
- Svalinn's Cast on Block Skill now makes supported skills cost nothing. [L583](../poe2-0.5.0-return-of-the-ancients.md#L583)
- Zerphi's Genesis gives skills from Corrupted Gems cost efficiency during flask effects. [L585](../poe2-0.5.0-return-of-the-ancients.md#L585)
- Bug fixes cover Feral Invocation and Devour, triggered-skill classification, triggered skills generating energy, Dialla's Desire quality for Meta Skill and item-granted Skill Gems, Pounce gem art as a Meta Gem, and channelled skill interruption. [L746](../poe2-0.5.0-return-of-the-ancients.md#L746), [L787](../poe2-0.5.0-return-of-the-ancients.md#L787), [L798](../poe2-0.5.0-return-of-the-ancients.md#L798), [L803](../poe2-0.5.0-return-of-the-ancients.md#L803), [L822](../poe2-0.5.0-return-of-the-ancients.md#L822), [L879](../poe2-0.5.0-return-of-the-ancients.md#L879)

## Skill Changes

- Align Fate now lets Cooldown Recovery Rate affect visage appearance frequency. [L471](../poe2-0.5.0-return-of-the-ancients.md#L471)
- Ancestral Warrior Totem loses a hidden delay and now describes delay as half the skill attack time. [L472](../poe2-0.5.0-return-of-the-ancients.md#L472)
- Bonestorm loses the Sustained tag. [L474](../poe2-0.5.0-return-of-the-ancients.md#L474)
- Boneshatter, Ice Strike, Shred, and Whirling Assault have adjusted attack-speed quality values. [L475](../poe2-0.5.0-return-of-the-ancients.md#L475), [L490](../poe2-0.5.0-return-of-the-ancients.md#L490), [L507](../poe2-0.5.0-return-of-the-ancients.md#L507), [L517](../poe2-0.5.0-return-of-the-ancients.md#L517)
- Comet and Fire-Infused Comet have lower listed damage values. [L476](../poe2-0.5.0-return-of-the-ancients.md#L476)
- Cull the Weak gets Can't be Evaded, higher damage, faster attack speed, lower mana costs, and longer dash range. [L477](../poe2-0.5.0-return-of-the-ancients.md#L477)
- Defiance Banner, Dread Banner, and War Banner lose movement penalties and gain larger base aura radius. [L478](../poe2-0.5.0-return-of-the-ancients.md#L478)
- Earthquake aftershock damage is increased. [L479](../poe2-0.5.0-return-of-the-ancients.md#L479)
- Eternal Rage must be active in both weapon sets and cannot be activated in only specific sets. [L480](../poe2-0.5.0-return-of-the-ancients.md#L480)
- Fortifying Cry only consumes one stack for shield-wall detonation and has lower shield Armour damage scaling. [L483](../poe2-0.5.0-return-of-the-ancients.md#L483)
- Fragmentation Rounds quality changes from more Physical Damage to extra Fragments per Shot. [L484](../poe2-0.5.0-return-of-the-ancients.md#L484)
- Freezing Salvo has lower Chill and Freeze Buildup scaling. [L485](../poe2-0.5.0-return-of-the-ancients.md#L485)
- Gathering Storm now detonates Tempest Bell with Perfectly Timed dash, adds shockwave rules, and changes quality. [L486](../poe2-0.5.0-return-of-the-ancients.md#L486)
- Ghost Dance is reworked around cooldown recovery, shroud loss on hit, and Energy Shield regeneration from Evasion. [L487](../poe2-0.5.0-return-of-the-ancients.md#L487), [L991](../poe2-0.5.0-return-of-the-ancients.md#L991)
- Grim Feast's Grim Resurrection now has a 1 second cooldown. [L488](../poe2-0.5.0-return-of-the-ancients.md#L488)
- Ice Shot's Ice Shards lose their extra Freeze Buildup. [L489](../poe2-0.5.0-return-of-the-ancients.md#L489)
- Ice Nova can no longer originate from Frostbolt while cascading sideways. [L952](../poe2-0.5.0-return-of-the-ancients.md#L952)
- Lightning Arrow beams can no longer chain multiple times onto the same target. [L491](../poe2-0.5.0-return-of-the-ancients.md#L491)
- Lunar Blessing's triggered Moonbeams are no longer melee skills. [L492](../poe2-0.5.0-return-of-the-ancients.md#L492)
- Magma Barrier, Resonating Shield, and Shield Wall have lower shield-stat damage scaling. [L493](../poe2-0.5.0-return-of-the-ancients.md#L493), [L502](../poe2-0.5.0-return-of-the-ancients.md#L502), [L506](../poe2-0.5.0-return-of-the-ancients.md#L506)
- Mirage Archer and Mirage Deadeye can now be used with channelled skills. [L494](../poe2-0.5.0-return-of-the-ancients.md#L494)
- Mirror of Refraction now lets Cooldown Recovery Rate affect mirror appearance frequency. [L495](../poe2-0.5.0-return-of-the-ancients.md#L495)
- Oil Barrage has lower mana cost, adjusted Empowered channel costs, damage changes, and faster power-charge consumption. [L496](../poe2-0.5.0-return-of-the-ancients.md#L496)
- Parry has animation-matched area changes and loses bonus attack distance. [L497](../poe2-0.5.0-return-of-the-ancients.md#L497)
- Poisonburst Arrow has fixed poison duration and lower quality magnitude scaling. [L498](../poe2-0.5.0-return-of-the-ancients.md#L498)
- Pounce has a longer cooldown. [L499](../poe2-0.5.0-return-of-the-ancients.md#L499)
- Ravenous Swarm now lets Cooldown Recovery Rate affect swarm spawning frequency. [L500](../poe2-0.5.0-return-of-the-ancients.md#L500)
- Rend fixes Lightning-Charged double scaling and adjusts damage to compensate. [L501](../poe2-0.5.0-return-of-the-ancients.md#L501)
- Rolling Magma chains more at all gem levels. [L503](../poe2-0.5.0-return-of-the-ancients.md#L503)
- Rolling Slam has shorter total attack time and lower slam damage values. [L504](../poe2-0.5.0-return-of-the-ancients.md#L504)
- Shattering Spite has lower damaging ailment magnitude and loses instant Life Leech from explosions. [L505](../poe2-0.5.0-return-of-the-ancients.md#L505)
- Snipe has adjusted attack and explosion damage values and a smaller Icy Blast explosion radius. [L508](../poe2-0.5.0-return-of-the-ancients.md#L508)
- Spell Totem can be used while moving and has updated animation. [L509](../poe2-0.5.0-return-of-the-ancients.md#L509)
- Supercharged Slam's fixed attack time text is clarified. [L510](../poe2-0.5.0-return-of-the-ancients.md#L510)
- Primal Strikes now has a higher minimum gem level, while Tame Beast has a lower minimum gem level, immediately summons newly tamed beasts when you have enough Spirit, and increases summoned beast damage. [L511](../poe2-0.5.0-return-of-the-ancients.md#L511), [L953](../poe2-0.5.0-return-of-the-ancients.md#L953)
- Tempest Bell can be Ancestrally Boosted like a Strike, can have 3 active bells, and has adjusted shockwave damage and trigger frequency. [L512](../poe2-0.5.0-return-of-the-ancients.md#L512)
- Toxic Growth fires more Pustules but has a much lower Pustule limit and different quality scaling. [L513](../poe2-0.5.0-return-of-the-ancients.md#L513)
- Thrashing Vines frequency text is clarified. [L514](../poe2-0.5.0-return-of-the-ancients.md#L514)
- Time of Need now lets Cooldown Recovery Rate affect blessing frequency and has a shorter interval. [L515](../poe2-0.5.0-return-of-the-ancients.md#L515)
- Volcano has higher base Critical Hit Chance. [L516](../poe2-0.5.0-return-of-the-ancients.md#L516)
- Wing Blast shockwave damage is increased. [L518](../poe2-0.5.0-return-of-the-ancients.md#L518)

## Support Changes

- Advancing Storm and Morgana's Tempest can support any Storm Skill under any conditions. [L524](../poe2-0.5.0-return-of-the-ancients.md#L524), [L540](../poe2-0.5.0-return-of-the-ancients.md#L540)
- Arjun's Medal has a lower chance to load a bolt on killing blow. [L525](../poe2-0.5.0-return-of-the-ancients.md#L525)
- Atziri's Impatience can no longer support Persistent Skills. [L526](../poe2-0.5.0-return-of-the-ancients.md#L526)
- Bhatair's Vengeance now grants cold damage based on Rage at a lower rate but longer duration. [L527](../poe2-0.5.0-return-of-the-ancients.md#L527)
- Brink I can be cut as a level 1 Support Gem. [L528](../poe2-0.5.0-return-of-the-ancients.md#L528)
- Culmination II changes Combo loss timing, max Combo, and damage per Combo. [L529](../poe2-0.5.0-return-of-the-ancients.md#L529)
- Dialla's Desire support quality bonus is reduced to +5%. [L532](../poe2-0.5.0-return-of-the-ancients.md#L532)
- Doedre's Undoing now spawns exploding Witchtoads from Cursed Ground instead of making it a Hazard. [L533](../poe2-0.5.0-return-of-the-ancients.md#L533)
- Infernal Legion I/II reduce minion maximum-Life self-damage and ignite scaling; Infernal Legion II also grants Fire Resistance. Infernal Legion III can no longer be obtained. [L534](../poe2-0.5.0-return-of-the-ancients.md#L534), [L535](../poe2-0.5.0-return-of-the-ancients.md#L535), [L536](../poe2-0.5.0-return-of-the-ancients.md#L536)
- Living Lightning no longer replaces minions when already at the minion cap. [L537](../poe2-0.5.0-return-of-the-ancients.md#L537)
- Mark of Siphoning adds Mana Leech from Physical Attack Damage, and Mark of Siphoning II adds both Mana and Life Leech from Physical Attack Damage. [L538](../poe2-0.5.0-return-of-the-ancients.md#L538), [L539](../poe2-0.5.0-return-of-the-ancients.md#L539)
- Spell Cascade is no longer limited to spells you use yourself. [L954](../poe2-0.5.0-return-of-the-ancients.md#L954)
- Overabundance III now describes its Persistent Skill restriction correctly. [L541](../poe2-0.5.0-return-of-the-ancients.md#L541)
- Overextend can no longer be obtained. [L542](../poe2-0.5.0-return-of-the-ancients.md#L542)
- Paquate's Pact now triggers a scaled Corrupted Blood skill and changes its Life-cost behavior. [L543](../poe2-0.5.0-return-of-the-ancients.md#L543)
- Rage I/II/III can support Minion Skills. [L544](../poe2-0.5.0-return-of-the-ancients.md#L544)
- Ratha's Assault grants fewer loaded bolts and lower attack speed. [L545](../poe2-0.5.0-return-of-the-ancients.md#L545)
- Refraction I/II adds Deflection Rating from Evasion Rating to supported Banner skills. [L546](../poe2-0.5.0-return-of-the-ancients.md#L546), [L547](../poe2-0.5.0-return-of-the-ancients.md#L547)
- Shock Conduction II can no longer be obtained. [L548](../poe2-0.5.0-return-of-the-ancients.md#L548)
- Uhtred's Augury and Uhtred's Omen grant +2 supported skill levels instead of +3. [L550](../poe2-0.5.0-return-of-the-ancients.md#L550), [L551](../poe2-0.5.0-return-of-the-ancients.md#L551)
- Volt grants fewer Voltaic Charges per metre and changes extra Lightning Damage scaling per charge consumed. [L552](../poe2-0.5.0-return-of-the-ancients.md#L552)

## Item-Granted and Item-Related Skill Changes

- The Vertex now rolls Curse Skill Gem levels instead of all Skill Gem levels. [L199](../poe2-0.5.0-return-of-the-ancients.md#L199)
- Chober Chaber now grants +2-3 to all Minion Skills. [L563](../poe2-0.5.0-return-of-the-ancients.md#L563)
- Collapsing Horizon now grants increased Elemental Damage generally rather than only Elemental Damage with Attacks. [L955](../poe2-0.5.0-return-of-the-ancients.md#L955)
- The Hollow Mask now grants Wildwood's Gifts and improves Remnant Skill reservation efficiency. [L569](../poe2-0.5.0-return-of-the-ancients.md#L569)
- Levinstone replaces +1 all Lightning Skills with Lightning Skills Chain +1 times. [L573](../poe2-0.5.0-return-of-the-ancients.md#L573)
- Unborn Lich granted skills were broadly retuned: several mana costs were reduced to zero, His Foul Emergence now has a fixed 8 second cooldown, His Vile Intrusion gains much higher Impale Magnitude and more impales at high gem levels, and His Winnowing Flame casts faster with stronger Grisly Pyres. [L958-L961](../poe2-0.5.0-return-of-the-ancients.md#L958-L961)
- Skill level modifiers on attack weapons, quivers, and Perfect Essence of Battle were reduced. [L609-L616](../poe2-0.5.0-return-of-the-ancients.md#L609-L616)

## Skill and Gem Bug Fixes

- Ritual Sacrifice, Pounce/Marks, Mirage Archer/Mirage Deadeye, Devour/Feral Invocation, clone/minion handling for "skills you use yourself" supports, and Hollow Palm Technique all received skill-function bug fixes. [L742-L746](../poe2-0.5.0-return-of-the-ancients.md#L742-L746), [L756](../poe2-0.5.0-return-of-the-ancients.md#L756), [L749](../poe2-0.5.0-return-of-the-ancients.md#L749)
- Projectile-count and chain modifier fixes affect rain-of-arrows-like skills and beam skills, and Arc no longer gains Lightning Infused stats without spending a Lightning Infusion. [L751-L755](../poe2-0.5.0-return-of-the-ancients.md#L751-L755)
- Unearth supportability, Unearth Bone Constructs from totems, Spell Totem/Align Fate Raging Spirit generation, and disabled Dialla's Desire support behavior were fixed. [L757](../poe2-0.5.0-return-of-the-ancients.md#L757), [L760-L763](../poe2-0.5.0-return-of-the-ancients.md#L760-L763), [L761](../poe2-0.5.0-return-of-the-ancients.md#L761)
- Comet quality, Devour/Lightning Warp corpse interactions, Poison Spores Support prices, Burning Inscription Support ground placement, Low Tolerance description, and Arctic Howl/Echoing Cry were fixed. [L754-L774](../poe2-0.5.0-return-of-the-ancients.md#L754-L774)
- Tactician's Cannons, Ready! now works with listed player skills; dual-wield simultaneous strikes now use intended average weapon attack time; Forge Hammer and Heightened Charges tracking/support interactions were fixed. [L777](../poe2-0.5.0-return-of-the-ancients.md#L777), [L779](../poe2-0.5.0-return-of-the-ancients.md#L779), [L782](../poe2-0.5.0-return-of-the-ancients.md#L782), [L783](../poe2-0.5.0-return-of-the-ancients.md#L783)
- Living Lightning II, Into the Breach with Selfless Remnants, Azmeri Spirit Possession player versions, Dialla's Desire with Meta Skill and item-granted Skill Gems, and Hayoxi's Fulmination supportability were fixed. [L784-L788](../poe2-0.5.0-return-of-the-ancients.md#L784-L788)
- Shockwave Totem, Echoing Cry, Mirage Archer/Deadeye supportability, Empower stacking, triggered-skill classification, Grim Feast minion revival, Ice Nova repeats, His Winnowing Flame, and channelled skill interruption were fixed. [L790-L803](../poe2-0.5.0-return-of-the-ancients.md#L790-L803)
- Arc, triggered skill energy generation, Stoicism Support, Volt Support, Iron Ward/Astral Projection, Lightning Warp targeting, Ancestrally Boosted attack area, and Blink/Parry/Raise Shield skill-use tracking were fixed. [L818](../poe2-0.5.0-return-of-the-ancients.md#L818), [L822-L829](../poe2-0.5.0-return-of-the-ancients.md#L822-L829)
- Queued skills can update targets correctly again, and additional dashes from Killing Palm and Staggering Palm should now hit their target. [L768-L769](../poe2-0.5.0-return-of-the-ancients.md#L768-L769)
- Varashta's Blessing Lineage Support, Totem skill-panel prompts, hidden Ascendancy-granted Skills when cutting Support Gems, Always Attack Without Moving selection, and Pounce Meta Gem art were fixed or clarified. [L850](../poe2-0.5.0-return-of-the-ancients.md#L850), [L854](../poe2-0.5.0-return-of-the-ancients.md#L854), [L862](../poe2-0.5.0-return-of-the-ancients.md#L862), [L867](../poe2-0.5.0-return-of-the-ancients.md#L867), [L879](../poe2-0.5.0-return-of-the-ancients.md#L879)
