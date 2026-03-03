# Reframe Canvas

An interactive Problem Framing Canvas based on **MITRE's Look Inward / Look Outward / Reframe** methodology. A single-file HTML tool that helps teams define the right problem before jumping to solutions.

![Canvas View](https://img.shields.io/badge/view-Canvas%20Matrix-9B3B5A) ![Guided View](https://img.shields.io/badge/view-Guided%20Wizard-2E7D6F) ![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-B8860B)

<video src="https://github.com/avinashlingaloo/reframe-canvas/releases/download/v0.2.0/mitre-problem-facing-canvas.mp4" controls width="100%"></video>

## What It Does

Most teams fail not because they build the wrong solution, but because they solve the wrong problem. This tool enforces structured divergence before convergence through three phases:

| Phase | Focus | Key Questions |
|-------|-------|---------------|
| **Look Inward** | Your assumptions, capabilities, and blind spots | What is the problem? Why haven't we solved it? How are we part of it? Who experiences it? |
| **Look Outward** | External landscape, analogies, and stakeholders | Who else has it? Who doesn't? Who's been left out? Who benefits from the status quo? |
| **Reframe** | Synthesis and redefinition | What patterns emerge? How might we restate the problem? What's the actionable HMW? |

## Two Ways to Work

**Canvas View** — A single-page matrix grid (inspired by MITRE's Problem Framing Canvas V3). Everything visible at once. Fill cells in any order. Best for experienced practitioners and team workshops.

**Guided View** — A step-by-step wizard that walks you through each phase sequentially. Best for first-time users or solo deep thinking.

Both views share the same data in real-time. Switch between them freely using the toggle in the top bar.

## Getting Started

```bash
# Clone and open — that's it
git clone https://github.com/avinashlingaloo/reframe-canvas.git
open reframe-canvas/reframe-tool.html
```

No build step. No dependencies. No server. Just open the HTML file in any modern browser.

### Demo Data

To see the tool pre-filled with a realistic example (B2B SaaS trial activation problem):

1. Open `reframe-tool.html` in your browser
2. Open the browser console (`Cmd+Shift+J` / `Ctrl+Shift+J`)
3. Paste the contents of `load-demo.js` and press Enter
4. Refresh the page

## Features

- **Auto-save** — Every keystroke persists to localStorage. Close the tab and come back later.
- **Markdown export** — Download your analysis as a structured `.md` file or copy to clipboard.
- **Checkbox inputs** — "Why haven't we solved it?" and "Why not?" categories match the original MITRE canvas.
- **HMW format** — The Reframe section uses the "How might we ___ as we aim to ___" actionable format.
- **Progress bar** — Visual indicator of how many fields you've completed across all phases.
- **Responsive** — Works on desktop, tablet, and mobile.

## Background

The **Problem Framing Canvas** was created by MITRE's Innovation Toolkit (itk.mitre.org) as part of their systems engineering methodology. The core insight: breakthroughs come not from better answers, but from better questions.

This digital version is not affiliated with MITRE. It adapts their publicly available Problem Framing Canvas V3 into an interactive web tool.

## License

MIT
