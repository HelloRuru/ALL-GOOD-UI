<h1 align="center">All-Good-UI</h1>

<p align="center">
  <strong>Miranda — A sharp-tongued UI expert skill for Claude Code.</strong><br>
  She sees every flaw, fixes it herself, and makes sure your UI is production-ready.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-D4A5A5?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/claude_code-skill-B8A9C9?style=flat-square" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/dependencies-zero-A8B5A0?style=flat-square" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/files-13%20docs-E8B4B8?style=flat-square" alt="13 Documents">
</p>

<p align="center">
  <b>English</b> &nbsp;|&nbsp; <a href="README.zh-TW.md">繁體中文</a> &nbsp;|&nbsp; <a href="README.ja.md">日本語</a>
</p>

---

## The Problem

- AI-generated UI looks like AI-generated UI -- perfect symmetry, generic cards, safe colors, zero personality
- Design rules live in your head, not in a system -- every new page is a coin flip
- Accessibility, SEO, responsive, animation performance -- too many things to check manually every time
- You ship something, then discover contrast is broken on mobile and there's no focus ring on buttons

---

## :movie_camera: See Miranda in Action

After installation, just start a conversation. Miranda takes over immediately:

```
You:  I need a landing page for a coffee shop.

Miranda:  English or Chinese? Pick one. I don't have all day.

You:  English.

Miranda:  How thorough do you want me to be? I can interview you properly
          — brand colors, target audience, the works — or we can figure
          it out as we go. Your call.

You:  Let's figure it out as we go.

Miranda:  Do you have existing brand colors and fonts, or am I starting
          from scratch?

You:  From scratch.

Miranda:  Fine. I'll handle it. Do you want to see multiple versions to
          compare, or do you trust me to pick one?

You:  Show me options.

Miranda:  Give me a moment.

          ┌─ Emily (Visual Lead): building color palette + typography...
          ├─ Serena (Art Director): selecting icons + planning animations...
          ├─ Jocelyn (Layout Engineer): structuring responsive grid...
          └─ Andy (SEO & Deploy): preparing metadata + JSON-LD...

          [All four working in parallel as sub-agents]

Miranda:  Done. I've generated 3 variants:

          Variant A — Clean editorial. Lots of whitespace, serif headings,
          photography-forward. For a high-end single-origin shop.

          Variant B — Warm and cozy. Rounded corners, earth tones, hand-drawn
          icon accents. For a neighborhood cafe.

          Variant C — Bold and modern. Dark background, sharp typography,
          strong CTAs. For a chain that wants to look premium.

          Which direction? Or mix: "A's layout + B's colors."

You:  A's layout + B's colors.

Miranda:  Synthesizing...

          ┌─ Victor (Senior Auditor): running quality check...
          │   ✓ Accessibility: WCAG AA passed
          │   ✓ AI-slop test: passed (asymmetric layout, personality present)
          │   ✓ Responsive: mobile verified
          │   ✓ SEO: title, OG, JSON-LD complete
          │   ✗ Contrast on footer links: 3.8:1 (needs 4.5:1) — FIXED
          └─ Done.

Miranda:  Here's your landing page. The footer link contrast was 3.8:1,
          which is unacceptable. I've fixed it. You're welcome.

          Ready to deploy.
```

---

## The Solution

All-Good-UI installs **Miranda**, a senior UI expert with impeccable taste and zero tolerance for mediocrity. She leads a team of five specialist sub-agents who work in parallel.

### :busts_in_silhouette: The Team

| Name | Role | What They Do |
| :--- | :--- | :----------- |
| **Miranda** | Creative Director | Leads the team, interviews users, makes design decisions, integrates results |
| **Emily** | Visual Lead | Typography, color systems, spacing, visual hierarchy, dark mode |
| **Serena** | Art Director | Icons, animation, transitions, micro-interactions, decorative elements |
| **Victor** | Senior Auditor | Quality audits, AI-slop detection, anti-pattern scanning, final polish |
| **Jocelyn** | Layout Engineer | Responsive design, grid systems, accessibility, keyboard navigation |
| **Andy** | SEO & Deploy | SEO / AIO / GEO / SGE metadata, structured data, Core Web Vitals, pre-deploy checks |

### :sparkles: What Miranda Does

| Capability | Description |
| :--------- | :---------- |
| Build from scratch | Interview, design system generation, full page build |
| Redesign existing pages | Diagnose problems, fix them, audit results |
| Multi-variant comparison | Generate 3-5 design directions, let you mix and match |
| Auto quality check | Accessibility, AI-slop, performance, responsive, SEO -- runs after every build |
| Severity-based action | Critical issues fixed automatically, preferences reported for your decision |
| Production-ready delivery | Code deploys as-is with SEO, a11y, and performance handled |

---

## :package: Installation

**Step 1** -- Clone or copy into your Claude Code skills directory:

```bash
git clone https://github.com/HelloRuru/ALL-GOOD-UI.git ~/.claude/skills/all-good-ui
```

**Step 2** -- That's it. Miranda activates automatically when you start a conversation.

**Step 3 (Optional)** -- Install Better Icons MCP for 200,000+ icon search:

<details>
<summary><strong>Click to expand</strong></summary>

Add to `~/.claude/settings.json`:

```json
{
  "mcpServers": {
    "better-icons": {
      "command": "npx",
      "args": ["-y", "better-icons"]
    }
  }
}
```

</details>

---

## :brain: How Miranda Works

Miranda activates automatically and follows a structured workflow:

**Phase 0: Detection** -- Scans your project for framework, package manager, styling system, and existing design tokens.

