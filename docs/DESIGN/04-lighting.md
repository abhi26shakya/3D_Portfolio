# Lighting System

# BOOK III — DESIGN

## Purpose
Lighting defines the emotional tone of the portfolio. It should evolve continuously with the visitor's journey while maintaining realism, readability and performance.

## LIGHT-001 Goals
- Cinematic realism
- Strong readability
- Smooth day-to-night transition
- Consistent mood
- Performance-friendly implementation

## Time of Day Sequence
1. Sunrise
2. Morning
3. Noon
4. Golden Hour
5. Sunset
6. Blue Hour
7. Night

## LIGHT-002 Sun
- Warm directional light.
- Soft shadows.
- Cascaded shadow maps.

## LIGHT-003 Moon
- Cool blue fill light.
- Lower intensity than sunlight.

## LIGHT-004 Lanterns
- Warm amber point lights.
- Visible bloom.
- Guide visitors through important locations.

## LIGHT-005 Environment
- Volumetric fog.
- HDR sky.
- Screen-space ambient occlusion.
- Gentle bloom only.

## LIGHT-006 Day/Night Toggle
The visitor may switch between Day and Night at any time. Lighting, skybox, UI accents and reflections should update smoothly without reloading the scene.

## Performance Budget
- Stable 60 FPS desktop.
- Adaptive quality for lower-end devices.

## Acceptance Criteria
Lighting should reinforce the story, preserve readability of portfolio content and make the environment feel alive throughout the entire journey.