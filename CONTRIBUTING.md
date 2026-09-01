# Contributing to Cobbleworks

Contributions are welcome in the repository that owns the plugin or documentation you want to change.

## Before opening a change

1. Search the repository's open issues and pull requests for related work.
2. Open an issue first when a change affects configuration compatibility, stored data, permissions, or established gameplay behavior.
3. Keep one pull request focused on one plugin and one clear outcome.

## Development checks

Cobbleworks plugins are Maven projects. Use the Java version documented in the repository and run:

```bash
mvn clean verify
```

Do not commit `target/`, IDE metadata, server worlds, generated plugin data, API keys, or credentials. Add tests for behavior that can be exercised without a live Minecraft server, and describe any manual server checks in the pull request.

## Commit and pull request notes

Write a short, concrete summary of the player-visible or administrator-visible change. Prefixes such as `feat:`, `fix:`, `perf:`, and `refactor:` help the automatic release workflow group changes into useful release-note sections.

Pull requests should state:

- What changed and why
- Which Minecraft and server versions were checked
- Which commands, permissions, configuration keys, or dependencies changed
- How the change was tested

By contributing, you agree that your work may be distributed under the license of the target repository.
