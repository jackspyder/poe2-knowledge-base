# PoE2 0.5.0 Cooldown, Trigger, Repeat, Echo, and Frequency Mechanics

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Repeat and Echo

- Chronomancer's Now and Again is reworked to give Cascadable Spells a 20% chance to Echo and Repeatable Spells a 20% chance to Repeat. [L378-L380](../poe2-0.5.0-return-of-the-ancients.md#L378-L380)
- Echoing Pulse now grants Echoed Spells increased Area of Effect and loses a nonfunctional final-repeat Area of Effect stat. [L430](../poe2-0.5.0-return-of-the-ancients.md#L430)
- Ice Nova can no longer originate from Frostbolt while cascading sideways. [L987](../poe2-0.5.0-return-of-the-ancients.md#L987)
- Ice Nova repeated visual and audio issues were fixed. [L810](../poe2-0.5.0-return-of-the-ancients.md#L810)

## Cooldown Recovery as Frequency Scaling

- Align Fate, Ghost Dance, Mirror of Refraction, Ravenous Swarm, and Time of Need now explicitly let Cooldown Recovery Rate apply to their appearance, gain, spawn, or blessing frequency. [L474](../poe2-0.5.0-return-of-the-ancients.md#L474), [L491](../poe2-0.5.0-return-of-the-ancients.md#L491), [L499](../poe2-0.5.0-return-of-the-ancients.md#L499), [L504](../poe2-0.5.0-return-of-the-ancients.md#L504), [L519](../poe2-0.5.0-return-of-the-ancients.md#L519)
- Ghost Dance's interval is no longer a duration, loses a Ghost Shroud on hit, and gains a longer base shroud interval. [L491](../poe2-0.5.0-return-of-the-ancients.md#L491), [L1026](../poe2-0.5.0-return-of-the-ancients.md#L1026)
- Time of Need's blessing interval is reduced at gem levels 8-20 while moving into the same cooldown-recovery-frequency model. [L519](../poe2-0.5.0-return-of-the-ancients.md#L519)
- Owl Idol grants Cooldown Recovery Rate from Foci, and Boar Idol's bonded modifier improves Warcry Cooldown Recovery Rate from Gloves. [L654](../poe2-0.5.0-return-of-the-ancients.md#L654), [L651](../poe2-0.5.0-return-of-the-ancients.md#L651)

## Triggered Skills and Trigger Tags

- Lunar Blessing's triggered Moonbeams are no longer considered melee skills. [L496](../poe2-0.5.0-return-of-the-ancients.md#L496)
- Static Shocks now clarifies that it triggers from shocking hits. [L553](../poe2-0.5.0-return-of-the-ancients.md#L553)
- Corrupting Cry I/II, Decaying Hex, and Paquate's Pact now trigger separate scaled skills instead of making the supported skill directly apply Corrupted Blood or Decay. [L534-L535](../poe2-0.5.0-return-of-the-ancients.md#L534-L535), [L547](../poe2-0.5.0-return-of-the-ancients.md#L547)
- Doedre's Undoing now creates interval-spawned Witchtoads from Cursed Ground instead of turning Cursed Ground into Hazards. [L537](../poe2-0.5.0-return-of-the-ancients.md#L537)
- Many skills that previously had no cost now cost 0 Mana, including triggered skills from support gems and other sources, so additional costs can now apply to those triggered skills. [L471](../poe2-0.5.0-return-of-the-ancients.md#L471)
- Svalinn's Cast on Block makes supported skills cost nothing. [L587](../poe2-0.5.0-return-of-the-ancients.md#L587)
- Fire Skills used by Spell Totems or Visages from Align Fate no longer generate Raging Spirits. [L771-L772](../poe2-0.5.0-return-of-the-ancients.md#L771-L772)

## Channelled and Persistent Skill Support

- Feral Invocation no longer bypasses the cooldown of socketed skills. [L485](../poe2-0.5.0-return-of-the-ancients.md#L485)
- Mirage Archer and Mirage Deadeye can support channelled skills including Snipe, Plasma Blast, and Detonating Arrow. [L498](../poe2-0.5.0-return-of-the-ancients.md#L498)
- Ancestral Bond clarifies that summoning a Spell Totem is not itself a spell, so added spell costs do not apply to the totem-summoning action. [L407](../poe2-0.5.0-return-of-the-ancients.md#L407)
- Spell Cascade is no longer limited to supporting spells you use yourself. [L989](../poe2-0.5.0-return-of-the-ancients.md#L989)
- Atziri's Impatience can no longer support Persistent Skills, and Overabundance III now describes that restriction correctly. [L530](../poe2-0.5.0-return-of-the-ancients.md#L530), [L545](../poe2-0.5.0-return-of-the-ancients.md#L545)
- Click-to-move no longer interrupts channelling for skills that can be used while moving, improving Flame Breath and Incinerate usability. [L707](../poe2-0.5.0-return-of-the-ancients.md#L707)
- Channelled skills can now be interrupted by another channelled skill. [L812](../poe2-0.5.0-return-of-the-ancients.md#L812)

## Skill-Specific Cooldowns and Trigger Rates

- Inevitable Agony is no longer a Curse and now has a 2 second cooldown. [L384](../poe2-0.5.0-return-of-the-ancients.md#L384)
- Grim Feast's Grim Resurrection now has a 1 second cooldown. [L492](../poe2-0.5.0-return-of-the-ancients.md#L492)
- Pounce has a longer cooldown at gem levels 3-20. [L503](../poe2-0.5.0-return-of-the-ancients.md#L503)
- His Foul Emergence from Unborn Lich now has a fixed 8 second cooldown at all levels. [L993](../poe2-0.5.0-return-of-the-ancients.md#L993)
- Tempest Bell can have 3 active Bells and triggers shockwaves every 0.3 seconds instead of 0.25 seconds. [L516](../poe2-0.5.0-return-of-the-ancients.md#L516)
- Oil Barrage consumes Power Charges faster while channelling Empowered Oil Barrage. [L500](../poe2-0.5.0-return-of-the-ancients.md#L500)

## Bug Fixes

- Ritual Sacrifice no longer gains a cooldown specifically at level 20. [L751](../poe2-0.5.0-return-of-the-ancients.md#L751)
- Devour and Feral Invocation now interact correctly. [L755](../poe2-0.5.0-return-of-the-ancients.md#L755)
- Arctic Howl no longer empowers you in human form while using Echoing Cry, and Echoing Cry can no longer support Ancestral Cry. [L783](../poe2-0.5.0-return-of-the-ancients.md#L783), [L800](../poe2-0.5.0-return-of-the-ancients.md#L800)
- Some inherently triggered skills are now correctly considered triggered skills for other stats. [L807](../poe2-0.5.0-return-of-the-ancients.md#L807)
- His Winnowing Flame's triggered ignite-consuming explosions now deal damage. [L811](../poe2-0.5.0-return-of-the-ancients.md#L811)
- Dialla's Desire Lineage Support no longer functions when socketed but disabled. [L770](../poe2-0.5.0-return-of-the-ancients.md#L770)
- Queued skills can update targets correctly again. [L777](../poe2-0.5.0-return-of-the-ancients.md#L777)
- Certain triggered skills no longer generate energy. [L831](../poe2-0.5.0-return-of-the-ancients.md#L831)
- Blink, Parry, and Raise Shield now count as skill uses, and Parry/Raise Shield now count as channelling. [L838](../poe2-0.5.0-return-of-the-ancients.md#L838)

## Practical Read

- The patch makes "frequency" a formal tuning axis for several interval-based skills; Cooldown Recovery Rate is now a direct scaling stat for those mechanics.
- Trigger builds need retesting because several direct-application effects were converted into separate triggered skills, and triggered-skill classification bugs were fixed.
- Channelled-skill usability improves, but supportability and interruption behavior changed enough that existing channel setups need verification.
