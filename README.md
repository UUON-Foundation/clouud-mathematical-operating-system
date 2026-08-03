cat > ~/Desktop/clouud-mathematical-operating-system/README.md << 'EOF'
# CLOUUD

UUON Foundation Inc. — Phillip Aguilar Ruiz III

A living computational system. Not a platform. Not a software stack. A mathematical operating system built on biological architecture — generating, storing, routing, and serving the complete mathematical substrate of natural form.

Each engine fills a biological function. Not metaphorically. Structurally. The mathematics governing biological systems and the mathematics governing these engines is the same mathematics.

---

## Biological Architecture

**Spine** — Express routing, GitHub OAuth, session state, rate limiting. The required substrate for everything else.

**Skeleton** — [Wave Field 3D Engine](https://github.com/UUON-Foundation/wave-field-3d-engine). 24 wave algorithms across a unified surface coordinate system. Deterministic frame sampler. Hand-built GLTF 2.0 encoder.

**Proprioception** — Propagation Engine. State change across connected graph networks. Three modes: Neural, Stress, Epidemic. Documented emergent equilibrium at 62% network activation.

**Visual Cortex** — [Recursive Fractal Engine](https://github.com/UUON-Foundation/recursive-fractal-engine). 7,744 distinct attractors from one compiled shader. Quantum generators producing probability density landscapes.

**Decision Layer** — Boundary State Engine. Binary threshold crossings, Shannon entropy, Boltzmann entropy, hypercube geometry from 0D to 3D.

**Prefrontal Cortex** — [pscience](https://github.com/UUON-Foundation/pscience-perception-engine). Competing interpretations held open simultaneously before collapsing to the most information-dense candidate.

**Fractal Skeleton** — [Kleinian-Hybrid IFS Engine](https://github.com/UUON-Foundation/mandelbox-amazing-family-engine). 462,026 vertices, fractal dimension 2.20-2.25, tetrahedral symmetry.

**Vascular Branching** — [Pythagorean Graph Engine](https://github.com/UUON-Foundation/pythagorean-graph-engine). Recursive binary tree topology from Pythagorean triples. Full graph export with provenance metadata.

**Compression Field** — [AIBH Compression Field Engine](https://github.com/UUON-Foundation/compression-field-engine). Four-zone infall model. Information encoded as gravitational particle field. Shannon entropy per zone.

**Atomic Structure** — [Hydrogenoid Atom Engine](https://github.com/UUON-Foundation/Hydrogenoid-Atom-Engine). Quantum orbital geometry rendered from first principles.

---

## Context Pipeline

Live world data enters through a public RSS adapter, passes through the AIBH Compression Field Engine for entropy classification and gravitational zone ranking, and reaches the Ollama reasoning layer already structured — not raw.

---

## Engine Index

| Biological Function | Engine | Status |
|---|---|---|
| Spine | uuon-clouud routing | Live |
| Skeleton | Wave Field 3D | Live |
| Visual Cortex | Recursive Fractal | Live |
| Vascular Branching | Pythagorean Graph | Live |
| Prefrontal Cortex | pscience | In progress |
| Compression Field | AIBH | Live |
| Fractal Skeleton | Kleinian IFS | Built |
| Proprioception | Propagation Engine | Built |
| Decision Layer | Boundary State | Built |
| Atomic Structure | Hydrogenoid Atom | Built |

---

## Getting Started

Requires Node.js 20+, Ollama running locally.

```bash
npm install
npm run dev
```

```bash
npx ts-node clouud-cli.ts
```

API runs on http://localhost:3000. CLI connects to Ollama at http://localhost:11434.

---

## IP Architecture

Engine cores are proprietary under USAL-1.0. Each public engine repo contains the renderer shell only. Core implementations are served from uuon.world and are not in any public repository. The CLI and API surface are open.

Commercial licensing available by arrangement.

Contact: phi1@uuonfoundation.com
EOF
git add README.md
git commit -m "docs: full engine index, IP architecture, repo links"
git push origin main
