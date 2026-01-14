# POE2 Perfect Waystone Crafting (T16+ Expert)

High-end farming requires **Perfect T16 Waystones** (>60% Pack Size + Desecrated Modifiers).

## 1. THE T16 CORRUPTION GAMBLE
You cannot "buy" T16 Waystones directly from NPCs.
- **The Method**: Use a **Vaal Orb** on a perfect 6-mod T15 Waystone.
- **Outcome (5% Success)**: T15 -> T16.
- **Outcome (95% Fail)**: Downgrade to T14, Brick (Reroll), or No Change.

## 2. THE DESECRATED LAYER
Desecrated modifiers (from Abyss) are mandatory for elite profit brackets.
1.  **Apply Preserved Vertebrae**: Adds a hidden desecrated mod to a Rare Waystone.
2.  **The Well of Souls**: Visit the Well to "unveil" and pick from 3 options.
3.  **Priority**: Pick **Monster Quantity** or **Pack Size** multipliers.

## 3. OMEN CONTROLLED ROLLING
Before corrupting, use Omens to force specific stats:
- **Omen of Chaotic Rarity**: Forces Rarity roll on next Chaos use.
- **Omen of Sinistral Necromancy**: Guarantees Desecration only adds Prefixes (important for density).

---

## 4. EXPERT FILTER REGEX (T16 READY)
```regex
"pa.+e: \+([5-6].|1..)%""qu.+y: \+([3-4].|1..)%"
```
*Filters for Waystones with 50%+ Pack Size and 30%+ Quantity.*
