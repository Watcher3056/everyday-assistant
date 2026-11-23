# Everyday Assistant

A reusable skill for research, comparisons, errands, forms, documents, PC
troubleshooting and everyday questions. Its source is in
`skills/everyday-assistant/`. It has its own repository, marketplace, package
and release boundary.

It builds and installs independently of Unity-dev and Graph. Install the
standalone FlowAI Graph tool separately if your workflow needs a live graph;
this skill's package does not bundle or require it.

Example in Codex: `$everyday-assistant compare these options`.
In Claude Code: `/everyday-assistant:everyday-assistant compare these options`.

## Install

```sh
git clone https://github.com/Watcher3056/everyday-assistant.git
cd everyday-assistant
python -m pip install -r requirements-dev.txt
python tools/build_plugin.py --install
```

For Claude Code, use `python tools/build_plugin.py --host claude --install`
instead. Start a new client session after installation.

To apply the general rules in every conversation, not only when the skill
loads, copy `skills/everyday-assistant/references/core.md` into your host's
always-on instructions: `~/.claude/CLAUDE.md` or `~/.codex/AGENTS.md`.

[Build/install/update/removal and data](docs/usage.md) · [MIT](LICENSE)

Private cases, personal data, research records and agent authoring instructions
are excluded from the [public source repository](https://github.com/Watcher3056/everyday-assistant).
