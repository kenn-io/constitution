# Clanker Constitution

The Clanker Constitution defines concise default operating principles for
coding agents. Direct user instructions and more specific repository
instructions override it.

The current release is
[`v2026.08.10`](https://github.com/kenn-io/constitution/releases/tag/v2026.08.10).

## Use it globally

Keep a persistent checkout of this repository on trusted `main`. Link
`CONSTITUTION.md` to `~/.codex/AGENTS.md` and to
`~/.claude/rules/clanker-constitution.md`. Preserve existing destinations;
merge the principles manually if either destination already exists.

## Use it in a repository

Copy `CONSTITUTION.md` from a reviewed release tag to the repository root.
Have the root `AGENTS.md` tell agents to read and follow it, and have the root
`CLAUDE.md` import it with `@CONSTITUTION.md`. Keep downstream copies pinned;
update them through normal pull-request review instead of fetching at agent
startup.

An unchanged mirror must retain the provenance and attribution notices. A
modified copy must retain attribution, identify its changes, and must not
present itself as an exact canonical version.

## Versioning

Releases use calendar tags such as `v2026.08.10`. A second release on the same
date appends a numeric component, such as `v2026.08.10.1`. Tags are immutable.

## License

Clanker Constitution © 2026 Kenn Software LLC. Licensed under
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).
