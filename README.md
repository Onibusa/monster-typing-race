# 🐲 Monster Typing Race 🏁

A friendly typing game for kids (ages ~8–10). Type the words to make your monster
run across the screen and beat the other monsters to the finish line!

It's a **single file** (`index.html`) with **no internet needed** — just open it and play.

---

## ▶️ How to play

1. Download `index.html` (see "Getting it to your kid" below).
2. **Double-click `index.html`** — it opens in your web browser (Chrome, Edge, etc.).
3. Type your name, pick a monster with **🎲 New monster**, then choose how to play.

### Ways to play
| Mode | What it does |
| --- | --- |
| 🖐️ **Tutorial** | Learn where your fingers go. The keyboard lights up the next key and tells you which finger to use. Great for beginners — start here! |
| 🐣 **Easy** | Short words and one slow monster. Shows a finger hint for each letter. |
| ⭐ **Medium** | Everyday words and two racers to beat. |
| 🔥 **Hard** | Long words, capital letters, and three speedy monsters. |

### Good to know
- **You only need the keyboard** — type the word shown in the middle. Correct letters turn green.
- Capital letters are forgiving: typing `saturday` works for `Saturday`.
- A wrong key just buzzes gently and shakes — no penalty, just try the right key.
- Best speeds (words-per-minute) are saved on that computer/browser between plays.
- 🔊 button mutes/unmutes the sounds.

---

## 👨‍👩‍👧 Getting it to your kid

This project lives in a **private** GitHub repo (only people you invite can see it).
There's no website to visit — she just needs the `index.html` file on her computer.
Two easy ways:

**A) Send her the file (simplest).**
Download `index.html` from this repo (open the file on GitHub → the **⬇ Download raw file**
button) and send it to her however you like (email attachment, USB stick, shared drive,
messaging app). She saves it and double-clicks it. Done — it works offline forever.

**B) Give her access to the repo.**
On GitHub: **Settings → Collaborators → Add people**, and invite her GitHub account.
She then opens the repo, clicks **Code → Download ZIP**, unzips it, and double-clicks
`index.html`.

> 💡 Because everything is in one file, you can also just keep a copy on her computer's
> Desktop and make a shortcut to it.

---

## 🛠️ For grown-ups: the technical bits

- **Self-contained:** all HTML, CSS, and JavaScript are in `index.html`. No build step,
  no installs, no dependencies, no network calls. Monster art is inline SVG; sounds use
  the Web Audio API; nothing is downloaded.
- **Private & safe:** it collects no data and sends nothing anywhere. "Best speed" is
  stored only in the local browser (`localStorage`).
- **Edit the words:** open `index.html` in any text editor and find the `WORDS` object
  (`easy` / `medium` / `hard` lists) to add her favourite words. The finger-placement
  lessons are in the `LESSONS` array just below it.

Enjoy the races! 🎉
