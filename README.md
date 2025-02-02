# ultraplayer-music
config files (and music) for ultraplayer

**The music files will only be supplied in cases like ultrakill where you can't find the correct files anywhere else.**  
**I'll include a link to wherever you can find the correct files if they aren't in this repo.**

You can download only a specific game music by following these steps:
```bash
git clone --no-checkout https://github.com/cracktorio/ultraplayer-music.git
cd ultraplayer-music
git sparse-checkout init --cone
git sparse-checkout set <game name>
git checkout
```
The `<game name>` should be replaced for the name of the game's folder in this repository.
