# Redoubt settings

The privacy configuration for [Redoubt](https://github.com/CPlusPlus17/Redoubt),
a privacy-hardened Android browser built from Firefox's source and LibreWolf's
privacy configuration. This repository is used as the `settings/` submodule of
the Redoubt repository.

**This is LibreWolf's work.** It is a fork of
[LibreWolf's settings](https://librewolf.dev/librewolf/settings), split into
fragments shared by desktop and Android:

| file | what |
|---|---|
| `common.cfg` | preferences shared by desktop and Android |
| `desktop.cfg` | desktop-only preferences (upstream LibreWolf) |
| `android.cfg` | Android-only preferences and locks for Redoubt |
| `librewolf.cfg` | generated: `common.cfg` + `desktop.cfg`, the file the desktop build ships (the name is an inherited code identifier, not branding) |
| `distribution/policies.json` | enterprise policies (desktop) |

Redoubt is **not affiliated with or endorsed by the LibreWolf project**, and
nothing here is supported by LibreWolf. Please report problems with these
settings in Redoubt to the
[Redoubt issue tracker](https://github.com/CPlusPlus17/Redoubt/issues), not to
LibreWolf. For LibreWolf itself, see [librewolf.net](https://librewolf.net).

LibreWolf's settings credit the research of [arkenfox](https://github.com/arkenfox)
and the work of the Firefox team; that credit carries over here.

Licence: [MPL-2.0](LICENSE.txt).
