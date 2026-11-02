# CHOME
CHOME is a multi-game entertainment platform bringing together exciting games in one place. Players can enjoy racing, adventure, sports, puzzles, action and many more games. Built for fun, competition, high scores and an amazing gaming experience across mobile and desktop devices. One platform. Many games. Endless fun.


## Skybound — Island One

The current Skybound build is the first playable technical foundation for CHOME's third-person adventure direction.

### Current implementation
- Three.js WebGL rendering with mobile-aware pixel ratio and responsive layout.
- Third-person human character loaded as a skinned GLB model.
- AnimationMixer integration for imported character animation clips.
- Follow camera, keyboard movement, touch controls, jump, pause/resume.
- Procedural floating-island environment, vegetation, rock formations, ruins, collectible light shards, clouds, fog, lighting and shadows.
- Loading state and explicit asset-load error reporting.

### Character asset and attribution
The current human model is **Cesium Man**, from the Khronos glTF Sample Assets collection. It is a temporary integration/reference character for validating the rigged-model and animation pipeline, not the final CHOME hero design. The model is licensed CC BY 4.0; credit: © 2017 Cesium. License: https://creativecommons.org/licenses/by/4.0/

### Production roadmap
1. Replace the reference character with an original CHOME human hero model, including a detailed face, hair, clothing, facial expressions and a production-ready humanoid rig.
2. Add a complete animation set: idle, walk, run, sprint, jump, fall, land, climb, dodge, attacks and interactions.
3. Build authored island zones, terrain, structures, props, materials, foliage and environmental storytelling.
4. Add combat, abilities, quests, checkpoints, save data, sound design, effects and polished UI.
5. Profile and optimize on real Android phones and desktop browsers.

**Production note:** this is an active prototype, not a finished commercial game. The final hero model, authored art assets, full animation set, gameplay systems and device testing remain production work.
