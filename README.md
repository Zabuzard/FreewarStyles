# FreewarStyles

CSS Style-Module für das MMORPG [Freewar.de](https://www.freewar.de).

Über Github Pages gehosted:
[zabuzard.github.io/FreewarStyles](https://zabuzard.github.io/FreewarStyles/).
Den Source Code gibts bei
[GitHub: Zabuzard/FreewarStyles](https://github.com/Zabuzard/FreewarStyles).

Um ein Modul zu nutzen, füge eine `import`-Zeile in deinen Benutzerdefinierten
Style ein, zum Beispiel:

```css
@import url("https://zabuzard.github.io/FreewarStyles/modules/dark/chat_colors.css");

@import url("https://zabuzard.github.io/FreewarStyles/modules/borderless_inventory.css");
@import url("https://zabuzard.github.io/FreewarStyles/modules/compact_inventory.css");
```

![Beispiel in UI](https://i.vgy.me/5XSbAI.jpg)

## Module

Module können im Verzeichnis
[modules](https://github.com/Zabuzard/FreewarStyles/tree/main/modules) gefunden
werden, und sind üblicherweise mit Hellen und Dunklen Styles kompatibel. Die
Module, welche Style-spezifisch sind, können im Unterverzeichnis `modules/light`
und `modules/dark` gefunden werden.

### `dark/chat_colors.css`

Definiert Chat und Button Farben, welche für Dunkle Styles geeignet sind.

![Dark Chat Colors](https://i.vgy.me/D5hdJA.jpg)

### `borderless_inventory.css`

Entfernt Ränder im Charakter-Menü und Inventar.

![Borderless inventory](https://i.vgy.me/wSKylg.jpg)

### `compact_inventory.css`

Macht das Inventar kompakter. Insbesondere indem Items jeweils nur eine, statt
zwei Zeilen haben, wodurch die Aktionen in der gleichen Zeile sind.

![Compact Inventory](https://i.vgy.me/mgJAhC.jpg)

Kombiniere zusätzlich mit dem Modul `borderless_inventory.css` für einen sehr
kompakten Look:

![Very compact](https://i.vgy.me/S5mZ6E.jpg)

### `weapon_durability.css`

Zeigt die Waffenhaltbarkeit direkt im Menü an, so dass ein Mouse-Hover nicht
mehr benötigt ist.

![Weapon Durability](https://i.vgy.me/1M7GsF.jpg)

### `dark/compact_status.css` or `light/compact_status.css`

Kürzt Status-Effekt Beschreibungen im Menü stark ab und zeigt die verbleibende
Zeit direkt im Menü an, so dass ein Mouse-Hover nicht mehr benötigt ist.
Mouse-Hover kann genutzt werden um die Abkürzung ausgeschrieben zu sehen.

![Compact Status](https://i.vgy.me/F67aUB.jpg)

### `bigger_fast_spell_menu.css`

Vergrößert die Schriftgröße im Schnellzauber Menü, so dass Schnellzauber
einfacher anzuklicken sind. Insbesondere nützlich für 4k Auflösungen.

![Bigger Fast Spell Menu](https://i.vgy.me/4gChpd.jpg)

### `job_hints.css`

Zeigt Kurzbeschreibungen für alle Aufträge (Auftragshalle) direkt im Inventar
an, so dass es nicht mehr nötig ist sich die volle Beschreibung eines Auftrags
durchzulesen.

![Job Hints](https://i.vgy.me/0yV2uz.jpg)

### `map_secure_locations.css`

Hebt alle sicheren Felder direkt auf der Karte hervor. Auf diesen Feldern können
Spieler keine anderen Spieler angreifen.

![Secure Locations Map](https://i.vgy.me/nNykbZ.jpg)

### `map_teleportation_blue.css`

Zeigt einen blauen Kreis auf Feldern an, welche mit einer gepressten Zauberkugel
(oder Ähnlichem) erreicht werden können.

![Blue Teleportation Map](https://i.vgy.me/ERt3Kb.jpg)

### `map_teleportation_yellow.css`

Zeigt einen gelben Kreis auf Feldern an, welche mit einer geklebte, gelbe
Zauberkugel (oder Ähnlichem) erreicht werden können.

![Yellow Teleportation Map](https://i.vgy.me/t1j4qX.jpg)

### `map_teleportation_portal.css`

Zeigt eine orangene Raute auf Feldern an, welche mit der Portalmaschine erreicht
werden können.

![Portal Teleportation Map](https://i.vgy.me/74NBCJ.jpg)

### `map_teleportation_ring_sandwind.css`

Zeigt eine violette Raute auf Feldern an, welche mit einem Ring des Sandwindes
(Taruner) erreicht werden können.

![Ring Sandwind Teleportation Map](https://i.vgy.me/iN6xIz.jpg)

### `map_teleportation_onlo.css`

Zeigt ein grünes Quadrat auf Feldern an, welche von Onlos erreicht werden
können, welche mit Lianen durch den Wald schwingen.

![Onlo Teleportation Map](https://i.vgy.me/y2UbcK.jpg)

### `map_shops.css`

Zeigt ein Haus-Symbol auf Feldern an, welche einen Shop zum Verkaufen von Items
haben.

- blaue Farbe für einen Shop der blauen Fraktion
- rote Farbe für einen Shop der roten Fraktion
- orangene Farbe für einen neutralen Shop
- violette Farbe für einen Shop der Natla

| Blau                                      | Rot                                      | Neutral                                      | Natla                                      |
| ----------------------------------------- | ---------------------------------------- | -------------------------------------------- | ------------------------------------------ |
| ![Blue Shop](https://i.vgy.me/wyfoI5.jpg) | ![Red Shop](https://i.vgy.me/EkeThX.jpg) | ![Neutral Shop](https://i.vgy.me/HWde3c.jpg) | ![Natla Shop](https://i.vgy.me/wUraLl.jpg) |

### `map_dungeon_entrances.css`

Zeigt ein Pfeil-Symbol auf Feldern an, welche einen Eingang oder Ausgang eines
Dungeons haben.

![Dungeon Icons](https://i.vgy.me/rbe44U.jpg)

### `map_aggressive_npcs.css`

Hebt Felder auf der Karte hervor, welche ein aggressives NPC haben. Angezeigt
werden die Angriffsstärken der NPCs. Dadurch wird verhindert, dass man
ausversehen ein Feld mit zu starken aggressiven NPCs betritt.

![aggressive NPC Map](https://i.vgy.me/kpbEcW.jpg)

### `map_job_npcs.css`

Hebt Felder auf der Karte hervor, auf denen Auftrags-NPCs spawnen können; so wie
andere Felder, welche für Aufträge relevant sind.

![Job NPC Map](https://i.vgy.me/aUFkWc.jpg)

Angezeigt werden:

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
- Ratte

### `banner_shop_prices.css`

Zeigt die aktuell besten Shops für den Verkauf von Items direkt im Banner an.

![Shop Price Banner](https://i.vgy.me/QoAOVb.jpg)

### `banner_rotating_quests_dungeons.css`

Zeigt Daten zu rotierenden Quests und Dungeons direkt im Banner an.

![Rotating Banner](https://i.vgy.me/vKPoH7.jpg)

### `clan_distress_right_aligned.css`

Zeigt den Link zum Clannotruf rechts- statt linksbündig im Menü an, so dass er
einfacher schnell anzuklicken ist.

![Clan Distress](https://i.vgy.me/WqPWbJ.jpg)

### `highlight_danger.css`

Hebt gefährliche Situationen vor, zum Beispiel aggressive NPCs oder bei
niedrigen Lebenspunkten.

![Aggressive NPC](https://i.vgy.me/NH0Aov.gif)

### `highlight_ring_activation.css`

Hebt hervor wenn ein angelegter Siegelring wieder benutzt werden kann.

![Signet Ring Highlight](https://i.vgy.me/jR9WYr.jpg)

### `highlight_job_links.css`

Hebt die Links zum Annehmen und Beenden eines Auftrags beim Haus der Aufträge
hervor.

![Job link highlights](https://i.vgy.me/FhmiPb.jpg)

### `settings_help.css`

Zeigt ✅- und ❌- Symbole im Einstellungs-Menü an, so dass es einfacher ist zu
verstehen welche Einstellung aktuell aktiviert oder deaktiviert ist.

![Settings Menu](https://i.vgy.me/GiTVOR.jpg)

## Nutzer definierte Styles

Das Unterverzeichnis
[user](https://github.com/Zabuzard/FreewarStyles/tree/main/user) enthält Styles
und Module, welche speziell auf die Bedürfnisse bestimmter Nutzer angepasst
sind.

Sie können auch von anderen Nutzern benutzt werden, aber möglicherweise
entsprechend sie dann nicht genau den eigenen Wünschen.

### Zabuza

#### `highlight_shop_selling.css`

Hebt bestimmte Items farblich hervor, welche zum Beispiel nicht ausversehen an
einen Shop verkauft werden sollten, oder stattdessen an andere Spieler verkauft
werden sollten.

Betrifft verschiedene Menüs, zum Beispiel beim Verkauf in Shops, an der Bank,
oder auch an der Markthalle.

![Shop Selling Highlight](https://i.vgy.me/RgNdV5.jpg)

#### `highlight_some_status.css`

Hebt bestimmte Statuse im Inventar mit einer anderen Farbe hervor, so dass es
einfacher ist zu bemerken, wenn sie auslaufen.

![Status Highlight](https://i.vgy.me/ZvuDmX.jpg)

#### `highlight_some_fastspells.css`

Hebt bestimmte Schnellzauberlinks mit einer anderen Farbe hervor, so dass sie
einfacher anzuklicken sind.

![Fastspell highlight](https://i.vgy.me/2yGsoK.jpg)

#### `highlight_some_teleportation_destinations.css`

Hebt bestimmte Ziele in Teleportations-Menüs hervor.

![Teleport highlight](https://i.vgy.me/6ZqiPi.jpg)

#### `highlight_finstereishöhle_symbols.css`

Hebt die Links zum Aktivieren der Symbole in der Finstereishöhle hervor.
