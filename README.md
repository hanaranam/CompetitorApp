# CompetitorApp - Ritual (Class Demo Edition)

## Quick Start
1. `npm install`
2. `npm run dev`
3. Open `http://localhost:8081` for the mobile demo
4. Optional: open `./index.html` in browser for a demo control panel

## Project Structure
- `apps/mobile`: Expo + React Native Web app
- `apps/server`: Express + Socket.io in-memory backend
- `shared/mock-data.ts`: shared mock menu and pricing logic
- `docs/ARCHITECTURE.md`: architecture notes

## Implemented Scope
- System architecture scaffold (mobile/server/shared)
- Phase 1 customization and exact-pay interaction
- Phase 2 Sync-Link host/guest real-time shared cart via Socket.io
- Phase 3 Glass Box overlay, split-payment math, and JIT order tracker
- Web-only phone frame for projector-friendly demo
