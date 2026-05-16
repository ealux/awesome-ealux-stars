# Awesome ealux's GitHub Stars — Systematization Map

**Profile**: [ealux (Egor Lyukhanov)](https://github.com/ealux) · Electric Power Systems Engineer, Yekaterinburg

**Total stars analyzed**: 445 (of ~453 on profile)  
**Primary languages**: C# (147), Python (100), C++ (48), TypeScript (21), C (17)  
**Last updated**: 2026-05-16

---

## Overview

This directory maps every starred repository into thematic clusters. The organization reflects the user's own GitHub list structure and the cross-cutting interests that emerge from the data. **All repo URLs have been verified against the actual API data** — every link corresponds to a repo ealux actually starred.

### Core Technical Identity

Egor's starred repos reveal a clear profile: a **power systems engineer** with deep expertise in **C#/.NET** who also invests heavily in:

- **AI coding agents** — the single largest category (~105 stars), covering Claude Code, Opencode, and the agent skill ecosystem
- **Numerical methods & HPC** — DSP, SIMD, optimization algorithms — applied to engineering problems
- **3D printing** — Klipper ecosystem, OrcaSlicer, Voron designs
- **Cross-pollination** — .NET GUI skills (WPF/Blazor) applied to engineering UI; SIMD knowledge used in both DSP and ML inference

---

## Cluster Map

| # | Cluster | Repos | Doc |
|---|---------|-------|-----|
| 1 | **AI / LLMs / Coding Agents** | ~105 | [↗](clusters/ai-llm-agents.md) |
| 2 | **.NET / C# / GUI** | ~135 | [↗](clusters/dotnet-gui.md) |
| 3 | **3D Printing / CAD / Embedded** | ~35 | [↗](clusters/3d-printing-embedded.md) |
| 4 | **Math / DSP / SIMD / HPC** | ~75 | [↗](clusters/math-dsp-simd.md) |
| 5 | **Power Systems / Energy** | ~30 | [↗](clusters/power-systems.md) |
| 6 | **Graphics / Visualization** | ~35 | [↗](clusters/graphics-visualization.md) |
| 7 | **Text / Data / Formats** | ~35 | [↗](clusters/text-data-formats.md) |
| 8 | **Games** | ~5 | [↗](clusters/games.md) |
| 9 | **Utilities / Awesome Lists** | ~50 | [↗](clusters/utilities-tools.md) |

---

## Language Distribution

```
C#              ████████████████████████████████████████████████████   147
Python          ███████████████████████████████████████░░░░░░░░░░░░   100
C++             ████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    48
TypeScript      ████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    21
C               ██████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    17
Jupyter         ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    11
HTML            ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    11
JavaScript      ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    11
Julia           ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░     8
Rust            ██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░     6
Other           ██████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    16
```

---

## Technical Stack (Inferred)

| Domain | Primary Stack |
|--------|--------------|
| Power engineering | Python (PYPOWER, PyPSA, pandapower), Julia (PowerDynamics), MATLAB (MATPOWER) |
| Desktop GUI | C# / WPF / Avalonia / WinUI / LiveCharts |
| Web frontend | Blazor / ASP.NET |
| ML/AI | Python (transformers, vllm, sglang), Claude/OpenAI ecosystem |
| DSP & numerics | C++ (DSPFilters, Simd, kfr), C# (MathSharp, NumSharp), Julia |
| 3D printing | Klipper, OrcaSlicer, FreeCAD, Voron |
| Embedded | C, C++, ARM CMSIS, Verilog/VHDL |
| Data | Polars, pandas, AngleSharp, LiteDB |

---

## How This Map Was Built

1. All 445 publicly starred repos fetched from GitHub API (5 pages × 100 per page)
2. Each repo classified by topics, description, and language
3. Clusters refined to match the user's own GitHub list organization (12 topic lists visible on profile)
