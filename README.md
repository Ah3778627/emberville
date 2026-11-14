# Embervale

A procedural 2D HTML5 Canvas platformer featuring responsive platforming physics, three atmospheric stages, patrolling enemies, moving stone lifts, particle effects, and synthesized Web Audio sound effects.

## Features

- **3 Atmospheric Stages**:
  1. **Sunlit Ruins** — Golden-hour cliffside ruins and ancient stone bridges
  2. **Mossy Aqueduct** — Emerald-lit waterways with vertical and horizontal moving lifts
  3. **Obsidian Spire** — Crimson volcanic spire guarded by fast obsidian stalkers
- **Responsive Physics**: Variable jump height, coyote time, jump buffering, one-way stone slabs, and moving platform momentum
- **Combat & Checkpoints**: Head-stomp patrolling sentinels, activate checkpoint braziers, and collect coins and sky gems
- **Synthesized Web Audio**: Zero-dependency procedural sound effects with mute toggle
- **Desktop & Touch Support**: Full keyboard controls plus on-screen touch controls for mobile and tablet devices

## Controls

| Action | Keys |
| :--- | :--- |
| **Move Left / Right** | `A` / `D` or `←` / `→` |
| **Jump** | `W`, `↑`, or `Space` |
| **Pause** | `P` or `Esc` |
| **Restart Run** | `R` |
| **Toggle Sound** | `M` |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)

### Installation & Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```
   Open `http://localhost:3000` in your browser.

### Build for Production

```bash
npm run build
npm run preview
```
