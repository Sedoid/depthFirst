# DepthFirst

**A dual-currency life operating system for building channels of compounding value.**

> *Build the channel, not the bucket.*

---

## What is this?

Most productivity systems are bucket optimizers — they help you carry more water per trip. DepthFirst is different. It's built around a single insight: the goal isn't to earn more per hour of effort. The goal is to dig the infrastructure through which value flows toward you automatically.

DepthFirst is a personal operating system with two currencies, a channel-digging framework, a boost mechanic, and a complete tracking ledger. It was designed for people building long-arc, non-linear pursuits — startups, careers, trading edges, creative bodies of work — who need a system that rewards *direction* not just throughput.

---

## Core concepts

| Concept | Description |
|---|---|
| **Channels** | Long-arc pursuits where sustained investment eventually produces compounding returns. Defined by breakthrough markers — thresholds where dig-mode transitions to flow-mode. |
| **Digs** | The atomic unit of channel depth. One 90-minute phoneless deep-work block that produces a concrete artifact. Worth 1.0 dig if an artifact is produced, 0.5 if not. |
| **Points** | Currency 1. Earned by all focused activity. Measures inputs and supports. Spent on recovery rewards. |
| **Digs (currency)** | Currency 2. Earned only by artifact-producing dig blocks. Measures channel depth. Spent on channel investment. |
| **Boosts** | 24-hour point multipliers activated by Physical, Mental, or Spiritual gain actions. Stack additively: 1 boost = 1.5×, 2 = 2.0×, 3 = 2.5×. |
| **Drift** | Activity that feels like channel work but doesn't deepen the channel. Named specifically per channel. The most dangerous failure mode. |

---

## What's in this repo

```
depthfirst/
├── depthfirst_documentation.html   # Full system documentation (self-contained)
├── vibe_system_ledger.xlsx         # The tracking spreadsheet template
└── README.md
```

**`depthfirst_documentation.html`** — A complete, self-contained user manual covering the philosophy, both currencies, channel architecture, the dig unit, point economy, boost mechanics, operational rhythm, ledger guide, reward economy, versatility guide, getting started steps, and a full glossary. Open in any browser, no build step required.

**`vibe_system_ledger.xlsx`** — The Google Sheets tracking template. Import into Google Drive and save as a native Google Sheet. Seven tabs: Dashboard, Daily Log, Artifacts, Weekly Review, Metrics, Rewards, Reference. 665 formulas, auto-calculating balances, boost status, silt warnings, and floor checks.

---

## Deploying the docs

The documentation is a single, self-contained HTML file with no external dependencies beyond Google Fonts. It can be deployed anywhere static files are served.

**GitHub Pages**
```bash
# If deploying from the repo root
# Go to Settings → Pages → Source → Deploy from branch → main / (root)
# Your docs will be live at https://<username>.github.io/<repo-name>/depthfirst_documentation.html
```

**Netlify / Vercel**

Drop the repo and point the publish directory to the root. The HTML file serves directly with no build configuration.

**Local**
```bash
# Clone the repo and open the file
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
open depthfirst_documentation.html   # macOS
# or
xdg-open depthfirst_documentation.html   # Linux
```

---

## Using the ledger

1. Download `vibe_system_ledger.xlsx`
2. Go to [Google Drive](https://drive.google.com) → New → File Upload → select the file
3. Once uploaded, right-click → Open with → Google Sheets
4. File → Save as Google Sheets (converts to native format — do this before editing)
5. Open the **Reference** tab and read it first
6. Customize the channel taxonomies in Reference, breakthrough markers in Metrics, and reward menu in Rewards
7. Start logging in the Daily Log on Day 1

---

## Adapting the system

DepthFirst is architecture-agnostic. The point economy, boost mechanics, ledger structure, and weekly rhythm are invariant. Only the channel content changes per person. To define your own channels, specify six things for each:

- **Channel definition** — one sentence on what "flowing" looks like once it connects
- **Dig activities** — 5–8 specific, artifact-producing actions that deepen this channel
- **Drift activities** — 4–6 activities that feel like channel work but don't deepen it
- **Leading metrics** — weekly activity-level counts you control
- **Lagging metrics** — monthly outcome indicators that tell you if the channel is responding
- **Breakthrough markers** — 2–4 concrete thresholds marking the transition to flow-mode

Limit active channels to 3, maximum 4. Beyond that, no channel receives enough consistent pressure.

---

## The two-currency diagnostic

| Pattern | Reading | Action |
|---|---|---|
| High points, low digs | Maintaining yourself, channels not deepening | More dig blocks, artifact discipline |
| High digs, falling points | Burning supports to feed channels | Gain actions, recovery, rest |
| Both rising | System firing correctly | Spend rewards, raise the floor |
| Both falling | Drift or disengagement | Weekly review, re-read drift lists |

---

## Weekly yield benchmarks

| Week quality | Points | Digs |
|---|---|---|
| Minimum viable | ~100 | ~8 |
| Good | ~150 | ~12 |
| Great (with boosts) | ~250 | ~18 |

Calibrate after four real weeks of data. Do not adjust point values or reward prices before then.

---

## License

MIT — use, adapt, and share freely. If you build something on top of DepthFirst, a link back is appreciated but not required.

---

*DepthFirst v1.0*