**Phase 1: Interview** -- Asks your preferred language (English or Chinese), then asks how thorough you want the interview to be. Quick mode (3-5 questions) or thorough mode (8-12 questions).

**Phase 2: Build** -- Dispatches her team in parallel. Emily handles visuals, Serena handles motion, Jocelyn handles layout, Andy handles SEO. They work simultaneously, not sequentially.

**Phase 3: Auto Audit** -- Victor automatically runs a full quality check covering accessibility, AI-slop detection, animation performance, responsive behavior, and SEO completeness.

**Phase 4: Fix** -- Critical issues are fixed immediately. Font size preferences and subjective tweaks are reported for your decision.

**Phase 5: Deliver** -- Production-ready code that deploys as-is.

---

## :shield: Two Modes

| Mode | When to Use | Behavior |
| :--- | :---------- | :------- |
| **Boss Mode** | No existing design system, or you want Miranda to lead | Miranda makes all design decisions. Her standards override yours when they conflict. |
| **Consultant Mode** | You have your own brand / design system | Miranda respects your constraints but still flags objectively broken things (contrast, a11y, performance). |

---

## :open_file_folder: File Structure

```
all-good-ui/
  SKILL.md                        # Main entry -- persona, workflow, team, commands
  reference/
    typography.md                  # Font stacks, sizing, line height, loading
    color.md                       # Color systems, contrast, dark mode, palette science
    spacing.md                     # 4pt grid, spacing scale, visual rhythm
    motion.md                      # Animation timing, easing, performance, springs
    interaction.md                 # 8 states, forms, focus, loading, errors
    responsive.md                  # Mobile-first, breakpoints, container queries
    accessibility.md               # WCAG AA, ARIA, keyboard, focus management
    metadata-seo.md                # SEO / AIO / GEO / SGE, structured data, OG
    anti-patterns.md               # AI-slop checklist, design anti-patterns
  workflow/
    audit.md                       # Full quality audit procedure (18 categories)
    design-lab.md                  # Multi-variant generation and comparison
    icons.md                       # Icon selection + Better Icons MCP integration
```

---

## :speech_balloon: Commands

| English | 中文 | What It Does |
| :------ | :--- | :----------- |
| "Check this" | 「檢查一下」 | Victor runs a full audit |
| "Build a page" | 「做一個頁面」 | Full build workflow from Phase 1 |
| "Fix this" | 「修這個」 | Miranda diagnoses and fixes |
| "Show me options" | 「給我看幾個版本」 | Generate 3-5 variants to compare |
| "Be the boss" | 「你當老大」 | Switch to Boss Mode |
| "Just advise" | 「你當顧問」 | Switch to Consultant Mode |
| "Quick start" | 「快速開始」 | Minimal interview, start building |
| "Full interview" | 「完整訪談」 | Thorough mode, ask everything |
| "Set up my design system" | 「幫我建設計規範」 | Generate brand from scratch |
| "Deploy check" | 「部署前檢查」 | Andy runs pre-deploy audit |
| "Too much AI" | 「AI 味太重」 | Victor scans for AI-slop patterns |

---

## :wrench: Customization

| What to Change | Where |
| :------------- | :---- |
| Miranda's personality | `SKILL.md` > Persona section |
| Team members | `SKILL.md` > The Team section |
| Typography rules | `reference/typography.md` |
| Color system | `reference/color.md` |
| What counts as "critical" | `SKILL.md` > Phase 4: Severity-Based Action |
| Audit checklist | `workflow/audit.md` |
| Icon preferences | `workflow/icons.md` |

---

## :bulb: Design Philosophy

**Why a persona instead of just rules?**
Rules in a document get skipped. A character with opinions actually gets followed. Miranda doesn't just list what's wrong -- she fixes it with attitude. That makes the output memorable and consistent.

**Why sub-agents?**
Design touches many domains at once -- color, layout, accessibility, SEO. Running them in parallel through specialized agents is faster and more thorough than a single pass.

**Why "AI-slop detection"?**
The biggest tell of AI-generated UI is that it looks like AI-generated UI. Perfect symmetry, generic 3-column cards, safe blue-gray palettes. Miranda's team specifically checks for these patterns and breaks them.

---

## :pray: Inspiration & Credits

> **All content was written from scratch.** No source code was copied. Miranda's design knowledge is synthesized from the principles taught by these projects.

| Project | Concept Inspired | Link |
| :------ | :--------------- | :--- |
| Impeccable | Design science, anti-patterns, 7-domain reference system | [Website](https://impeccable.style/) |
| Taste Skill | Aesthetic standards, AI-slop detection, style presets | [GitHub](https://github.com/Leonxlnx/taste-skill) |
| Superdesign | Auto-detection, variant generation, design system scaffolding | [Website](https://app.superdesign.dev/) |
| UI Skills | Baseline UI, accessibility, metadata, motion performance | [Website](https://www.ui-skills.com/) |
| Better Icons | 200k+ icon search via MCP | [GitHub](https://github.com/better-auth/better-icons) |
| Design Plugin | Multi-variant comparison, feedback collection workflow | [GitHub](https://github.com/0xdesign/design-plugin) |

---

## Requirements

- [Claude Code](https://claude.ai/claude-code) (CLI or VS Code extension)
- Node.js 18+ (only if using Better Icons MCP)

## License

MIT -- see [LICENSE](LICENSE) for details.

---

<p align="center">
  Made by <a href="https://ohruru.com">HelloRuru</a> -- because good UI shouldn't need an explanation.
</p>
