

# Discord.py Bot

This is a customizable Discord bot built using Discord.py, designed to handle various server management tasks, music playback, and more. The bot includes features for moderation, role management, giveaways, and integration with external APIs like YouTube.

## Features

### General
- **Ping**: Check the bot's latency.
- **Server Stats**: Display server information such as owner, region, member count, and server ID.
- **Instructions**: Send instructions to the user via direct message.

### Moderation
- **Clear Messages**: Delete a specified number of messages.
- **Kick/Ban/Unban**: Kick, ban, or unban users.
- **Mute/Unmute**: Mute or unmute users.
- **Profanity Filter**: Automatically delete messages containing profane words and warn the user.

### Role Management
- **Assign/Remove Roles**: Assign or remove roles from users.
- **Reaction Roles**: Assign roles based on reactions to messages.

### Giveaways
- **Host Giveaways**: Create and manage giveaways with a specified prize and duration.

### Announcements
- **Make Announcements**: Post announcements in a specified channel.

### External API Integration
- **YouTube Trending**: Fetch and display trending YouTube videos for a specified region.

### Music Playback (using Wavelink)
- **Play**: Play music from YouTube.
- **Pause/Resume/Stop**: Control music playback.
- **Loop**: Loop the currently playing track.
- **Queue**: Display the current music queue.

## Setup

1. **Clone the repository:**
    ```sh
    git clone https://github.com/StarlitDreams/Discord.py-bot.git
    cd Discord.py-bot
    ```

2. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Configure the bot:**
    - Create a `.env` file in the root directory and add your Discord bot token:
      ```
      DISCORD_TOKEN=your_discord_bot_token
      ```
    - Set up your Google API key for YouTube API in the code where necessary.

4. **Run the bot:**
    ```sh
    python bot.py
    ```

## Usage

Invite the bot to your Discord server using the OAuth2 URL generated from the Discord Developer Portal. Once added, use the command prefix `~` to interact with the bot.

### Example Commands

- `~ping`: Check the bot's latency.
- `~serverstats`: Display server information.
- `~clear [amount]`: Clear the specified number of messages.
- `~kick [@user] [reason]`: Kick a user with an optional reason.
- `~play [song name or URL]`: Play a song from YouTube.
- `~giveaway`: Start a giveaway by answering a few prompts.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please open an issue on the GitHub repository.

---

Much luv <3
