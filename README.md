# RaindanceMC/names

- **`names-module`** — Rain's Flexible Modules — Coloured names: A name tag crafted with a dye remembers that colour; crafted with an item it paints that item's name, and a row of them paints a gradient. The grid is read, charged and refunded by hand because none of it can be expressed as a Bukkit recipe — see CraftRule for why.
- **`names-standalone`** — Rain's Coloured Names: Rain's Coloured Names, as a plugin of its own. Nothing here but a build file and a descriptor: the names module and the standard wrapper are shaded together, and that is the whole plugin. The name and the data folder are unchanged from the standalone plugin it replaces.

Part of [RaindanceMC](https://github.com/RaindanceMC); built on [RainsCore](https://github.com/RaindanceMC/RainsCore) and the shared parent in [framework](https://github.com/RaindanceMC/framework). Split out of `rains-flexible-modules` on 16.10.2026, history kept.

## Build

```
mvn install
```

Needs Java 25 and read access to `packages.tstieh.de` (server ids `packages-releases` / `packages-snapshots` in `~/.m2/settings.xml`).

## Plugins

- `names-standalone/target/RainsColouredNames-2.4.0.jar` — also published as `de.raindancer.modules:names-standalone:2.4.0`

## Versions

A module's version is a property in this repository's root `pom.xml`, a plugin's is `plugin.version` in its own pom. CI publishes every version that is not in the registry yet on the next push to master.
