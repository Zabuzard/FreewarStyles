# FreewarStyles

Offers multiple CSS stylesheet modules for use in the MMORPG
[Freewar.de](https://www.freewar.de).

Hosted and available through Github Pages at
[zabuzard.github.io/FreewarStyles](https://zabuzard.github.io/FreewarStyles/).
Visit
[GitHub: Zabuzard/FreewarStyles](https://github.com/Zabuzard/FreewarStyles) for
the source code.

To use a module, put an `import` line in your custom style, for example:

```css
@import url("https://zabuzard.github.io/FreewarStyles/modules/dark/chat_colors.css");

@import url("https://zabuzard.github.io/FreewarStyles/modules/borderless_inventory.css");
@import url("https://zabuzard.github.io/FreewarStyles/modules/compact_inventory.css");
```

![Example in UI](https://i.vgy.me/5XSbAI.jpg)

## Modules

Available modules can be found in the directory
[modules](https://github.com/Zabuzard/FreewarStyles/tree/main/modules) and are
usually compatible with Light and Dark mode styles. For the ones that are
specific to a mode, see the subfolder `modules/light` and `modules/dark`
respectively.

### `dark/chat_colors.css`

Defines chat message and button colors suitable for dark mode styles.

![Dark Chat Colors](https://i.vgy.me/D5hdJA.jpg)

### `borderless_inventory.css`

Removes borders in the character menu and inventory.

![Borderless inventory](https://i.vgy.me/wSKylg.jpg)

### `compact_inventory.css`

Makes the inventory more compact, especially by making items only one instead of
two rows, moving the actions into the same line.

![Compact Inventory](https://i.vgy.me/mgJAhC.jpg)

Combine with `borderless_inventory.css` for a very compact look:

![Very compact](https://i.vgy.me/S5mZ6E.jpg)

### `weapon_durability.css`

Displays weapon durability directly in the menu, so mouse hover is not needed
anymore.

![Weapon Durability](https://i.vgy.me/1M7GsF.jpg)

### `dark/compact_status.css` or `light/compact_status.css`

Abbreviates status effects in the menu and shows the remaining time directly
without needing to mouse hover. Mouse hover to see the abbreviation fully
spelled out.

![Compact Status](https://i.vgy.me/F67aUB.jpg)

### `bigger_fast_spell_menu.css`

Increases the font size of the Fast Spell menu, so Fast Spells become easier to
click on. This is especially useful for 4K resolutions.

![Bigger Fast Spell Menu](https://i.vgy.me/4gChpd.jpg)

### `map_secure_locations.css`

Highlights each location on the map that is a secure location where players
cannot attack other players.

![Secure Locations Map](https://i.vgy.me/nNykbZ.jpg)

### `map_teleportation_blue.css`

Shows a blue circle on map tiles that are reachable with a "gepresste
Zauberkugel" (blue teleportation).

![Blue Teleportation Map](https://i.vgy.me/ERt3Kb.jpg)

### `map_teleportation_yellow.css`

Shows a yellow circle on map tiles that are reachable with a "geklebte, gelbe
Zauberkugel" (yellow teleportation).

![Yellow Teleportation Map](https://i.vgy.me/t1j4qX.jpg)

### `map_teleportation_portal.css`

Shows an orange diamond on map tiles that are reachable with a "Portalmaschine"
(portal device).

![Portal Teleportation Map](https://i.vgy.me/74NBCJ.jpg)

### `map_teleportation_ring_sandwind.css`

Shows a purple diamond on map tiles that are reachable with a "Ring des
Sandwindes" (Ring of Sandwinds, Taruner).

![Ring Sandwind Teleportation Map](https://i.vgy.me/iN6xIz.jpg)

### `map_teleportation_onlo.css`

Shows a green rectangle on map tiles that are reachable by Onlos travelling
through the forest.

![Onlo Teleportation Map](https://i.vgy.me/y2UbcK.jpg)

### `map_shops.css`

Shows a house icon on map tiles with a shop for selling items.

- blue color for the blue fraction shop
- red color for the red fraction shop
- orange color for a neutral shop
- purple color for a Natla shop

| Blue                                      | Red                                      | Neutral                                      | Natla                                      |
| ----------------------------------------- | ---------------------------------------- | -------------------------------------------- | ------------------------------------------ |
| ![Blue Shop](https://i.vgy.me/wyfoI5.jpg) | ![Red Shop](https://i.vgy.me/EkeThX.jpg) | ![Neutral Shop](https://i.vgy.me/HWde3c.jpg) | ![Natla Shop](https://i.vgy.me/wUraLl.jpg) |

### `map_aggressive_npcs.css`

Highlights locations on the map that can spawn aggressive NPCs. The map tiles
display their attack power. That way, you will not accidentally enter a location
with a too strong aggressive NPC.

![aggressive NPC Map](https://i.vgy.me/kpbEcW.jpg)

### `map_job_npcs.css`

Highlights locations on the map that can spawn NPCs relevant for jobs
(_Auftragshaus_), so finishing jobs becomes easier.

![Job NPC Map](https://i.vgy.me/aUFkWc.jpg)

Shown are:

- Onlo
- Blattalisk
- Bürger
- Ektofron
- t-Falter
- Kröte
- e-Kröte
- Wiesel
- Strativar
- Undaron
- Bro.-Virus
- leb. Ast

### `banner_shop_prices.css`

Shows the shops currently best for selling in the banner.

![Shop Price Banner](https://i.vgy.me/QoAOVb.jpg)

### `clan_distress_right_aligned.css`

Right-aligns the link to send a clan distress signal, so it becomes easier to
click on quickly.

![Clan Distress](https://i.vgy.me/WqPWbJ.jpg)

### `highlight_danger.css`

Highlights dangerous situations, such as aggressive NPCs or low life situations.

![Aggressive NPC](https://i.vgy.me/NH0Aov.gif)

### `highlight_ring_activation.css`

Highlights when the signet ring can be activated.

![Signet Ring Highlight](https://i.vgy.me/jR9WYr.jpg)

## User specific styles

The subfolder [user](https://github.com/Zabuzard/FreewarStyles/tree/main/user)
contains styles and modules for tailored towards specific users needs.

They can also be used by other users, but bear in mind that they might not be
tuned for your particular use cases.

### Zabuza

#### `highlight_shop_selling.css`

Highlights specific items that should not be sold accidentally to shops, as well
as items that should be sold to players instead.

Applies to multiple menus, such as when selling to shops, at the Bank, or also
at the Market Hall.

![Shop Selling Highlight](https://i.vgy.me/RgNdV5.jpg)

#### `highlight_some_status.css`

Highlights some specific status with a different color, so it becomes easier to
notice when they ran out while having multiple status effects.

![Status Highlight](https://i.vgy.me/ZvuDmX.jpg)

#### `highlight_some_fastspells.css`

Highlights some fastspell links with a different color, so they become easier to
click on.

![Fastspell highlight](https://i.vgy.me/2yGsoK.jpg)
