# z-navi-cheats

`navi` cheat collection for advanced Linux ops and automation workflows.

## Files

- `xargs.cheat`
- `awk.cheat`
- `inotifywait.cheat`
- `docker.cheat`
- `perf.cheat`

## Quick Start

1. Install `navi`.
2. Add this directory to your cheats path:

```bash
navi repo add https://github.com/baibaidashixiong/z-navi-cheats
```

3. Start using:

```bash
navi --print
```

## Cheat File Rules

Each `.cheat` file should follow these conventions:

1. First line must be tags:
   `% tag1, tag2`
2. Every command must have an English description line above it:
   `# Description`
3. Use placeholders for complex inputs:
   `<variable>`
4. Add variable completion at the bottom:
   `$ variable: command`

## Add a New Cheat File

1. Create a new file, e.g. `mytool.cheat`.
2. Add tags on the first line.
3. Add high-value commands with one-line English descriptions.
4. Use variables for parameters users usually change.
5. Add completion providers for every variable used in commands.
6. Validate format and test interactively in `navi`.
