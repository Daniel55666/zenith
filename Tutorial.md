ZENITH
Guide and Installation

Zenith is a browser extension that gives you live coaching while you play on chess.com or lichess.org. It runs a chess engine (Stockfish) entirely on your own device, so nothing is uploaded anywhere and no account is needed. When it is your turn, it shows you the best move to play, the strongest alternatives, and a live evaluation of the position.

This guide covers installation on a desktop computer and the Android phone method (via the Kiwi browser). Android has its own guide in the file ANDROID.md.

---------------------------------------------------------------------------
Part 1 - Installing on Desktop (Chrome or Edge)
---------------------------------------------------------------------------

Step 1: Unzip the "dist" folder that contains these files. If you only have the "dist.zip" file, right click it and choose Extract All.

Step 2: Open your browser and go to chrome://extensions (for the Edge browser it is edge://extensions).

Step 3: Turn on "Developer mode". This switch is in the top right corner of that page.

Step 4: Click the "Load unpacked" button and select the "dist" folder you unzipped in Step 1.

Step 5: The extension is now installed. Make sure it is switched on.

---------------------------------------------------------------------------
Part 2 - How to Use It
---------------------------------------------------------------------------

Step 1: Start a game on chess.com or lichess.org. It works with live games and with the analysis board.

Step 2: Wait until it is your turn. The assistant will then show:
   - a green arrow, which is the best move,
   - red arrows, which are good alternative moves,
   - the evaluation in the small panel on the right (a number score or "mate in X"),
   - a list of the top moves and the line that follows them.
If you turned on "Show opponent threats", it will also tint the squares that your opponent currently attacks, so you can avoid moving your pieces there.

Step 3: Your own color (white or black) is detected automatically by looking at which side of the board is at the bottom. If you ever need to force it, you can choose White or Black manually in the extension popup.

---------------------------------------------------------------------------
Part 3 - Settings
---------------------------------------------------------------------------

Open the extension by clicking its icon in the browser toolbar and choosing Zenith. Each site keeps its own settings, so what you set for chess.com does not affect lichess and the other way around.

The settings available are:

   Assistant
   The master on/off switch for the whole extension.

   I play as
   Auto is the default and reads the board automatically. You can force White or Black here if you prefer.

   Difficulty
   The playing strength of the coach, from about 600 Elo (very casual) up to 3000 Elo (master). The default is 2000. Lowering this makes the suggestions more forgiving and human-like.

   Alternative moves
   How many red arrows to draw, from 1 to 5. The default is 3.

   Show opponent threats
   Highlights the squares your opponent controls.

To edit a site's settings, simply open the popup while you are on that site.

---------------------------------------------------------------------------
Part 4 - Android (Kiwi Browser)
---------------------------------------------------------------------------

iOS does not allow third party browser extensions, so Android is the only realistic mobile option. It works through the Kiwi browser.

For the full setup, read the file ANDROID.md in this folder. In short: install the Kiwi browser from the Play Store, load this extension into it, then open chess.com or lichess. The assistant automatically uses a built in version of the engine so it works on the phone without needing the desktop background piece.

---------------------------------------------------------------------------
Part 5 - Tips and Troubleshooting
---------------------------------------------------------------------------

   - After enabling the extension or changing major settings, reload the game page once so everything picks up correctly.
   - The arrows appear after a short pause so the suggestion feels like natural thinking time. This is intentional.
   - If the panel ever says "Engine unavailable - reload page", just reload the game page and the engine will start again.
   - Even at low difficulty the suggestions are sensible, but they get noticeably sharper as you raise the difficulty slider.

If you have any questions or problems, message salzloskittelbanana on Discord.