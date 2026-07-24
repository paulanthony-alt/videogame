# 🦋 MOLT — a pocket roguelike for road trips

A single-file, offline browser game built for the car. Open `index.html` on any
phone or laptop and play — no install, no server, no account.

**[▶ Just open `index.html`](index.html)**

## Why it's a road-trip game
- **Short runs** — a full crawl is ~10–15 minutes.
- **Saves after every action** — hit a tunnel, lose signal, or your phone dies?
  Reopen the page and tap **Continue** — you resume mid-fight, nothing lost.
- **No twitchy aiming, no timing pressure** — combat is fully turn-based. A car
  bump can never get you killed.
- **Works offline** — everything is in one HTML file. Load it once (or save it to
  your home screen) and it plays with zero connection.
- **Mute in one tap** — considerate of sleeping passengers.

## How it plays
You're a small beast crawling deeper through a burrow, one room at a time.

**Combat** — each turn the enemy *telegraphs* its next move. Read it, then tap:
- ⚔️ **Strike** — deal damage, but you're exposed
- 🛡️ **Guard** — soak the hit, great against big red telegraphs
- 💨 **Dodge** — gamble to avoid the attack entirely

That's the whole loop: read the tell, pick your tap.

**The Molt** — every few rooms you reach a molt chamber and are offered **4 new
forms — you keep 2.** Trade claws for wings, armor for speed, grow venom fangs or
a second heart. This is your run's one big decision, and it's where builds are
made: bleed, poison, thorns, lifesteal, crit, frenzy, and much more.

**Rarities** — the 100+ forms span five tiers: **Common → Uncommon → Rare →
Epic → Legendary**. The deeper you descend, the better the odds of the good
stuff. Legendaries are run-defining — revive on death, an enemy that skips turns,
every other passive counting as one copy stronger. Duplicate forms **stack** — a
second copy doubles the effect.

Your shell only holds **15 forms**, so a run isn't about hoarding everything —
once you're full, molting means **shedding**: you pick which forms to release to
take the new ones. Every molt stays a real decision, and no build grows without
limit.

**Descending** — each of the named zones is deadlier than the last: more beasts,
poison, life-drain, enrage, and bosses that can end a run. Fall in battle and the
run ends — but you keep how deep you reached. Then you crawl again, a little wiser.

## Tech
Plain HTML/CSS/JS in one file. State auto-saves to `localStorage`. Audio is a
tiny WebAudio synth (no asset files). No dependencies, no build step.
