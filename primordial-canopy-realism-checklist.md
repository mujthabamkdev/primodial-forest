# Primordial Canopy realism pass

## Implemented in `primordial-canopy-photorealistic-copy.html`

- [x] Load local PBR vegetation through `GLTFLoader`.
- [x] Replace procedural vegetation when PBR asset load succeeds.
- [x] Add 2K PBR vegetation GLBs with Draco geometry compression for denser live loading.
- [x] Add varied canopy heights, understory plants, shrubs, ferns, and anthuriums.
- [x] Ground assets to terrain height instead of leaving them at world Y=0.
- [x] Increase forest density and walkable world bounds.
- [x] Add collision volumes around loaded plants and trees.
- [x] Add local forest-floor diffuse, normal, and roughness maps.
- [x] Archive candidate wolf and squirrel GLBs without showing low-poly wildlife in scene.
- [x] Remove low-poly/procedural dinosaurs and other plastic-looking wildlife from visible scene.
- [x] Keep animal visuals disabled until suitable non-plastic licensed models are available.
- [x] Add night sky stars and moon lighting.
- [x] Extend exploration bounds and populate extended world area.
- [x] Darken and reshape river/waterfall shaders for night-water response.
- [x] Improve procedural hand material and knuckle volume.
- [x] Add subtle movement to wildlife so animals do not appear as static props.
- [x] Add public-domain/CC-licensed wolf and squirrel recordings.
- [x] Make wildlife cues intermittent and movement/fear-driven.
- [x] Reduce footstep and rain volume.
- [x] Add breathing inhale/exhale pulses tied to fatigue and fear.
- [x] Remove synthetic tonal ambient calls that sounded like beeps.
- [x] Add rain streaks, rain-triggered ripples, and shallow puddle patches.
- [x] Add dense wild-forest props: webs, lianas, broken logs, shallow ponds, fallen leaves, and occasional fruit.
- [x] Make fallen leaves react to player movement.
- [x] Expand rain visibility with denser streaks and more rain impact ripples.
- [x] Add hand up/down swing during walking and stronger stride motion during running.
- [x] Add hand reach, finger curl, and plant rustle on object contact.
- [x] Add loading overlay while GLB/PBR assets load.
- [x] Add keyboard, mouse, touch, sprint, and interaction instructions to start screen.

## Still needed for true AAA/photogrammetry realism

- [ ] Replace procedural first-person hands with a licensed high-resolution rigged hand GLB.
- [ ] Replace procedural cliffs/river with licensed sculpted and textured GLB assets.
- [ ] Add HDRI/environment lighting and reflection probes.
- [ ] Add contact-shadow or GTAO pass for roots, feet, plants, and puddles.
- [ ] Add temporal anti-aliasing and subtle depth of field.
- [ ] Add high-resolution wind animation or vertex-cache animation for imported plants.
- [ ] Add spatial audio / HRTF positioning for wildlife and rain.
- [ ] Add real terrain collision and slope-aware locomotion.
- [ ] Add asset LODs and instancing before increasing density further.
