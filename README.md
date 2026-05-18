# w_karabiner

Workspace combining Karabiner-Elements rule configs and a Next.js SVG visualizer for them.

## Submodules

| Path | Repo | Purpose |
| --- | --- | --- |
| `karabiner/` | [suenot/karabiner](https://github.com/suenot/karabiner) | Karabiner-Elements `complex_modifications` rule JSONs |
| `karabiner-visualizer/` | [suenot/karabiner-visualizer](https://github.com/suenot/karabiner-visualizer) | Next.js frontend that renders those rules as interactive SVG keyboards |

## Clone

```bash
git clone --recurse-submodules <this-repo>
# or, after a plain clone:
git submodule update --init --recursive
```

## Update submodules

```bash
git submodule update --remote --merge
```

## Run the visualizer

```bash
cd karabiner-visualizer
npm install
npm run dev
```
