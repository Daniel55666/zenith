ZENITH ON ANDROID
Setup Guide

This guide explains how to run Zenith on an Android phone. The desktop version (see Tutorial.md) works in a normal Chrome or Edge browser. On a phone, iOS does not allow third party browser extensions at all, so Android is the only practical mobile option, and it is done through the Kiwi browser.

---------------------------------------------------------------------------
Part 1 - The Short Version
---------------------------------------------------------------------------

Step 1: Install the Kiwi browser from the Google Play Store.

Step 2: Put the "dist" extension folder on your phone. The easiest way is to copy the unzipped folder into the Download folder. If you only have the "distfnl.zip" file, extract it on the phone first.

Step 3: Open the Kiwi browser and go to chrome://extensions.

Step 4: Turn on "Developer mode" and tap the "Load from .zip" or "Load unpacked" option, then choose the "distfnl" folder.

Step 5: Open chess.com or lichess in the Kiwi browser and start a game. Coaching arrows should appear once you are on the game screen.

---------------------------------------------------------------------------
Part 2 - Why It Works on Android
---------------------------------------------------------------------------

On a normal desktop browser, the extension runs the chess engine in a hidden "offscreen" page. The Android version of the Chrome engine inside Kiwi does not always support that hidden page or the background service reliably. For this reason, Zenith version 2 can detect when this happens and switches to a built in fallback. In fallback mode it loads the engine directly inside the page as a normal background worker and still calculates on your phone, with nothing sent to the internet. The analysis stays local.

A note on status: this fallback mode is newer than the desktop path and is treated as preview on Android. It works fine for a single game, but a long analysis session will use more battery than the desktop version.

---------------------------------------------------------------------------
Part 3 - Things to Keep in Mind
---------------------------------------------------------------------------

   - When Kiwi asks for permission to read files from your storage, grant it. The browser needs this to load the extension folder.
   - Open the Zenith popup while you are on the site you are playing so the settings apply to the right site (chess.com or lichess).
   - If the arrows do not appear, make sure Android has not closed the Kiwi browser tab in the background. Keep the game tab open and in the foreground.
   - The automatic color detection works the same way as on desktop. You can also pick White or Black manually in the popup if you prefer.

---------------------------------------------------------------------------
Part 4 - Known Limits
---------------------------------------------------------------------------

   - Only the chess.com and lichess.org web versions are supported.
   - The iOS app and the iOS Safari browser cannot run extensions, and there is no known workaround.
