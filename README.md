# 👋 Hey, I'm Brendan Lucas

I'm a young developer, systems thinker, and language designer working on tools that challenge how we think about programming, file formats, and automation. I believe software should be **lightweight**, **transparent**, and **scalable**—and that most modern stacks are way too bloated for what they do.

## What I'm Building:

### Z# – The Low-Level, High-Power Language.
Z# is my from-scratch programming language that blends system-level control with modern syntax.  

- **User-defined types as first-class citizens**.
- **No runtime—compile directly to native binaries via `.iz` files**.
- A modular feature system, so only what you need gets compiled.

[Documentation](https://docs.zsharp.dev) · `zs emit` for bare-metal builds.

---

### CORAL.

**CORAL** is the intermediate representation (IR) used by Z# during compilation.
The name CORAL stands for **Compiled** **Object** **Representation** for **Abstract** **Logic**.

Like Z#, CORAL is configurable through Luau, allowing the compilation pipeline to be extended or customized without modifying the core compiler.

CORAL is architecture-independent, which makes it suitable for portable build artifacts. These artifacts can be reused as build checkpoints, enabling incremental builds and reducing total compilation time across targets.

---

### SV3D – Scalable Vector 3D Format.
I'm redefining 3D asset pipelines with SV3D:
- Infinite precision vector shapes rendered at runtime.
- ~(1000+)x smaller files than traditional formats.
- Optimized for games and real-time environments.
- Dynamic texturing with SVG-like patterns.

---

### Renderlabs Studio (Rewriting in Z#).
A 3D editor and animation toolkit using SV3D.  
Being rebuilt in Z# to maximize performance and push boundaries in how 3D assets are created and compiled.

---

### Subvertia – Automation That Fights Back.
Subvertia is a browser-based school automation tool that:
- Bypasses slow workflows.
- Uses stealth, AI, and headless logic.

Targeted at students, open-source soon. (*Not* your average homework helper.)

---

### Experimental Stuff.
- `zap` – The Z# package manager and CDN.

---

## Philosophy.

- Minimalism isn’t about less code. It’s about **less *waste***.
- The best code is the one that **respects the hardware**.
- If you can build it better, **build it**. Even if no one’s watching.
