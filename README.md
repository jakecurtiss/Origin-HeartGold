# Origin HeartGold Pokédex

A mobile-first Pokédex built from the supplied Origin HeartGold v4.0.3 Markdown data.

## Features
- 1,440 species/form entries
- Search by Pokémon, ability or dex number
- Filter by type, generation, base/form entries and documented availability
- Tap HP / Atk / Def / SpA / SpD / Spe / BST to sort high-to-low or low-to-high
- Pokémon Showdown Gen 5-style sprites with a PokéAPI fallback
- Tap a Pokémon for evolutions, acquisition, moves, TMs/HMs, tutors and egg moves
- PWA support so the hosted page can be added to an iPhone Home Screen

## Put it on GitHub Pages
1. Create a new public GitHub repository, e.g. `origin-heartgold-pokedex`.
2. Upload every file in this folder to the repository root.
3. In GitHub open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. After GitHub publishes it, open the Pages URL in Safari.
7. On iPhone, tap **Share → Add to Home Screen**.

Sprites are loaded from Pokémon Showdown, with PokéAPI as a fallback. Once viewed, the service worker caches resources for faster repeat visits.
