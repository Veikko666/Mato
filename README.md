# Glowworm / Kiiltomato

A one-touch cave flyer for phones, a tribute to the classic **SFCave**.
A glowing worm flies through a dark cave that keeps getting narrower.

- **Hold** the screen → the worm rises
- **Let go** → the worm falls
- On a computer: mouse button, Space or Arrow Up.

## Modes

- **Endless**: a brand-new cave every run.
- **Daily cave**: everyone gets the same cave for the whole day (seeded from the date); it changes at midnight.
  Each mode has its own top 10.
- **Ghost** (menu toggle, daily cave): a pale worm replays your best run of the day through the same cave,
  and an X marks where it crashed.

The cave layout depends only on distance and the seed, never on time or screen size, so the daily cave
is identical on every device.

## Scoring

You score 10 points per second, plus bonuses:

- **Light orbs**: +20, or +40 for the ones hugging a wall.
- **Close calls**: skim a wall or obstacle without touching it for +15.
- **Multiplier**: every 4 orbs or close calls in a row raise it (up to ×5). It applies to everything,
  and it runs out if you go 4 seconds without either.
- **Your furthest**: a light gate marks where your longest run ended, and passing your best score
  mid-run is announced.

The run ends when the worm hits a wall or an obstacle.
The cave changes colour as you go deeper, and the top 10 list is stored in the browser (localStorage).
English by default; switch to Finnish from the menu. All sound, including the calm generative
ambient soundtrack, is synthesized with Web Audio (music and sound can be toggled separately).
The music style is a menu setting: **Calm**, or **Rising**, which adds a beat, hats, an arpeggio and a
faster tempo as the run goes on,
so there are no asset files.

## Playing

Open `index.html` in a browser. It is a single file with no build step, so it can be hosted
as-is, e.g. on GitHub Pages.

---

**Suomeksi:** Pidä sormi näytöllä, niin mato nousee, ja päästä irti, niin se laskee. Väistä luolan
seiniä ja esteitä. Kielen voi vaihtaa valikosta.
