# POE2 T15+ Anomaly Boss Farming (High-End / Expert)

## 1. THE VISION MECHANIC (Double Runs)
The core of high-end boss farming is the **Visions of Paradise** Unique Tablet.
- **Function**: Irradiates the target map.
- **Efficiency**: Run the map twice (Normal -> Irradiated).
- **Strategy**: Only use on **Jade Isles** or **Sacred Reservoir** (Temporal Sandstorm) once they are unlocked and juiced.
- **v0.4 Update**: Visions of Paradise is now applied directly to the map via the Tablet slot in the Map Device; tower range is no longer required.
- **Expert Tip**: The tablet is single-use. Ensure the map is pre-rolled for maximum Rarity before applying.

---

## 2. HIGH-VALUE TARGETS & DROPS
Focus exclusively on these two maps for the highest Exalt-per-hour returns.

| Map (Anomaly) | Boss | Chase Drop (Lineage Support) | Effect |
| :--- | :--- | :--- | :--- |
| **Jade Isles** | Manoki, the Chosen | **Rakiata's Flow** | Inverts enemy Elemental Resistances. |
| **Sacred Reservoir** | Zahmir, the Blade Sovereign | **Garukhan's Resolve** | Critical hit bifurcation / Move-to-use support. |

---

## 3. TABLET SYNERGY (THE JUICE)
High-end farming requires 3 tablet slots (6-mod maps).

| Tablet Priority | Modifier Goal | Purpose |
| :--- | :--- | :--- |
| **Visions of Paradise** | N/A (Unique) | Doubling the boss encounter. |
| **Overseer Tablet** | **+1 Map Level** / **Boss Rarity** | Scales drop quality and base item levels. |
| **Rarity Tablet** | **25-30% Item Rarity** | Critical for Lineage/Unique drop rates. |

---

## 4. THE HUNT (Loop & Atlas)
The "Loop" involves unlocking the anomaly maps through adjacent triggers.

### The Unlocking Loop
1.  **Jade Isles (Eye of the Storm)**: Clear coastal maps. Find **Karui Beacon** to clear the maelstrom.
2.  **Sacred Reservoir (Temporal Sandstorm)**: Clear desert maps. Find **3 Temporal Tethers** to clear the sandstorm.

**v0.4 Atlas Change**: You no longer need to find the beacon/tethers in *adjacent* maps specifically; clearing any map in the region now provides a % chance to reveal the Anomaly area directly.

### Atlas Strategy
- **Boss Specialization**: Take all nodes increasing Rarity and Quantity from Map Bosses.
- **Anomaly Discovery**: Prioritize nodes that increase the chance of finding Beacons/Tethers in adjacent maps.
- **Duplicate Bosses**: If a node allows for additional map bosses, take it (synergizes with Overseer tablets).

---

## 5. STORAGE & REGEX

### Stash Filter for Boss Juicing
```regex
"overseer""visions of paradise""rarity: \+([2-3].|1..)%""qu.+y: \+([1-2].|1..)%"
```

### High-End Target Tracking
- **Rakiata's Flow**: (20-40+ Divines). High liquidity item.
- **Garukhan's Resolve**: High value, specialized builds.
- **Karui Beacons**: Track for rapid Jade Isles resets.
