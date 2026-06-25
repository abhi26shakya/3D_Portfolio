# System Architecture

# BOOK V — ENGINEERING

## Purpose
Define the high-level architecture for the 3D portfolio. The system should be modular, scalable and maintainable while delivering a cinematic experience.

## ARCH-001 Core Stack
- Next.js 15
- React 19
- TypeScript
- React Three Fiber
- Drei
- Tailwind CSS
- GSAP
- Framer Motion
- Zustand
- React Postprocessing

## ARCH-002 Layers
1. Presentation Layer (UI)
2. Experience Layer (3D World)
3. State Layer
4. Content Layer
5. Asset Layer
6. Infrastructure Layer

## ARCH-003 Principles
- Separation of concerns.
- Reusable components.
- Lazy-loaded assets.
- Declarative scene composition.
- Accessibility by default.

## ARCH-004 Data Flow
User Input → Scroll Engine → State Store → Scene Updates → Camera → UI Synchronization.

## Acceptance Criteria
The architecture should support future expansion while keeping individual systems loosely coupled and easy to maintain.