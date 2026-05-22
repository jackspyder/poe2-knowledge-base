# PoE2 0.5.0 Cooldown, Trigger, Repeat, Echo, and Frequency Mechanics

Source: [Content Update 0.5.0 captured patch notes](../poe2-0.5.0-return-of-the-ancients.md)

## Repeat and Echo

- Chronomancer's Now and Again is reworked to give Cascadable Spells a 20% chance to Echo and Repeatable Spells a 20% chance to Repeat. [L361-L363](../poe2-0.5.0-return-of-the-ancients.md#L361-L363)
- Echoing Pulse now grants Echoed Spells increased Area of Effect and loses a nonfunctional final-repeat Area of Effect stat. [L407](../poe2-0.5.0-return-of-the-ancients.md#L407)
- Ice Nova repeated visual and audio issues were fixed. [L750](../poe2-0.5.0-return-of-the-ancients.md#L750)

## Cooldown Recovery as Frequency Scaling

- Align Fate, Ghost Dance, Mirror of Refraction, Ravenous Swarm, and Time of Need now explicitly let Cooldown Recovery Rate apply to their appearance, gain, spawn, or blessing frequency. [L444](../poe2-0.5.0-return-of-the-ancients.md#L444), [L459](../poe2-0.5.0-return-of-the-ancients.md#L459), [L467](../poe2-0.5.0-return-of-the-ancients.md#L467), [L472](../poe2-0.5.0-return-of-the-ancients.md#L472), [L487](../poe2-0.5.0-return-of-the-ancients.md#L487)
- Ghost Dance's interval is no longer a duration, loses a Ghost Shroud on hit, and gains a longer base shroud interval. [L459](../poe2-0.5.0-return-of-the-ancients.md#L459), [L841](../poe2-0.5.0-return-of-the-ancients.md#L841)
- Time of Need's blessing interval is reduced at gem levels 8-20 while moving into the same cooldown-recovery-frequency model. [L487](../poe2-0.5.0-return-of-the-ancients.md#L487)
- Owl Idol grants Cooldown Recovery Rate from Foci, and Boar Idol's bonded modifier improves Warcry Cooldown Recovery Rate from Gloves. [L617](../poe2-0.5.0-return-of-the-ancients.md#L617), [L614](../poe2-0.5.0-return-of-the-ancients.md#L614)

## Triggered Skills and Trigger Tags

- Lunar Blessing's triggered Moonbeams are no longer considered melee skills. [L464](../poe2-0.5.0-return-of-the-ancients.md#L464)
- Static Shocks now clarifies that it triggers from shocking hits. [L519](../poe2-0.5.0-return-of-the-ancients.md#L519)
- Corrupting Cry I/II, Decaying Hex, and Paquate's Pact now trigger separate scaled skills instead of making the supported skill directly apply Corrupted Blood or Decay. [L502-L503](../poe2-0.5.0-return-of-the-ancients.md#L502-L503), [L513](../poe2-0.5.0-return-of-the-ancients.md#L513)
- Doedre's Undoing now creates interval-spawned Witchtoads from Cursed Ground instead of turning Cursed Ground into Hazards. [L505](../poe2-0.5.0-return-of-the-ancients.md#L505)
- Svalinn's Cast on Block makes supported skills cost nothing. [L552](../poe2-0.5.0-return-of-the-ancients.md#L552)

## Channelled and Persistent Skill Support

- Feral Invocation no longer bypasses the cooldown of socketed skills. [L453](../poe2-0.5.0-return-of-the-ancients.md#L453)
- Mirage Archer and Mirage Deadeye can support channelled skills including Snipe, Plasma Blast, and Detonating Arrow. [L466](../poe2-0.5.0-return-of-the-ancients.md#L466)
- Atziri's Impatience can no longer support Persistent Skills, and Overabundance III now describes that restriction correctly. [L498](../poe2-0.5.0-return-of-the-ancients.md#L498), [L511](../poe2-0.5.0-return-of-the-ancients.md#L511)
- Click-to-move no longer interrupts channelling for skills that can be used while moving, improving Flame Breath and Incinerate usability. [L666](../poe2-0.5.0-return-of-the-ancients.md#L666)
- Channelled skills can now be interrupted by another channelled skill. [L752](../poe2-0.5.0-return-of-the-ancients.md#L752)

## Skill-Specific Cooldowns and Trigger Rates

- Inevitable Agony is no longer a Curse and now has a 2 second cooldown. [L367](../poe2-0.5.0-return-of-the-ancients.md#L367)
- Grim Feast's Grim Resurrection now has a 1 second cooldown. [L460](../poe2-0.5.0-return-of-the-ancients.md#L460)
- Pounce has a longer cooldown at gem levels 3-20. [L471](../poe2-0.5.0-return-of-the-ancients.md#L471)
- Tempest Bell can have 3 active Bells and triggers shockwaves every 0.3 seconds instead of 0.25 seconds. [L484](../poe2-0.5.0-return-of-the-ancients.md#L484)
- Oil Barrage consumes Power Charges faster while channelling Empowered Oil Barrage. [L468](../poe2-0.5.0-return-of-the-ancients.md#L468)

## Bug Fixes

- Ritual Sacrifice no longer gains a cooldown specifically at level 20. [L706](../poe2-0.5.0-return-of-the-ancients.md#L706)
- Devour and Feral Invocation now interact correctly. [L710](../poe2-0.5.0-return-of-the-ancients.md#L710)
- Arctic Howl no longer empowers you in human form while using Echoing Cry, and Echoing Cry can no longer support Ancestral Cry. [L723](../poe2-0.5.0-return-of-the-ancients.md#L723), [L740](../poe2-0.5.0-return-of-the-ancients.md#L740)
- Some inherently triggered skills are now correctly considered triggered skills for other stats. [L747](../poe2-0.5.0-return-of-the-ancients.md#L747)
- His Winnowing Flame's triggered ignite-consuming explosions now deal damage. [L751](../poe2-0.5.0-return-of-the-ancients.md#L751)
- Certain triggered skills no longer generate energy. [L770](../poe2-0.5.0-return-of-the-ancients.md#L770)
- Blink, Parry, and Raise Shield now count as skill uses, and Parry/Raise Shield now count as channelling. [L777](../poe2-0.5.0-return-of-the-ancients.md#L777)

## Practical Read

- The patch makes "frequency" a formal tuning axis for several interval-based skills; Cooldown Recovery Rate is now a direct scaling stat for those mechanics.
- Trigger builds need retesting because several direct-application effects were converted into separate triggered skills, and triggered-skill classification bugs were fixed.
- Channelled-skill usability improves, but supportability and interruption behavior changed enough that existing channel setups need verification.
