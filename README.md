# Antimatter Lab — Stage 1

This is the Stage 1 frontend foundation for the educational antimatter platform.

## Included
- React + TypeScript + Vite project
- Three.js scene with electron and positron visual placeholders
- Simulator / Learning Hub / History Zone navigation
- Responsive dark scientific interface
- Clearly marked placeholder physics values and future Stage 2 work

## Run locally
Requires Node.js 20 or newer.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Important scientific boundary
The Stage 1 particle scene is only a visual placeholder. It does not yet calculate or animate a physical annihilation. Stage 2 will implement a deterministic relativistic physics engine and automated energy/momentum conservation tests. The UI must never present unvalidated animation as a calculated physical result.
