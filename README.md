# Phylactery

A desktop (and browser) command center I'm building to **prep and run** my tabletop
RPG sessions — one place for the cast, the mystery, the scenes, the battle map, and
everything I need at the table. Built around D&D 5e, but kept flexible.

It's an early alpha — I mostly tinker with it for my own games — so expect rough edges
and frequent updates.

## Download

➡️ **[Get the latest version](https://github.com/fuchcar/phylactery-releases/releases/latest)**

Download the `..._x64-setup.exe`, run it, and you're in. Windows may warn about an
unknown publisher — click **More info → Run anyway**. Once installed, it checks here for
updates and can update itself.

## Two modes

- **✎ Prep** — build the session: your world, cast, mystery, scenes, and maps.
- **▶ Live** — run it: a glanceable dashboard, combat, clocks, and quick rulings. Kept
  lean on purpose, so at the table you're *playing*, not doing data entry.

A left rail (dice roller, timers, turn order, quick notes) follows you on every screen,
so jotting something never pulls you away from what you're doing.

## What it does

- **Cast** — Build PCs, NPCs, and monsters. Add a character fast (one field at a time)
  or with a step-by-step wizard that *explains every 5e choice* — ancestry, class,
  ability scores, skills, spells — which helps a lot if you or your players are new.
  Full stat blocks with auto-derived HP/AC/to-hit/save math, and a one-click portrait
  **art-prompt** generator for AI image tools.

- **Compendium ("Living Grimoire")** — A built-in rules wiki that opens like a book —
  Spells, Bestiary, Magic Items, Conditions, Rules. It's a *big* bundled reference:
  roughly **1,000 spells, 2,150 creatures, and 1,400 magic items** drawn from the SRD and
  other license-clean sources, all searchable and filterable by book. Right-click any
  entry to favorite it, drop a monster into the tracker, or hand an item to the story.

- **The mystery (Case)** — A board for your leads and clues with a reveal-state tracker
  (hidden → revealed), the facts players can uncover, world-state flags, and faction
  standings. It nudges you toward the "three clues" rule so an investigation can't
  dead-end.

- **Scenes** — Lay out your beats with read-aloud text, private DM cues, and linked NPCs.

- **Battle map** — A proper tactical map editor: draw walls / rooms / doors, paint
  terrain (grass, stone, water; difficult / hazard / cover), drop in your own art, or hit
  **Generate** for an instant dungeon, cave, forest, or town. Dynamic lighting with
  wall-cast shadows, **fog of war** with a separate **player-view** window for a second
  screen, and **turn-aware darkvision** — on a Dark map the fog lights to whoever's turn
  it is. You run the actual fight on it: a **BG3-style action bar** for the active
  character, move tokens (with their speed enforced), aim attacks (with line-of-fire and
  a **Cover** tool), and preview areas of effect as smooth shapes that track your cursor.

- **Combat tracker** — Initiative order, HP with an undo-able damage log, conditions,
  concentration, and death saves. Pull a creature in and its real attacks/spells resolve
  — roll to-hit vs AC, crits, damage, range/reach enforced — with re-roll and
  *confirm-before-it-logs* so you stay in control. Spell effects apply with one click
  (buff/debuff chips + token auras), concentration saves prompt themselves, timed effects
  count down, and an encounter-difficulty meter reads the fight at a glance. One tap of
  **combat focus** hides everything but the fight.

- **Clocks** — Countdown/progress clocks, real-time timers, round counters, and in-game
  time-of-day — each with a hidden option for the ones players shouldn't see.

- **Oracle** — On-the-fly generators: characterful NPCs, plus complication / rumor /
  quirk tables for when the party goes somewhere you didn't prep.

- **Lore & Reference** — A home for your world notes, and a beginner-friendly rules
  helper ("describe the situation → get a ruling"). It can also build a prompt to paste
  into Claude for a richer NPC or a tricky ruling — no account, nothing leaves your
  machine.

- **DM Dashboard (Live)** — An at-a-glance card: who's in play, the current scene,
  ticking clocks, clue states, and the loose promises you improvised. One look and you're
  oriented. The panels are customizable.

- **Printable sheets** — One-page DM screen, a player quick-reference, and character
  sheets, so the table leans on a handout instead of pausing to look things up.

- **Session log** — Rolls, reveals, clue flips, and combat all log themselves; flip to
  **★ Key** for just the story beats, and build a one-click session summary.

- **Find anything (Ctrl-K)** — A quick-launcher to jump to any tab, character, clue, or
  rules entry — or create things — without hunting through menus.

## Systems & scope

Built for D&D 5e but adapts to Pathfinder 2e, OSR, PbtA, generic d20, or homebrew. Pick a
scenario flavor (mystery, heist, dungeon, political, sandbox, horror, war) and it focuses
the tools around it. Runs a single **one-shot** or a full **campaign** — campaigns add a
session timeline ("Previously on…" recaps) and multi-session plot arcs.

## Offline & yours

No account, no internet required, no tracking. Everything saves locally — the desktop app
auto-saves to a real file on your machine and keeps **dated daily backups** you can
restore from. Updates download from this page automatically.

## Still cooking

Very much a work in progress — some things are half-built, some will change. It makes a
backup before updating, but keep anything important backed up too. If I've shared this
with you, I'd genuinely love your feedback.

---

*My own hobby project. See [LICENSE](LICENSE). © 2026 fuchcar.*
