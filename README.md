# Primordial Canopy

Interactive first-person rainforest experience built with Three.js.

Current copy focuses on a dark, rainy, densely packed wild forest: PBR vegetation, night sky, moon lighting, terrain-aware movement, visible rain, shallow ponds, spider webs, natural lianas, fallen logs, moving leaves, occasional fruit, river/waterfall shaders, subtle breathing, wildlife audio, object contact, and expanded exploration bounds.

## Run locally

GLB, audio, and texture loading require HTTP. Do not open `index.html` directly with `file://`.

```bash
python3 -m http.server 4173
```

Open:

```text
http://127.0.0.1:4173/index.html
```

## Controls

- `WASD` / arrow keys: move
- Mouse drag / right touch: look
- `Shift`: run
- Touch/click near vegetation: reach and rustle object
- `RUN` button: toggle sprint on touch devices

## Included assets

- Draco-compressed 2K Poly Haven vegetation GLBs
- Forest-floor diffuse, normal, and roughness maps
- Public-domain wolf howl recording
- CC BY-SA jungle palm squirrel recording
- Local asset credits in `primordial-canopy-assets-CREDITS.md`

## Visual systems

- Dense imported canopy and understory placement across expanded world bounds
- Instanced 20x density layer for larger plants, medium plants, and rooted ground cover
- Distance culling for imported vegetation
- Terrain-height grounding and plant collision volumes
- Deep blue night fog, stars, moon, and cool moonlight
- Rain streaks, shallow puddles, and surface ripples
- Spider webs between plants, natural lianas, broken wood, shallow ponds, fallen leaves, and sparse fruit
- Darker river flow and waterfall foam/mist shaders
- Physical skin material, knuckle volume, walk/run hand swing
- Fear response, movement resistance, and subtle camera instability

## Animal policy

Low-poly animal GLBs were intentionally removed from visible scene because they looked artificial. Current build uses wildlife recordings only. High-quality photogrammetry animal models require licensed assets or user-supplied GLBs; do not substitute low-quality models.

## Known limitations

- Page loads roughly 150 MB of local vegetation GLBs and textures.
- Draco decoder is loaded from Three.js CDN.
- Hands remain procedural rather than scan-based.
- River and waterfall are shader-built, not scanned fluid simulation.
- Realistic animal models are not bundled until suitable licensed assets are approved.

## Project notes

See `primordial-canopy-realism-checklist.md` for implemented and remaining realism work.
