# LeanC2

This repository is a Lean 4/Lake project.

## Build CLI

Use the small wrapper script at the repository root for local build tasks:

```sh
./leanc2          # same as: ./leanc2 build
./leanc2 check    # build the root Lean target
./leanc2 clean
./leanc2 --help
```

The script uses `lake` from your `PATH`, falls back to `~/.elan/bin/lake`, and can be pointed at a specific executable with `LAKE=/path/to/lake ./leanc2`.
