# Primordial Canopy asset credits

Photorealistic copy uses locally cached assets so browser loading does not depend on third-party CORS headers.

## CC0 Poly Haven vegetation

- `assets/models/polyhaven/island_tree_01/` — Island Tree 01
- `assets/models/polyhaven/pachira_aquatica_01/` — Pachira Aquatica 01
- `assets/models/polyhaven/fern_02/` — Fern 02
- `assets/models/polyhaven/shrub_02/` — Shrub 02
- `assets/models/polyhaven/anthurium_botany_01/` — Anthurium Botany 01

Source: https://polyhaven.com/ — CC0. Poly Haven attribution is included as courtesy.

The copy loads Draco-compressed 2K GLB conversions from `assets/models/realistic/`; original source packages remain under `assets/models/polyhaven2k/`.

- `assets/materials/forest_floor/` — Forest Floor PBR material
  - Source: https://polyhaven.com/a/forest_floor
  - License: CC0

## Wildlife GLB files

- `assets/models/wildlife/wolf.glb` — Quaternius Wolf, Poly Pizza
  - Source: https://poly.pizza/m/P1gU3Qkr9r
  - License: CC0
- `assets/models/wildlife/squirrel.glb` — Poly by Google Squirrel, Poly Pizza
  - Source: https://poly.pizza/m/caxos24uWC9
  - License: CC BY 3.0, Poly by Google

The wolf and squirrel files are lightweight browser-ready GLBs. They are useful as wildlife silhouettes and animation hooks, but are not photogrammetry-grade assets. Replacing them with high-resolution licensed scans would be a separate asset upgrade.

Current build does **not** bundle or load low-poly wildlife GLBs. They were intentionally excluded until higher-quality licensed animal models are supplied.

## Wildlife recordings

- `assets/audio/wolf-howls.ogg` — “Wolf howls”, Wikimedia Commons, public domain
  - Source: https://commons.wikimedia.org/wiki/File:Wolf_howls.ogg
- `assets/audio/jungle-palm-squirrel-sound.wav` — “Jungle palm squirrel's sound”, Ganesh Mohan T, CC BY-SA 4.0
  - Source: https://commons.wikimedia.org/wiki/File:Jungle_palm_squirrel%27s_sound.wav
