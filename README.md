# SGRPG - Singapore RPG

A text-based RPG loot system with web-based editor.

## Files

- `loot_database.json` - Core loot data (rarities, slots, item types, consumables)
- `index.html` - Web editor for viewing and editing the database

## Usage

1. Open `index.html` in any browser
2. Edit loot data through the UI
3. Export JSON when done
4. Copy exported JSON to `loot_database.json`

## Data Structure

### Rarities (E/D/C/B/A/S)
- `name` - Display name
- `color` - Hex color for UI
- `drop_weight` - Lower = rarer
- `salvage_multiplier` - Material return multiplier

### Slots
- `main_hand`, `off_hand` - Weapons
- `head`, `body`, `gloves`, `boots` - Armor
- `necklace`, `ring_1`, `ring_2` - Accessories

### Item Types
Base templates for equipment (sword, dagger, staff, shield, etc.)

### Consumable Types
- Potions (health, mana, stamina, elixir)
- Skill Stones
- Currencies (gold, premium token, honor point)
- Materials (iron ore, leather, magic essence, ancient rune)

## Future Expansion

- Add stat templates (damage, armor, effects)
- Add procedural generation rules
- Add loot tables for enemies/zones
- Add crafting recipes
