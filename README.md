# Xbox Rich Presence

*Note: Discord already haves an integrated presence for Xbox Live, but if you want to show more information about what you are playing on Xbox Live u can use this*
## This Rich Presence contains:
1. Game/app name
2. Game/app image (not all games/apps haves an image, you can add images by [contributing](https://github.com/MrCoolAndroid/Xbox-Rich-Presence-Discord#contribute))
3. Timestamp
4. Device name (Xbox One, Xbox 360, etc) and image
5. Xbox Live Rich Presence (if game/app supports it)

*Note: Android and iOS has been removed for now because the rich presence "mixes" with the actual rich presence, please avoid playing on multiple devices while i try to make a device selector or something like that*

## Example
![logo](https://github.com/MrCoolAndroid/Xbox-Rich-Presence-Discord/raw/main/Example2.png)


## Installation
1. Download latest release and install it following instructions on the setup

2. Go to [OpenXBL](https://xbl.io) and login with your Xbox Live account and you will get an API key, save it on a .txt file

3. Open the app and insert your Gamertag and API key

4. Press Start!


## To-Do list
- [ ] Show Xbox Live party
- [ ] Multi-language Rich Presence
- [x] GUI App
- [x] Database for games
- [x] Cool animations and effects
- [ ] Device selector

## Contribute
Wanna contribute on adding games with pictures and backgrounds? Now you can! Just do a pull request editing the [Games List.json](https://github.com/MrCoolAndroid/Xbox-Rich-Presence-Discord/blob/main/Games%20List.json) file!
- "titlename" should have the original name of the game that shows on Xbox, remove any Copyright or Trademark symbols
- Images on "titleicon" should be 1024x1024, and "titlebackground" can be any size but choose one that fits on the app correctly
- "titleimage" is a Discord parameter, give it any name or the game name, i will edit it after the pull request

## Contributors
People that helped me creating the app!
- Klaudex17 (Games pictures and design)
- J_Felipe (Ideas for the app)

And many people on Discord!

If you're not seeing any image while playing your game, please contact me on Discord *MrCoolAndroid#2118* and i will add an image to your game!

*Note: Not all games haves an image as Discord only can storage up to 300 images, i will be updating the database with more images*
