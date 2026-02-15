[한국어](./README-ko.md)

# Hi, I'm Youngjae

I'm a self-taught full-stack engineer who makes complex systems predictable and observable.
At BoxHero, that means turning intricate business domains into clean product behavior.
Outside of work, I apply the same instinct to AI systems, developer tools, and Linux workflows.

## Contact

- Email: `bityoungjae@gmail.com`

## Core Strengths

- Fast, self-directed learner: Every language, framework, and system I work with, I picked up on my own — through official docs, not courses. I learn fast by building, and I don't slow down.
- Turning complexity into structure: I take tangled business rules, opaque model behavior, and undocumented interfaces and build systems with clear state, explicit boundaries, and observable internals.
- Verification over assumption: I don't guess how systems behave — I observe, experiment, and verify. When I can't see inside something, I build tools to make it visible.
- Right-sized engineering: I match the solution to the problem. Type-level constraints over runtime checks. Focused modules over frameworks. Deliberate limits over speculative flexibility.
- Tooling instinct: When I notice friction in a workflow, I build something to remove it — CLI tools, automation pipelines, editor extensions.

## Experience

### BoxHero · Full-stack Developer

- First tenure: Sep 2020 - Aug 2022
- Rejoined: Jan 2023 - Present

Contributing to a global inventory management platform serving thousands of businesses.

Key contributions:

- Built full-stack product features with Clojure/ClojureScript and Re-frame
- Implemented advanced inventory workflows (serial, batch, and expiration tracking)
- Developed order/return flows, invoice customization, and print sessions
- Executed zero-downtime schema migrations and idempotent integration patterns
- Built barcode/QR workflows, scanner integrations, and document rendering pipelines
- Improved internal automation for i18n and day-to-day engineering operations

### AnnotationAI · Frontend Developer

- Sep 2022 - Jan 2023

Built annotation interfaces for AI data labeling with React, Vue.js, and TypeScript.

## Selected Public Projects

Couldn't find what I wanted, so I made my own. I use all of them.

- [ChalKak](https://github.com/BitYoungjae/ChalKak):
  I wanted screenshots on Hyprland to feel like a complete product, not a pile of scripts.
  Built a preview-first Wayland capture tool in Rust with a lightweight annotation editor (blur, pen, arrow, rectangle, crop, text), keyboard-first flow, configurable theme/keybindings, and release packaging for AUR.

- [gitkkal-skills](https://github.com/BitYoungjae/gitkkal-skills):
  Working with AI coding assistants, branch names, commit messages, and PR structure tend to get inconsistent.
  This skill set keeps the entire Git workflow — from branch creation to PR authoring — clean and uniform. Originally built as a Claude Code plugin, then restructured into standard Agent Skills when I started using Codex too.

- [marketplace](https://github.com/BitYoungjae/marketplace):
  I kept building tools for Claude Code until I had five.
  Learning material generation, Neovim diagnostics, Obsidian visual blocks, Git automation, Linux theming — bundled into a single marketplace for easy installation and management.

- [mpvpaper-rs](https://github.com/BitYoungjae/mpvpaper-rs):
  I wanted motion wallpapers on my Wayland desktop. The original mpvpaper had memory leak issues, so I rewrote it in Rust — only to find the leaks were coming from an external dependency I couldn't control. They're still there, but the work was too good to throw away, so I published it as an AUR package anyway.

- [garak](https://github.com/BitYoungjae/garak):
  I listen to Spotify on my Hyprland + Waybar setup, and controlling playback was just annoying enough to do something about it. Built an MPRIS popup with GTK4 and TypeScript — album art, playback controls, and a seekable progress bar.

- [byj-cc-statusline](https://github.com/BitYoungjae/byj-cc-statusline):
  During long Claude Code sessions, there's no way to tell when context will auto-compact. This statusline shows the current model, Git status, and remaining token budget in one line. The popular alternatives felt overcomplicated, so I made something that just shows what actually matters. Runs on bash and jq — nothing else.

- [bityoungjae.nvim](https://github.com/BitYoungjae/bityoungjae.nvim):
  I was building a theme for Omarchy and couldn't find a Neovim colorscheme that matched, so I made one just for myself. Turns out customizing your own editor environment is more fun than I expected.

## Private Work

Much of my recent work lives in private repositories.
It's still in progress, so I can't share details — but I'm exploring how to use LLMs at the application level and how to build production-grade agent systems, by actually building them.

Lately I've been digging into Claude Code's internals — antml tags, Auto Memory, System Reminders, and more. There's a lot to find interesting. The more I learn, the more impressed I am: it's a system that extracts remarkable value from near-sandcastle-fragile foundations, through deep thought and clever engineering.

## Tech I Use Often

- Languages: TypeScript, JavaScript, Clojure, ClojureScript, Rust
- Frontend: React, Next.js, Astro, Re-frame, Tailwind CSS
- Backend: Node.js ecosystem, Ring, PostgreSQL, HugSQL
- AI/LLM: Claude Code ecosystem tooling, system/prompt workflow design, reproducible evaluation loops, security-minded prompt analysis, API integrations (OpenAI/Claude), and practical automation patterns
- Tooling/Runtime: Electron, Shell, CLI tooling, Neovim
- DevOps: Docker, GitHub Actions, AWS

## How I Work

- Design first, then build — architecture specs and type contracts come before implementation
- Treat AI systems as production infrastructure: explicit assumptions, trust boundaries, and operational runbooks
- Optimize for reproducibility over one-off cleverness
- Make practical architecture decisions with clear trade-offs
- Document decisions and verification steps so work is transferable across teams
