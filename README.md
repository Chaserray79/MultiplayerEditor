# Multiplayer Editor

A multiplayer Geometry Dash mod for building levels with others, made using [enet](https://github.com/lsalzman/enet). This works on 2.2091 and only 2.2091.

----------------------------------------------------------

## Installation
(everyone follows these steps)
1. Install [Geode](https://github.com/geode-sdk/geode/releases/tag/v6.0.0-beta.1) and go through the full setup process.
2. Download the latest release from the [Releases page](https://github.com/Chaserray79/MultiplayerEditor/releases/latest). It should be a `.geode` file.
3. Place the `.geode` file in your `geode/mods` folder.
4. Launch Geometry Dash.

This mod uses **P2P**, we recommend to use [playit.gg](https://playit.gg/).

## Setup
(host follows these next steps)
After install here is how to get it working in game.
1. Whoever is hosting needs to go to [playit.gg](https://playit.gg/) and click download.
2. Once downloaded, follow all of the steps to link your account.
3. When your account is linked and you are on your playit dashboard, click new tunnel.
4. Scroll down and click other software, type in Geometry Dash for the game title and make sure connection type is set to UDP, scroll down and set port to 8080, check the agreement box at the bottom, then hit continue.
5. Scroll down and click continue, set the tunnel name to Geometry Dash, hit continue, click automatic, scroll to the bottom and hit create tunnel.
6. Now scroll to the top and where it says public address of your tunnel, under the box with words.morewords:numbers, there should be something that has all numbers and some dots, something like 012.345.678.910:12345, copy that and send it to everyone who will be joining you.
7. Now in gd, go to the level you want to edit with other people.
8. Open the menu and at the bottom there should be a button that says host session.
9. Make sure the port is set to 8080, set a password if you want one.
10. Once you click host then you are done and tell everyone else to follow the next steps.

(everyone else follows these steps)
1. Once the host tells you to start following these steps, click the blue-purple button in the main menu
2. Copy the numbers the host sent you, they should be something like 012.345.678.910:12345, paste those numbers into the address box (the one on the top).
3. If the host set a password, put that in the password box, otherwise leave it blank.
4. Click join and you should be transported into the level the host is in.

   # Hope this was helpful! If you want to make a yt tut over this credit me and Zyyedev (mainly Zyyedev though all I did was write the tut and make it work in 2.2091, he did literally everything else).
