# WinBot
WinBot is a Discord bot designed specifically for use in the WinWorld Discord server.

## Usage/Build instructions
1. Clone the repository: ``https://github.com/pinksub/WinBot.git`` and ensure that you have cloned this branch (windows)
2. Move into the project directory: ``cd WinBot``
3. Build the source code: ``dotnet build -c Release -r win-x64``
4. Change into the build directory: ``cd bin\Release\net6.0\win-x64``
5. Run the bot: ``WinBot``. This will generate a blank configuration file for you.
6. Edit the ``config.json``  file and add your token into the token field, as well as your client ID and log channel if you want one
7. Run the bot once more, as before. Once it has started up (It'll output "Ready" to the terminal), you should be good to go into Discord and use it.

## Post-install instructions
For the level rank cards to work you'll need to install Roboto. Due to some annoyances with System.Drawing you have to install it twice in a way.
Steps:

1. Download the font family https://fonts.google.com/specimen/Roboto
2. Extract Roboto-Regular.ttf into the bot's working directory
3. Install Roboto-Regular.ttf on your system
