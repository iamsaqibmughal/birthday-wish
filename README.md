# 💗 Birthday Surprise for Ayesha — version 2

An interactive birthday world: a live countdown to 5 December, candles to blow out,
a cake to cut, balloons hiding reasons you love her, a photo album, a sealed love
letter, and a fireworks finale with her name in gold script.

## How it works before vs. on the big day

- **Before 5 December** (Pakistan time): she sees the live countdown
  (days : hours : min : sec with 💗 separators) and an "I can't wait 🎀" button.
  Tapping it shows a teasing love popup — "19 days left… you need to wait,
  my love 💗" — with a **different color, message, and animation every tap**.
  The surprise itself is **locked**: she cannot get past this screen.
  The floating background animation also changes every day (hearts, petals,
  snow, butterflies, stars…).
- **On 5 December**: the countdown is replaced by "Happy Birthday! IT'S
  TODAY!! 🎉", confetti bursts, and the button becomes **"Open my surprise 🎁"**
  which unlocks the whole experience.
- **Secret preview**: open the link with `?preview` at the end to get a button
  that opens every screen now.

## Privacy

Her birth year, age, and DOB appear **nowhere** in the page or source code —
only the day + month, for the countdown (counted in Pakistan time, UTC+5).

## Photos

`photos/` contains: `1.jpg` the holding-hands photo, and `2.jpg`–`5.jpg`
four original couple illustrations generated with Canva. Each card shows a
love line below the photo — edit the captions in the config. Replace any
file to swap a photo.

## Personalize

Open `index.html` and find the block marked `💗💗💗 EDIT THIS CONFIG`:

- `reasons` — the balloon messages
- `letter` — write your own words (this matters most!)
- `photos` — the love-line captions
- `TEASE_MSGS` (just below the config) — the teasing popup messages
- `reviewMode` — `true` opens all screens for review; keep `false` to stay locked

## Tips

- Tap 🎵 — it plays a soft music-box "Happy Birthday".
- Designed for her phone; works on desktop too.
