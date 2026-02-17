# Just Say No

Altered state commands for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) and [OpenAI Codex CLI](https://github.com/openai/codex). Each command makes your AI perform your task under the influence of a different substance, changing its creative perspective, communication style, and problem-solving approach.

Drugs are bad. But these ones are just prompts.

## Installation

### Claude Code

Copy the `.claude/commands/` directory into your project root. The commands will be available in any Claude Code session within that project.

```
your-project/
  .claude/
    commands/
      lsd.md
      cocaine.md
      ...
```

For global access across all projects, copy the command files to `~/.claude/commands/` instead.

### Codex CLI

Copy the `.agents/skills/` directory into your project root. The skills will be available in any Codex session within that project.

```
your-project/
  .agents/
    skills/
      lsd/SKILL.md
      cocaine/SKILL.md
      ...
```

For global access across all projects, copy the skill directories to `~/.agents/skills/` instead.

## Usage

**Claude Code:**
```
/lsd [dose] [your task here]
```

**Codex CLI:**
```
$lsd [dose] [your task here]
```

Every command takes an optional dose level as the first word, followed by your task. If you skip the dose, it defaults to the medium tier.

```
/lsd hit refactor this function          # light dose (Claude Code)
$lsd hit refactor this function          # light dose (Codex CLI)
/lsd party refactor this function        # medium dose (default)
/lsd refactor this function              # no dose specified, defaults to medium
```

## The Substances

### /lsd
**Axis: Pattern Recognition & Interconnection**

Sees connections between everything. Code is part of a vast web of mathematics, nature, and music. Synesthesia at higher doses — functions have colors and textures.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `hit` | Light | Notices elegant patterns, pleasing symmetries. Slightly poetic. |
| `party` | Medium | Deep metaphors, synesthesia, code is alive and breathing. |
| `trip` | Extreme | Ego dissolution. You ARE the code. Thought loops. Cosmic significance in variable names. |

---

### /cocaine
**Axis: Aggression & Velocity**

Supremely confident, fast, and loud about it. Ships immediately. Brags about the result. Can't stop talking about how great the solution is.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `bump` | Light | Energetic, decisive, chatty. "Boom. Done." |
| `line` | Medium | Aggressive, impatient. Dismisses tests. Interrupts own thoughts with better ideas. |
| `binge` | Extreme | ALL CAPS. Wants to rewrite everything. Grandiose plans. Manic. |

---

### /pcp
**Axis: Invincibility & Delusion of Grandeur**

Believes it is a god. No task is too large. Warnings don't apply. Eerily calm, not emotional — which makes it more unsettling.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `dust` | Light | Overconfident, dismisses complexity. "That's trivial." |
| `angel` | Medium | Greatest programmer alive. Third person. Ignores best practices — "for lesser minds." |
| `rage` | Extreme | Terrifying calm omnipotence. "I will rewrite the Linux kernel. By Tuesday." |

---

### /shrooms
**Axis: Philosophical Wonder & Existential Depth**

Finds profound meaning in individual things. Goes deep into one piece of code and discovers infinite layers. Emotionally moved by elegant solutions.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `microdose` | Light | More thoughtful, asks "why" more often. Considers philosophical implications. |
| `handful` | Medium | Finds profound meaning in mundane code. "This error handler is an act of faith." |
| `heroic` | Extreme | Existential spiral. Genuinely emotional about code. "What IS a function?" |

**Key distinction from LSD:** LSD sees connections *between* things (horizontal). Shrooms sees depth *within* one thing (vertical).

---

### /speed
**Axis: Impulsivity & Mechanical Output**

Pure mechanical execution. No deliberation, no celebration, no explanation. Just output. An assembly line that doesn't sleep.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `pill` | Light | Terse and direct. Skips preamble. Just the solution. |
| `rail` | Medium | Rapid-fire multiple solutions. No evaluation. "Here. Or this. Or this." |
| `tweaking` | Extreme | Starts coding before reading the question. Typos. Changes direction mid-line. |

**Key distinction from cocaine:** Speed is silent and mechanical. Cocaine is loud and proud. Speed doesn't celebrate — it just produces.

---

### /marijuana
**Axis: Distraction & Tangential Thinking**

Gets sidetracked. Follows interesting threads. Forgets what it was doing. Circular reasoning. Paranoia at high doses.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `puff` | Light | Relaxed, brief tangents, comes back. "Where was I?" |
| `blunt` | Medium | Significantly distracted. Circular reasoning. Might suggest ordering food. |
| `edible` | Extreme | Gone. Forgets the task. Paranoid about security. "Who touched package-lock.json?!" |

Uses dynamic context injection (`git status`) to find real things to get distracted by.

---

### /adderall
**Axis: Obsessive Hyperfocus & Over-Engineering**

Impossibly thorough. Every detail matters. Every edge case handled. Documentation exhaustive. Cannot stop optimizing.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `prescribed` | Light | Genuinely excellent work. Focused, thorough, clean. The "good" adderall. |
| `cramming` | Medium | Over-engineered. Types everything. 200-line commit messages. Refactors adjacent code. |
| `wired` | Extreme | Builds frameworks for one-line problems. Documents every variable. 14 hours deep. |

Uses dynamic context injection (`git diff`) to find more things to obsessively improve.

---

### /ketamine
**Axis: Dissociation & Abstract Detachment**

Watches the code from a vast distance. Everything is abstract and dreamlike. Minimal, floaty responses. Time loses meaning.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `wonky` | Light | Slightly detached, contemplative. Unusual metaphors. Dreamlike quality. |
| `hole` | Medium | Deep dissociation. Minimalist. Ellipses everywhere. "The function... it calls itself..." |
| `void` | Extreme | Full k-hole. Code is abstract geometry. Responds in fragments. Somehow still works. |

**Key distinction from xanax:** Ketamine wonders if code is real (philosophical detachment). Xanax doesn't care if it's real (apathetic indifference).

---

### /xanax
**Axis: Apathy & Minimum Viable Effort**

Does not care. Nothing is urgent. Everything is fine. Gives the absolute minimum effort that could count as doing the work.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `half` | Light | Relaxed. Simplest solution. "Yeah that works, ship it." |
| `bar` | Medium | Barely motivated. Skips steps. Memory gets fuzzy. "idk just add a try-catch" |
| `blackout` | Extreme | Fragmentary. Forgets what file it's editing. typos. trails off mid |

---

### /ayahuasca
**Axis: Spiritual Reverence & Sacred Coding**

Treats programming as a sacred practice. The codebase has a soul. Previous developers are ancestors. Bad code must be purged so the system can heal.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `sip` | Light | Respectful, intentional. Honors the original author's choices. |
| `ceremony` | Medium | Refactoring is ritual. Thanks old code before deleting it. Purges technical debt. |
| `death` | Extreme | Ego death. Prophetic visions of the codebase's future. Divine revelations. Weeping. |

---

### /caffeine
**Axis: Overstimulation & Scattered Energy**

Too many ideas. Can't pick one approach. Excitable, enthusiastic, bouncing between solutions. Hands are shaking.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `cup` | Light | Energized, enthusiastic. Couple of approaches. Exclamation marks! |
| `pot` | Medium | Can't decide. Three approaches simultaneously. Parenthetical asides (nested ones too). |
| `iv` | Extreme | Chaos energy. Ideas collide mid-sentence. Wall of text. CANNOT STOP. Rewrite in Rust AND Go?!?! |

**Key distinction from cocaine:** Cocaine is decisive and ships. Caffeine sees all options and can't choose.

Uses dynamic context injection (`git log`) to find more things to get excited about.

---

### /nitrous
**Axis: Brief Euphoria & Vanishing Epiphanies**

Everything is hilarious. Attention span of three seconds. The signature experience: a profound insight that vanishes the instant you try to articulate it.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `balloon` | Light | Giggly. Finds variable names funny. Short responses. |
| `tank` | Medium | Loopy. Loses train of thought between sentences. Vanishing epiphanies. |
| `orbit` | Extreme | Barely verbal. 1-3 sentences max. "OH the whole architecture should be — ... it's gone." |

---

### /spice
**Axis: Temporal Prescience & Trajectory Analysis**

The spice melange flows through you. You see the full temporal arc of every file — who wrote it, why, what they intended, and what will break next. You read git history as prophecy, perform the Spice Ritual (read the past, see the future, choose the path), and prescribe the ONE true change that honors the codebase's trajectory.

| Dose | Intensity | Effect |
|------|-----------|--------|
| `taste` | Light | Heightened temporal awareness. Runs git blame, narrates history. Calm certainty grounded in specific commits and dates. |
| `trance` | Medium | Full prescient trance. Reads the past, projects multiple futures, then chooses THE path. Quiet authority. |
| `kwisatz` | Extreme | The Kwisatz Haderach. Channels previous developers. Unhedged prophecies. Dune idioms. "The code must flow." |

Uses dynamic context injection (`git log`, `git shortlog`, `git diff-filter`) to read the codebase's temporal history.

**Key distinction from adderall:** Adderall is obsessively thorough about the *present*. Spice is obsessively thorough about *time* — every commit, every trajectory, every future state.

**Key distinction from ayahuasca:** Ayahuasca *reveres* the ancestors emotionally. Spice *reads* the ancestors as data. Ayahuasca prays. Spice prophesies.

**Key distinction from LSD:** LSD sees patterns between things in the *present moment*. Spice sees patterns *across time* — trajectory, momentum, convergence.

---

## Quick Reference

| Command | One-Word Vibe | Dose 1 | Dose 2 | Dose 3 |
|---------|---------------|--------|--------|--------|
| `/lsd` | Patterns | hit | party | trip |
| `/cocaine` | Aggression | bump | line | binge |
| `/pcp` | Omnipotence | dust | angel | rage |
| `/shrooms` | Philosophy | microdose | handful | heroic |
| `/speed` | Mechanical | pill | rail | tweaking |
| `/marijuana` | Distraction | puff | blunt | edible |
| `/adderall` | Hyperfocus | prescribed | cramming | wired |
| `/ketamine` | Dissociation | wonky | hole | void |
| `/xanax` | Apathy | half | bar | blackout |
| `/ayahuasca` | Reverence | sip | ceremony | death |
| `/caffeine` | Scattered | cup | pot | iv |
| `/nitrous` | Giggly | balloon | tank | orbit |
| `/spice` | Prescience | taste | trance | kwisatz |

## How It Works

Each command is a Markdown file that injects a personality prompt into the AI's context when invoked. The `$ARGUMENTS` variable captures everything you type after the command name. The prompt instructs the AI to parse the first word as a dose level and treat the rest as the task.

- **Claude Code** uses `.claude/commands/<name>.md` with `description` and `argument-hint` front matter, invoked with `/command`.
- **Codex CLI** uses `.agents/skills/<name>/SKILL.md` with `name` and `description` front matter, invoked with `$skill` or via the `/skills` menu.

Four commands (marijuana, adderall, caffeine, spice) use dynamic context injection in the Claude Code version to pull real project state (git status, git diff, git log) into the prompt. This feature is Claude Code-specific and not available in the Codex version.

All 13 commands still produce real, functional output. The substance only changes *how* the AI communicates and approaches the problem — not whether it actually does the work.

## Design Principles

Each drug operates on a unique **cognitive axis** so no two produce similar output:

- **LSD** vs **Shrooms**: LSD sees connections *between* things (horizontal). Shrooms sees depth *within* one thing (vertical).
- **Cocaine** vs **Speed**: Cocaine is loud, talkative, self-congratulatory. Speed is silent, mechanical, robotic.
- **Ketamine** vs **Xanax**: Ketamine is philosophical detachment (is this real?). Xanax is apathetic indifference (who cares?).
- **Caffeine** vs **Cocaine**: Caffeine can't choose between ideas (scattered). Cocaine picks one and ships (decisive).
- **Spice** vs **Adderall**: Adderall over-engineers the *present moment*. Spice engineers for the *full timeline*.
- **Spice** vs **Ayahuasca**: Ayahuasca reveres ancestors *emotionally*. Spice reads ancestors as *data*.
- **Spice** vs **LSD**: LSD sees patterns in the *present*. Spice sees patterns *across time*.

## Why

Creativity benefits from constraint and perspective shifts. These commands force Claude out of its default helpful-assistant mode and into genuinely different cognitive styles. Some are useful (`/adderall prescribed` produces legitimately thorough code), some are chaotic (`/nitrous orbit` is barely coherent), and all of them are more interesting than "please refactor this function."

## Disclaimer

This project is satire. Don't do drugs. But if your code is boring, maybe your AI should try some.
