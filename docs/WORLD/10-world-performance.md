# World Performance

# BOOK IV — WORLD

## Purpose
Define the performance strategy required to deliver a cinematic 3D portfolio while maintaining a smooth user experience across a range of devices.

## PERF-001 Targets
- Desktop: 60 FPS target.
- Mid-range laptops: 45–60 FPS.
- Graceful degradation on lower-end hardware.

## PERF-002 Rendering
- Use Level of Detail (LOD).
- GPU instancing for repeated assets.
- Frustum culling.
- Lazy-load distant models.

## PERF-003 Assets
- Compress textures.
- Reuse materials.
- Stream HDRIs only when needed.
- Optimize GLTF assets.

## PERF-004 Adaptive Quality
- Automatic quality presets.
- Reduce shadows and particles on slower devices.
- Limit active NPCs dynamically.

## PERF-005 Monitoring
- Measure frame time.
- Track GPU memory.
- Log loading durations.
- Test on desktop, tablet and mobile.

## Acceptance Criteria
The portfolio should remain responsive, visually impressive and stable while preserving the cinematic experience on supported devices.