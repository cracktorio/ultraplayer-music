# ultraplayer-music
config files (and music) for ultraplayer

You can download only a specific game music by following these steps:
```bash
git clone --no-checkout https://github.com/cracktorio/ultraplayer-music.git
cd ultraplayer-music
git sparse-checkout init --cone
git sparse-checkout set <game name>
git checkout
```
The `<game name>` should be replaced for the name of the game's folder in this repository.
