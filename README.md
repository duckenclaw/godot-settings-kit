# Settings Kit (`settings_kit`)

Settings persistence (graphics/audio/gameplay/controller/locale) plus key & gamepad rebinding, with a reusable rebind-row UI.

Part of the **[godot-game-kit](https://github.com/duckenclaw/godot-game-kit)** modular
template ecosystem — a set of reusable Godot 4 addons shared across FPS,
third-person, 2D sidescroller and top-down game templates.

## Install

**Git submodule (recommended)** — this repo is root-layout, so it drops straight
into a project's `addons/`:

```bash
git submodule add https://github.com/duckenclaw/godot-settings-kit addons/settings_kit
git submodule update --init
```

Then enable **Settings Kit** in *Project → Project Settings → Plugins*.

**Godot Asset Library** — an Asset-Library-compatible release (files wrapped under
`addons/settings_kit/`) is published per tagged version; search for "Settings Kit" in the
editor's AssetLib tab.

## Dependencies

none (localization pairs with Game Core)

## Versioning

Semantic versioning via git tags (`v1.0.0`). The Asset Library entry tracks tags.

## License

MIT — see [LICENSE](LICENSE).
