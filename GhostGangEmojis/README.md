# GhostGangEmojis

This project integrates a collection of emojis into a Minecraft resource pack, allowing users to replace in-game symbols with custom emojis. The emojis are sourced from the "Ghost Gang Scrapped" folder and are intended for use in conjunction with Discord chat and DiscordSRV.

## Project Structure

- **README.md**: Documentation for the project.
- **Ghost Gang Scrapped**: Contains the original emoji files and stickers.
  - **Emojis_Ghost_Gang__sfw__wholesome__aesthetic__make_friends.zip**: A compressed file containing emojis and stickers.
  - **Emojis**: Directory with emoji files in PNG and GIF formats (e.g., AdminAbooz0.png, AdminBan0.gif, Alert0.gif, etc.).
  - **Stickers**: Intended for sticker files.
- **Unzipped**: Contains the unpacked resource pack.
  - **Twemoji Visibility 1.4.6**: The resource pack directory.
    - **pack.mcmeta**: Metadata for the resource pack.
    - **pack.png**: Icon for the resource pack.
    - **assets**: Directory containing the resource pack assets.
      - **minecraft**: Contains font and texture files.
      - **twemoji**: Directory for Twemoji assets, including font definitions, language files, symbol tabs, and symbols.

## Importing Emojis

To import the 600 emojis into the resource pack:

1. Move the emoji files (PNG and GIF) from the `Ghost Gang Scrapped/Emojis` directory into `Unzipped/Twemoji Visibility 1.4.6/assets/twemoji/font/` or another appropriate directory within the assets folder.
2. Update the relevant symbol files in `Unzipped/Twemoji Visibility 1.4.6/assets/twemoji/symbols/` to include references to the new emoji files, using the format `:EmojiName:` (e.g., `:Alert0:` for Alert0.gif).
3. Ensure that the `pack.mcmeta` file is correctly configured to recognize the new assets.

This setup will allow the emojis to be used in-game, similar to how they function in Discord.