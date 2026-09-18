# week roller

Prompt generator for a one-game-a-week Roblox project.

Every roll pulls a **core** word (mechanic / genre, 64 of them). A **flavor**
word (setting / vibe, 40 of them) fires only on a dice hit — default 40%, adjustable
in 5% steps. A miss is a legitimate result: build it plain.

- `no repeats` draws from a shuffled bag, so nothing repeats until the pool empties
- `2 core` rolls two mechanics to mash together
- space / enter rolls, clicking a word copies it
- settings and the last 12 rolls live in localStorage

Single file, no build, no dependencies. Open `index.html`.
