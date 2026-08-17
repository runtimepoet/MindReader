<div align="center">

# 🔮 MindReader

**A tiny web app that reads your mind — or at least pretends to.**

[![License: MIT](https://img.shields.io/badge/License-MIT-39d353?style=flat-square)](LICENSE)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-none-0d1117?style=flat-square)

</div>

## What is this?

MindReader is a classic math-trick toy: think of a number, follow a few
steps, and the app "guesses" your result. Every time. It's not magic —
just arithmetic dressed up in a nice UI.

## How it works

1. You pick a number and do some simple operations on it.
2. The operations always collapse to a single known outcome.
3. The app reveals that outcome with a dramatic flourish. 🎩

## Run it

No build step, no dependencies — it's plain HTML/CSS/JS:

```bash
git clone https://github.com/runtimepoet/MindReader.git
cd MindReader
# open index.html in your browser, or serve it:
python -m http.server 8000
```

## Tech

- Vanilla JavaScript (zero frameworks)
- Roboto typeface, hand-rolled CSS variables
- ~300 KB total

## License

MIT — see [LICENSE](LICENSE).
