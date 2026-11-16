# Aristotle, in his own words

A self-contained, installable web app that runs **semantic search over Aristotle's own words**
entirely in your browser — no server. Type a question and get back his most relevant passages
from six public-domain primary works (Nicomachean Ethics, Politics, Poetics, The Categories,
The Athenian Constitution, History of Animals — 3,687 passages).

- **Engine:** [transformers.js](https://github.com/xenova/transformers.js) `all-MiniLM-L6-v2`,
  embeddings computed on first load and cached in IndexedDB; top-8 cosine similarity.
- **Offline-capable PWA:** installable via *Add to Home Screen*; works offline after first visit.

## Run locally
```
python3 -m http.server 8080
# open http://localhost:8080
```

## Live site
Enabled via GitHub Pages → https://jafa106.github.io/Aristotle/

*Texts are public-domain English translations from Project Gutenberg.*
