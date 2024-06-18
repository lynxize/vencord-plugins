
> [!WARNING]
> I'm not a frontend dev (or even a JS/TS dev for that matter), and have no idea what I'm doing.
> Don't expect great code quality.

Some random unofficial plugins for [Vencord](https://github.com/Vendicated/Vencord/).

See `src/userplugins` for the plugins themselves; the rest of this repo is just Vencord with some very minor tweaks.

Installation instructions can be found [here](https://github.com/Vendicated/Vencord/blob/main/docs/1_INSTALLING.md) and [here](https://github.com/Vendicated/Vencord/blob/main/docs/2_PLUGINS.md). (Put the desired plugins in the `src/userplugins/` folder of your own Vencord install)

> [!NOTE]
> I don't recommend cloning Vencord from this repo, as I probably won't keep it super up to date

## Plugins

### pk4v

[PluralKit](https://pluralkit.me/) integration, inspired by [PluralChum](https://github.com/estroBiologist/pluralchum) and [this earlier Vencord plugin](https://github.com/Vendicated/Vencord/pull/2536/).

- Adds edit and delete buttons to proxied messages
- Optionally allows coloring of member names in chat by either member color, system color, or highest account role color
- Replaces the annoying`APP` (formerly `BOT`) tag with `PK`

(see [the plugin itself](src/userplugins/pk4v/index.tsx) for known issues and more information)

### More soon?


*All plugins are licensed under GPLv3 to match Vencord itself.*
