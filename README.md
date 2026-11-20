# CTF-Solver

> **This repository has moved.** The agent definitions that started here now live in
> **[VSCODE_Agents](https://github.com/UniquePratham/VSCODE_Agents)** — a library of 77
> GitHub Copilot agent definitions covering every CTF category plus full-lifecycle
> engineering domains.

## Why the move

This repo began as a single CTF-solving agent. It grew into a general agent library, so
the name no longer described the contents. `VSCODE_Agents` is the maintained home.

## What is in VSCODE_Agents

| Group | Count | Covers |
|---|---|---|
| CTF agents | 15 | web, pwn, rev, crypto, forensics, osint, misc, mobile, hardware, cloud, blockchain, database, games, AD, ops |
| Domain agents | 61 | backend, frontend, security, data, mobile, infra, design, and more |
| Shared ledger | 1 | cross-agent technique notes |

## Use it

```bash
git clone https://github.com/UniquePratham/VSCODE_Agents
cp VSCODE_Agents/agents/ctf-web.agent.md ~/.copilot/agents/
```

Then pick the agent by name in the VS Code Copilot Chat agent picker.

## License

MIT — see [LICENSE](LICENSE).