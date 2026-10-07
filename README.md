# shii

Roblox project synced into Roblox Studio with [Rojo](https://rojo.space).

## Setup (once)

1. Install [Rokit](https://github.com/rojo-rbx/rokit), then run `rokit install` in this folder to get Rojo.
2. In Roblox Studio, install the Rojo plugin: run `rojo plugin install`, or get it from the Creator Store.
3. Optional: install the Rojo extension for VS Code.

## Syncing to Studio

1. `git pull` to get the latest code.
2. Run `rojo serve` in this folder.
3. In Studio, open the **Rojo** plugin and click **Connect**.

Edits to files under `src/` now show up in Studio live.

## Layout

| Folder        | Ends up in Studio at                            |
|---------------|-------------------------------------------------|
| `src/shared`  | `ReplicatedStorage.Shared`                      |
| `src/server`  | `ServerScriptService.Server`                    |
| `src/client`  | `StarterPlayer.StarterPlayerScripts.Client`     |

Build a place file without Studio: `rojo build -o shii.rbxl`
