# Magic Cast VFX Lite (Godot 4)

A free, fully working sample from the **Magic Cast VFX** pack: one multi-layered
arcane **rune-circle** cast effect, complete with source. Open this project and
press **Play**, or copy `addons/magic_cast_vfx_lite/` into your own project and
drag `scenes/cast_rune_circle.tscn` into a scene. It plays in the editor and in
game. No autoloads, no dependencies.

This is the exact system the full pack uses: a smoke volume, the hero shape, a
cast ring, sparks and a light, all HDR-tuned for glow. Three colours in the
preset turn the arcane circle into fire, frost or gold.

## Install
Copy `addons/magic_cast_vfx_lite/` into your project's `res://addons/`. Enabling
the plugin under Project → Plugins is optional. The effect works either way.

## Requirements
- Godot 4.x (built and tested on 4.7), Forward Plus recommended
- Glow enabled in your `WorldEnvironment` (glow_hdr_threshold ≈ 1.5, ACES
  tonemap). Copy the environment from `demo/dragdrop_example.tscn`.

## Docs
- [Quick start](docs/quick-start.md)
- [Upgrading to the full pack](docs/upgrade.md)

## Upgrade
The full **Magic Cast VFX** pack adds five more effects: arcane nova, frost
bloom, holy flash, poison puff and heal halo, plus 10 reusable shape textures,
on the same store account.

## License
MIT, see [LICENSE](LICENSE). Use in unlimited personal and commercial projects.


## Part of a family

This is one free tier from the selodev catalog of no-code Godot 4 systems. They share an item contract and a save contract, so they plug into each other, and each one also works fully on its own.

Free systems:

- [Inventory Lite](https://github.com/seloc0des/godot-inventory-lite)
- [Equipment Lite](https://github.com/seloc0des/godot-equipment-lite)
- [Loot Lite](https://github.com/seloc0des/godot-loot-lite)
- [Crafting Lite](https://github.com/seloc0des/godot-crafting-lite)
- [Vendor Lite](https://github.com/seloc0des/godot-vendor-lite)
- [Quests Lite](https://github.com/seloc0des/godot-quests-lite)
- [Stats / Skills Lite](https://github.com/seloc0des/godot-stats-skills-lite)
- [Save / Load Lite](https://github.com/seloc0des/godot-save-load-lite)
- [Dialogue Lite](https://github.com/seloc0des/godot-dialogue-lite)
- [Combat Lite](https://github.com/seloc0des/godot-combat-lite)
- [Controller Lite](https://github.com/seloc0des/godot-controller-lite)
- [Enemy AI Lite](https://github.com/seloc0des/godot-enemy-ai-lite)
- [Scene Flow Lite](https://github.com/seloc0des/godot-scene-flow-lite)
- [Audio Lite](https://github.com/seloc0des/godot-audio-lite)
- [Level Builder Lite](https://github.com/seloc0des/godot-level-builder-lite)
- [Weather System Lite](https://github.com/seloc0des/godot-weather-lite)
- [Settings + Menus](https://github.com/seloc0des/godot-settings-menus) (complete and free, no paid tier)

Free VFX: [Magic Cast](https://github.com/seloc0des/godot-magic-cast-vfx-lite), [Elemental Impact](https://github.com/seloc0des/godot-elemental-impact-vfx-lite), [Explosion](https://github.com/seloc0des/godot-explosion-vfx-lite), [Pickup, Buff & Heal](https://github.com/seloc0des/godot-pickup-buff-vfx-lite).

Free starter projects: [Free Starter](https://github.com/seloc0des/free-starter-godot), [Dungeon](https://github.com/seloc0des/godot-dungeon-starter), [Survival](https://github.com/seloc0des/godot-survival-starter), [RPG](https://github.com/seloc0des/godot-rpg-starter).

The [full versions](https://selodev.itch.io/magic-cast-vfx-spell-effects-for-godot-4) add drop-in UI, editor docks and the cross-system wiring. They're on itch.io: **https://selodev.itch.io**
