# Satsu

Roblox game synced into Studio with [Rojo](https://rojo.space).

## Setup

1. Install [Rokit](https://github.com/rojo-rbx/rokit), then run `rokit install` in this folder (installs the Rojo version pinned in `rokit.toml`).
2. Install the Rojo plugin in Studio: `rojo plugin install`.

## Syncing

1. `rojo serve`
2. In Studio, open the **Rojo** plugin and click **Connect**.

Edits under `src/` now sync live into Studio:

| Folder        | Studio location                          |
| ------------- | ---------------------------------------- |
| `src/shared`  | `ReplicatedStorage.Shared`               |
| `src/server`  | `ServerScriptService.Server`             |
| `src/client`  | `StarterPlayer.StarterPlayerScripts.Client` |

To build a place file instead: `rojo build -o Satsu.rbxl`.
