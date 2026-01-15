# POE2 T15+ Ritual Strategy (End-Game / Seasonal Reset)

## 1. TABLET SETUP

### Fishing Phase (The Hunt)
For a 10-map rotation. Aim for high Omen spawn rates and reroll count.
1.  **Freedom of Faith (Unique)**: Mandatory for reroll scaling. [Trade Link](https://www.pathofexile.com/trade2/search/poe2/Fate%20of%20the%20Vaal/9GJQPR4tK)
2.  **Reroll/defer cost**: Reroll cost reduction + defer cost reduction. [Trade Link](https://www.pathofexile.com/trade2/search/poe2/Fate%20of%20the%20Vaal/9zna9Y0yfK)
3.  **Stacker Tablet**: Focus +2/3 Rerolls. [Trade Link](https://www.pathofexile.com/trade2/search/poe2/Fate%20of%20the%20Vaal/6zj29q9XFG)

**v0.4+ Access**: King in the Mists now uses **Ritual Splinters**.
- **T1 Boss**: 50 Splinters.
- **T2 Boss**: 100 Splinters.
- **T3 Boss**: 150 Splinters.
- **Total**: 300 Splinters required to complete all three tiers (must be done in sequence).

**Priority Modifiers (0.4+):**
- **Rare Monsters**: 35-40% (Up to 120% total)
- **Magic Monsters (Teeming)**: 60-70%
- **Item Rarity**: 25-30%
- **Ritual Rerolls/Tribute Cost**: High Tier rolls only.

### Buying Phase (The Payoff)
Switch to this setup once high-value items are deferred. [Trade Link](https://www.pathofexile.com/trade2/search/poe2/Fate%20of%20the%20Vaal/op2gDq2YFl)
- **3x Tribute Tablets**: Magic Pack Size > Pack Size > Suffix Tribute%.
- **Strategy**: 10 Maps Fishing -> 2 Maps Buying.

---

## 2. WAYSTONE OPTIMIZATION (T15+)

### Crafting >60% Pack Size (Density Cap)
1.  **Omen of Chaotic Quality**: Force pack size priority on Rare T15 base.
2.  **6-Mod Lock**: Alchemy + Exalted Orbs to cap density.
3.  **Additives**: **Diluted Liquid Guilt** (Flat PS) + **Preserved Vertebrae** (Desecrate density).

**Priority Modifiers:**
- **Quantity/Rarity**: Highest bracket only.
- **Pack size / Monster Packs**: Synergize prefix + suffix for >60%.

---

## 3. ATLAS PASSIVE SETUPS

### Setup A: Fishing (Omen Hunting)
- **Ominous Portents**: 2x Omen chance.
- **Tempting Offers**: 2x Rerolls + Additional Window.
- **Promise of Devotion**: 50% Defer Cost Reduction (Mandatory to avoid losing Mirror/Whittling drops).

### Setup B: Buying (Tribute Engine)
- **Wildwood Line (4pt)**: Full Tribute from revived monsters.
- **Drop**: Omen chance/Rerolls.
- **Keep**: Defer cost reduction + 4 Ritual count.

---

## 4. T15+ MAP SELECTION

**v0.4 Density Note**: Open maps (Savannah, Steppe) received a ~10% density reduction vs. Indoor maps (Hive, Confluence) to balance clear speed.

| Elite Layouts (Run) | Avoid (Dead Slots / Low Density) |
| :--- | :--- |
| **Hive** (Highest Density) | Mesa |
| **Confluence** | Decay |
| **Willow** | Razed Fields |
| **Sandspit** | Forge |
| **Savannah** | Steaming Springs |
| **Steppe** | Blooming Field |
| **Wetlands** | |

---

## 5. HIGH-VALUE TARGETS & REGEX

### Chase Omens
- **Omen of Whittling**: Primary currency goal (150+ Exalts).
- **Annulment / Erasure**: (Dextral/Sinistral) for high-end crafting.
- **Amelioration**: Quality scaling.

### STASH REGEX (2025 Meta)

**Elite Waystones/Tablets:**
```regex
"rare mo.+: \+([3-4].|1..)%""teeming"
```
**Waystone Ready (>40% PS / >25% Q):**
```regex
"pa.+e: \+([4-6].|1..)%""qu.+y: \+([2-3].|1..)%"
```
**All-In-One High-End:**
```regex
"i.+ty: \+([4-9].|1..)%|pa.+e: \+([5-9].|1..)%"
```

### Video Reference Regex:
- **Rare + Rarity**: `r.+s: \+([4-9].|1..)%""i.+ty: \+([3-9].|1..)%`
- **Pack Size**: `m.+e: \+(4[2-9]|[5-9].|1..)%`
- **Magic Mobs**: `(6.|70)%.+ma`
- **Rare Mobs**: `(3[3-9]|40)%.+rare`
