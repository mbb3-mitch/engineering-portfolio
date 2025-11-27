# Engineering Portfolio: mbb3-mitch

> Building practical tools, shipping full-stack solutions, and learning by doing—this is my narrative.

---

## Repo Name & Positioning

- Repo: `engineering-portfolio-mbb3-mitch`
- Positioning: A curated showcase of my engineering projects—spanning internal tools, developer experience, prototypes, and pragmatic solutions across the stack.

## Folder Layout

```
/engineering-portfolio-mbb3-mitch
  /assets            # Screenshots, diagrams, logos (assets/<project>/...)
  /projects          # Individual project profiles: projects/<repo>.md
  README.md          # Main portfolio page
```

## Highlights

- 🛠 Builder of internal tools; developer productivity and experience focus.
- 🌐 Full-stack generalist: backend, frontend, DevOps.
- 💻 Cross-platform pragmatism: Mac, Windows, Linux.
- 🧑‍🔬 Prototypes and experiments, turning ideas into outcomes.
- 🌲 Calm, senior energy – tradeoffs, constraints, results matter.

---

## Project Index

Only showing projects with completed writeups.

| Project | Category | Stack | Links | 1-line Value |
|---------|----------|-------|-------|---------------|
| Calisthenics For A Year | Product | Django, DRF, React | [Profile](projects/cfay.md) · [Repo](https://github.com/mbb3-mitch/Calisthenics-For-A-Year) · [Live](https://calisthenicsforayear.com/) | Skill progression tracker with an API-first backend |
| CFAY SFX Challenges | Product | Django, DRF, React | [Profile](projects/cfay-sxf-challenges.md) · [Repo](https://github.com/mbb3/cfay-sxf-challenges) · [Live](https://challenges.calisthenicsforayear.com/#/) | Workout logging + analytics for challenge cohorts |
| Programmer Dvorak Typing Game | Experiment | React, Express | [Profile](projects/programmer-dvorak-typing-game.md) · [Repo](https://github.com/mbb3/programmer-dvorak-typing-game) · [Live](https://typingdvorak.com/) | Dvorak-focused typing drills with live stats |

---

## Project Groups

### 🏋️‍♂️ Fitness Platforms

- **Calisthenics For A Year**  
  Track skill progressions with Django/DRF + React; live at https://calisthenicsforayear.com/.  
  ![Skill detail](assets/cfay/skill-detail.png)  
  [Read more →](projects/cfay.md)

- **CFAY SFX Challenges**  
  Challenge-focused workout logger with analytics dashboards.  
  ![Workout dashboard](assets/cfay-sfx-challenges/workout-dashboard.png)  
  [Read more →](projects/cfay-sxf-challenges.md)

### 🎮 Learning & Experiments

- **Programmer Dvorak Typing Game**  
  Dvorak-specific typing drills with live stats and lesson tracks.  
  ![Typing session](assets/programmer-dvorak-typing-game/typing-session.png)  
  [Read more →](projects/programmer-dvorak-typing-game.md)

---

## How to Use This Portfolio

- Browse highlighted projects above.
- Visit `/projects/<repo>.md` for a deep dive (case studies, stack, notes, screenshots).
- Want more context? Reach out anytime.

## Per-Project Template

- Use `projects/TEMPLATE.md` as the starting point for each profile.
- Save screenshots and diagrams in `assets/<project>/` and reference them with `![desc](assets/<project>/<image>.png)`.

## Next Actions Checklist

- Add screenshots quickly: take OS screenshots, save in `assets/<project>/`, name them clearly (`overview.png`, `feature1.png`), and reference in project pages.
- Keep content current: update `/projects/<repo>.md` with new features, decisions, or outcomes; add visuals for major UI/architecture changes.
- Optional: enable GitHub Pages (Settings → Pages → main branch → `/` root) to publish; initial content can be README-based.

## Bonus: Codex README Upgrade Prompt

```
Task: Rewrite README.md for this repository to be portfolio-grade.

Requirements:

Keep any existing installation/usage steps accurate—do not break commands.

Write an opening summary in 2–4 lines: what it is + why it exists.

Add these sections if missing:

Features

Tech Stack

Local Development

Architecture / Notes (short)

Roadmap (3–6 bullets)

If the repo is a prototype/experiment, say so plainly.

Add a “Screenshots” section with placeholders:

assets/ path and image names

Keep the README concise and skimmable.

Output a complete updated README.md only.
```
