# Server Nuker

Server Nuker is a Discord self-bot that performs destructive actions on Discord servers. It is designed for educational and testing purposes only. **Do not use this bot on any server where you do not have explicit permission. Unauthorized use of this bot is against Discord's Terms of Service and may result in your account being banned.**

## Features

- **Kick All Members**: Kicks all members from a server.
- **Ban All Members**: Bans all members from a server.
- **Rename All Members**: Renames all members in a server.
- **Message All Members**: Sends a predefined message to all members in a server.
- **Destroy Server**: Deletes channels, remakes new ones, deletes roles, bans and kicks members, and wipes emojis.
- **Ping**: Gives the ping to the client (in milliseconds).
- **User Info**: Provides information about a specified user.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/quehole/Server-Nuker.git
   cd Server-Nuker
   ```

2. **Install Dependencies**

   Ensure you have Node.js installed, then install the required packages:

   ```bash
   npm install discord.js-selfbot-v13 chalk figlet
   ```

3. **Setup**

   - Create a `config.js` file in the project directory with your bot token and prefix:

     ```js
     module.exports = {
       prefix: '.',  // Command prefix
       token: 'YOUR BOT TOKEN'  // Replace with your Discord bot token
     };
     ```

4. **Run the Bot**

   ```bash
   node index.js
   ```

## Usage

1. **Commands**:

   - `.secret`: Displays a list of available commands.
   - `.kall`: Kicks every member in the server.
   - `.ball`: Bans every member in the server.
   - `.rall <new_name>`: Renames every member in the server.
   - `.mall`: Sends a message to every member in the server.
   - `.destroy`: Deletes channels, creates new ones, deletes roles, bans and kicks members, and wipes emojis.
   - `.ping`: Displays the bot's ping.
   - `.info [@user]`: Provides information about a user.

## Important Notes

- **Ethical Use**: This bot is intended for educational purposes only. Misuse or unauthorized use may result in severe consequences, including permanent bans from Discord.
- **Token Security**: Keep your bot token secure and never share it. If exposed, regenerate your token immediately.
- **Discord TOS**: Using this bot in a manner that violates Discord’s [Terms of Service](https://discord.com/terms) is strictly prohibited.

## Author

Created by [quehole](https://github.com/quehole). For further assistance or questions, please refer to the GitHub repository.
