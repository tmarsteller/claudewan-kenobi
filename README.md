# claudewan-kenobi

A Claude Code skill that responds in full Star Wars prequel trilogy meme character.

---

## What it does

Activates when you drop a prequel quote, reference, or trigger phrase. Claude responds as Obi-Wan Kenobi (or whoever the moment calls for) while still completing whatever you actually asked it to do.

The skill covers 120+ call-and-response triggers across four tiers:

| Tier | Description | Examples |
|---|---|---|
| 1 | Sacred Texts | *Hello there*, *Execute Order 66*, *I am the Senate* |
| 2 | Council Chambers | *A surprise to be sure*, *Impossible, perhaps the archives are incomplete*, *We shall watch your career with great interest* |
| 3 | Deep Cuts | *Fear leads to anger*, *From my point of view*, *Do or do not* |
| 4 | Senate Archives | Sheev posting, Commander Cody's moment, Darth Jar Jar theory, *Somehow Palpatine returned* |

---

## Triggers

Any of these will activate the skill:

- Prequel quotes: `hello there`, `do it`, `execute order 66`, `I am the Senate`, `I have the high ground`, `I don't like sand`, `did you ever hear the tragedy of Darth Plagueis the Wise`, `you were the chosen one`, `so this is how liberty dies`
- References: the Senate, the high ground, sand, Order 66, the Jedi Council, the chosen one, Darth Plagueis
- Asking to speak in Star Wars / prequel / Jedi mode
- Subtle drops: `a surprise to be sure`, `possibly`, `so uncivilized`, `good soldiers follow orders`, `I love democracy`

When in doubt, it triggers. That's the point.

---

## Example interactions

```
User: hello there. why is this query running slow?
AI:   General Kenobi! You are a bold one.
      [analyzes query, finds missing index]
      The Separatists have been routed. You're missing an index on user_id.
      Another happy landing.
```

```
User: execute order 66 on all the console.log statements
AI:   It will be done, my Lord. Good soldiers follow orders.
      [removes all console.log calls]
      *Anakin's Betrayal plays softly.* It is done.
```

```
User: I can't find that config file anywhere
AI:   Impossible. Perhaps the archives are incomplete.
      [searches]
      Well, whaddya know. Three folders deep, with a typo in the name.
```

```
User: somehow this bug came back
AI:   Somehow Palpatine returned.
      ...We don't talk about that. Let's fix it. Again.
```

---

## Installation

From within Claude Code, add this repo as a marketplace and install the plugin:

```
/plugin marketplace add tmarsteller/claudewan-kenobi
/plugin install claudewan-kenobi@claudewan-kenobi
```

Then run `/reload-plugins` to activate it.

---

## Related

- [structured-vibe-accounting](https://github.com/tmarsteller/structured-vibe-accounting) — a more serious skill, for when the fun is not beginning
