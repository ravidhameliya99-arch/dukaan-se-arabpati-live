# Dukan Se Arabpati – online content

This repository is **public on purpose**: the Dukan Se Arabpati game reads `content/shop.json` from here every time it starts
(through the free jsDelivr CDN, with GitHub as a fallback). It holds only game content — never code, keys or passwords.

What you can change here (edit the file on github.com and "Commit changes"):

- shop labels and badges (for example `RECOMMENDED`, `MOST POPULAR`), sale text and sale dates;
- luxury items (`"luxury"`): names, words, prices, profit bonuses and the big title that opens each collection; new items can be added only with a picture that is already in the game;
- `"app": {"min": <version number>}` — asks every player with an older app to update from Google Play.

Prices that players pay are set only in Google Play Console. Changes reach players within about 12 hours (CDN cache).
Every change is saved in this repository's history, so any old version can be restored.
