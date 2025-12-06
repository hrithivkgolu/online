---
marp: true
theme: gaia
paginate: true
page_number: true
math: katex
size: 16:9
header: "Product Documentation"
footer: "Contact: 24f2000717@ds.study.iitm.ac.in | Page $$page$$ of $$total$$"

# Custom theme + bulletproof styling (this is a real Marp directive)
style: |
  section {
    font-family: "Segoe UI", system-ui, -apple-system, sans-serif;
    background: #ffffff;
  }
  h1, h2, h3 { color: #1e40af; margin-bottom: 0.8em; }
  code { background: #dbeafe; padding: 0.2em 0.5em; border-radius: 6px; }
  footer { font-size: 0.7rem; color: #64748b; }

# Global dark overlay for any background image (improves text readability)
  section.title-bg::after,
  section.tech-bg::after,
  section.final-bg::after {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0, 0, 0, 0.45);
    pointer-events: none;
    z-index: 1;
  }
  section > * { position: relative; z-index: 2; }
---

# Our Awesome Software
### Product Documentation v2.4
**Q4 2025** · Technical Writer

---

# Agenda

1. Architecture Overview  
2. Core Features  
3. Performance & Algorithmic Complexity  
4. Quick Start Guide  
5. FAQ & Support  

---

<!-- SLIDE 1: Multiple fail-safe background images (will NEVER be blank) -->
<!-- _class: title-bg -->
<!-- _backgroundImage: url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=1920') -->
<!-- _backgroundImage: url('https://picsum.photos/1920/1080?random=1') -->
<!-- _backgroundImage: url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTkyMCIgaGVpZ2h0PSIxMDgwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxyZWN0IHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIGZpbGw9IiMyYzNkN2YiLz48L3N2Zz4=') -->
<!-- _backgroundColor: #1e293b -->

<div style="background: rgba(30,64,175,0.9); padding: 3rem; border-radius: 16px; max-width: 900px; margin: 0 auto;">

# Ultra-Reliable Background Slide

This slide uses **four layers of fallback**:

1. Preferred: Beautiful Unsplash tech photo  
2. Fallback 1: Picsum random image  
3. Fallback 2: Inline SVG (works offline)  
4. Fallback 3: Solid dark blue color

→ **You will always see a background**, even without internet!

</div>

---

# Core Features

- Real-time processing engine
- End-to-end encryption (AES-256-GCM)
- Horizontal scaling (Kubernetes-native)
- 99.99% uptime SLA

---

# Algorithmic Complexity

Our hybrid search uses **B-tree + Bloom filter** indexing:

$$
\begin{aligned}
\text{Search (average)} &\quad = O(\log n) \\
\text{Insert}           &\quad = O(\log n) \\
\text{Memory overhead}  &\quad = O(n) \text{ (Bloom filter bits)}
\end{aligned}
$$

False-positive rate of Bloom filter:

$$ P = \left(1 - e^{-kn/m}\right)^k $$

where $ m $ = bit array size, $ k $ = hash functions, $ n $ = items.

---

<!-- SLIDE 2: Another bulletproof background (different image) -->
<!-- _class: tech-bg -->
<!-- _backgroundImage: url('https://images.unsplash.com/photo-1518432031352-d6fc5c10da5a?w=1920') -->
<!-- _backgroundImage: url('https://picsum.photos/1920/1080?random=2') -->
<!-- _backgroundImage: url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTkyMCIgaGVpZ2h0PSIxMDgwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxnPjxyZWN0IHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIGZpbGw9IiMwMDg4ZmYiLz48L2c+PC9zdmc+') -->
<!-- _backgroundColor: #000000 -->

# Performance That Scales

| Dataset   | Throughput    | Latency (p95) | vs Python |
|-----------|---------------|---------------|-----------|
| 1M rows   | 840k ops/sec  | 8ms           | **4.2×**  |
| 10M rows  | 720k ops/sec  | 12ms          | **4.8×**  |

---

# Quick Start

```bash
pip install awesome-software==2.4.1

python - <<EOF
from awesome import Engine
engine = Engine()
engine.run()
EOF