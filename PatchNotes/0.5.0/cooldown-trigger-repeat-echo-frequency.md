# PoE2 0.5.0 Cooldown, Trigger, Repeat, Echo, and Frequency Mechanics

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Repeat and Echo

- Chronomancer's Now and Again is reworked to give Cascadable Spells a 20% chance to Echo and Repeatable Spells a 20% chance to Repeat. [L376-L378](../poe2-0.5.0-return-of-the-ancients.md#L376-L378)
- Echoing Pulse now grants Echoed Spells increased Area of Effect and loses a nonfunctional final-repeat Area of Effect stat. [L428](../poe2-0.5.0-return-of-the-ancients.md#L428)
- Ice Nova can no longer originate from Frostbolt while cascading sideways. [L952](../poe2-0.5.0-return-of-the-ancients.md#L952)
- Ice Nova repeated visual and audio issues were fixed. [L801](../poe2-0.5.0-return-of-the-ancients.md#L801)

## Cooldown Recovery as Frequency Scaling

- Align Fate, Ghost Dance, Mirror of Refraction, Ravenous Swarm, and Time of Need now explicitly let Cooldown Recovery Rate apply to their appearance, gain, spawn, or blessing frequency. [L471](../poe2-0.5.0-return-of-the-ancients.md#L471), [L487](../poe2-0.5.0-return-of-the-ancients.md#L487), [L495](../poe2-0.5.0-return-of-the-ancients.md#L495), [L500](../poe2-0.5.0-return-of-the-ancients.md#L500), [L515](../poe2-0.5.0-return-of-the-ancients.md#L515)
- Ghost Dance's interval is no longer a duration, loses a Ghost Shroud on hit, and gains a longer base shroud interval. [L487](../poe2-0.5.0-return-of-the-ancients.md#L487), [L991](../poe2-0.5.0-return-of-the-ancients.md#L991)
- Time of Need's blessing interval is reduced at gem levels 8-20 while moving into the same cooldown-recovery-frequency model. [L515](../poe2-0.5.0-return-of-the-ancients.md#L515)
- Owl Idol grants Cooldown Recovery Rate from Foci, and Boar Idol's bonded modifier improves Warcry Cooldown Recovery Rate from Gloves. [L650](../poe2-0.5.0-return-of-the-ancients.md#L650), [L647](../poe2-0.5.0-return-of-the-ancients.md#L647)

## Triggered Skills and Trigger Tags

- Lunar Blessing's triggered Moonbeams are no longer considered melee skills. [L492](../poe2-0.5.0-return-of-the-ancients.md#L492)
- Static Shocks now clarifies that it triggers from shocking hits. [L549](../poe2-0.5.0-return-of-the-ancients.md#L549)
- Corrupting Cry I/II, Decaying Hex, and Paquate's Pact now trigger separate scaled skills instead of making the supported skill directly apply Corrupted Blood or Decay. [L530-L531](../poe2-0.5.0-return-of-the-ancients.md#L530-L531), [L543](../poe2-0.5.0-return-of-the-ancients.md#L543)
- Doedre's Undoing now creates interval-spawned Witchtoads from Cursed Ground instead of turning Cursed Ground into Hazards. [L533](../poe2-0.5.0-return-of-the-ancients.md#L533)
- Svalinn's Cast on Block makes supported skills cost nothing. [L583](../poe2-0.5.0-return-of-the-ancients.md#L583)
- Fire Skills used by Spell Totems or Visages from Align Fate no longer generate Raging Spirits. [L762-L763](../poe2-0.5.0-return-of-the-ancients.md#L762-L763)

## Channelled and Persistent Skill Support

- Feral Invocation no longer bypasses the cooldown of socketed skills. [L481](../poe2-0.5.0-return-of-the-ancients.md#L481)
- Mirage Archer and Mirage Deadeye can support channelled skills including Snipe, Plasma Blast, and Detonating Arrow. [L494](../poe2-0.5.0-return-of-the-ancients.md#L494)
- Spell Cascade is no longer limited to supporting spells you use yourself. [L954](../poe2-0.5.0-return-of-the-ancients.md#L954)
- Atziri's Impatience can no longer support Persistent Skills, and Overabundance III now describes that restriction correctly. [L526](../poe2-0.5.0-return-of-the-ancients.md#L526), [L541](../poe2-0.5.0-return-of-the-ancients.md#L541)
- Click-to-move no longer interrupts channelling for skills that can be used while moving, improving Flame Breath and Incinerate usability. [L700](../poe2-0.5.0-return-of-the-ancients.md#L700)
- Channelled skills can now be interrupted by another channelled skill. [L803](../poe2-0.5.0-return-of-the-ancients.md#L803)

## Skill-Specific Cooldowns and Trigger Rates

- Inevitable Agony is no longer a Curse and now has a 2 second cooldown. [L382](../poe2-0.5.0-return-of-the-ancients.md#L382)
- Grim Feast's Grim Resurrection now has a 1 second cooldown. [L488](../poe2-0.5.0-return-of-the-ancients.md#L488)
- Pounce has a longer cooldown at gem levels 3-20. [L499](../poe2-0.5.0-return-of-the-ancients.md#L499)
- His Foul Emergence from Unborn Lich now has a fixed 8 second cooldown at all levels. [L958](../poe2-0.5.0-return-of-the-ancients.md#L958)
- Tempest Bell can have 3 active Bells and triggers shockwaves every 0.3 seconds instead of 0.25 seconds. [L512](../poe2-0.5.0-return-of-the-ancients.md#L512)
- Oil Barrage consumes Power Charges faster while channelling Empowered Oil Barrage. [L496](../poe2-0.5.0-return-of-the-ancients.md#L496)

## Bug Fixes

- Ritual Sacrifice no longer gains a cooldown specifically at level 20. [L742](../poe2-0.5.0-return-of-the-ancients.md#L742)
- Devour and Feral Invocation now interact correctly. [L746](../poe2-0.5.0-return-of-the-ancients.md#L746)
- Arctic Howl no longer empowers you in human form while using Echoing Cry, and Echoing Cry can no longer support Ancestral Cry. [L774](../poe2-0.5.0-return-of-the-ancients.md#L774), [L791](../poe2-0.5.0-return-of-the-ancients.md#L791)
- Some inherently triggered skills are now correctly considered triggered skills for other stats. [L798](../poe2-0.5.0-return-of-the-ancients.md#L798)
- His Winnowing Flame's triggered ignite-consuming explosions now deal damage. [L802](../poe2-0.5.0-return-of-the-ancients.md#L802)
- Dialla's Desire Lineage Support no longer functions when socketed but disabled. [L761](../poe2-0.5.0-return-of-the-ancients.md#L761)
- Queued skills can update targets correctly again. [L768](../poe2-0.5.0-return-of-the-ancients.md#L768)
- Certain triggered skills no longer generate energy. [L822](../poe2-0.5.0-return-of-the-ancients.md#L822)
- Blink, Parry, and Raise Shield now count as skill uses, and Parry/Raise Shield now count as channelling. [L829](../poe2-0.5.0-return-of-the-ancients.md#L829)

## Practical Read

- The patch makes "frequency" a formal tuning axis for several interval-based skills; Cooldown Recovery Rate is now a direct scaling stat for those mechanics.
- Trigger builds need retesting because several direct-application effects were converted into separate triggered skills, and triggered-skill classification bugs were fixed.
- Channelled-skill usability improves, but supportability and interruption behavior changed enough that existing channel setups need verification.
