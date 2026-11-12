Sculkwire gives your AI agent the Bedrock docs, a validator, a test server and the real game. The agent can write a Minecraft: Bedrock Edition add-on, check it, run it and watch it work.

## What the Agent Gets

- **Knowledge.** Docs, Script API, components, commands, Molang, vanilla examples and changelogs, for stable and preview.
- **Validation.** Each problem in a pack, with its file, line and rule.
- **Test server.** Your packs and GameTests on a Bedrock Dedicated Server.
- **Live game.** The real game in a test world with your packs: reload after edits, read the log, take screenshots. Works on Windows and Linux.
- **Player control.** Walk, find paths, fight mobs, craft, smelt, trade and work toward goals like a player.

The [tool reference](https://github.com/Sculkwire/sculkwire/blob/main/docs/tools.md) explains every tool.

## Install

You need Node.js 22.18 or newer and git. Paste this into your AI agent harness:

```text
Install the sculkwire MCP server: clone https://github.com/Sculkwire/sculkwire.git and follow the "Agent Install" steps in its docs/install.md.
```

Or install in one line. Linux and macOS:

```sh
curl -fsSL https://raw.githubusercontent.com/Sculkwire/sculkwire/main/install.sh | sh
```

Windows (Windows PowerShell 5.1 or PowerShell 7):

```powershell
irm https://raw.githubusercontent.com/Sculkwire/sculkwire/main/install.ps1 | iex
```

Both give you a `sculk` command and register sculkwire with your MCP client. `sculk doctor` lists each problem on your machine with a fix.

## Repositories

| Repository | What it is |
|---|---|
| [sculkwire](https://github.com/Sculkwire/sculkwire) | The MCP server, the `sculk` CLI and the optional in-game agent. MIT licence. |

## Links

- [Quick Start](https://github.com/Sculkwire/sculkwire#quick-start)
- [Game Client Setup](https://github.com/Sculkwire/sculkwire/blob/main/docs/client.md)
- [Extensions](https://github.com/Sculkwire/sculkwire/blob/main/docs/extensions.md)
- [Contributing](https://github.com/Sculkwire/sculkwire/blob/main/CONTRIBUTING.md)
- [Releases](https://github.com/Sculkwire/sculkwire/releases) and [Changelog](https://github.com/Sculkwire/sculkwire/blob/main/CHANGELOG.md)

<sub>NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.</sub>
