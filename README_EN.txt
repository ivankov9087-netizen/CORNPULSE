CORNPULSE Windows x64 Edition
Created by Fields Food

This is an offline vegetable zombie FPS made for viewers of my channel.
It combines movement mechanics such as portals, grappling, and wall-running
with mysterious elemental reactions and roguelike upgrades as you fight hordes of enemies.

(A note)
CORNPULSE is an original FPS inspired by Splitgate's portal combat and EMPULSE's movement.
It is not affiliated with 1047 Games and has not been approved, endorsed, or sponsored by the company.
No code, game data, or assets from Splitgate or EMPULSE have been used or repurposed.
If 1047 Games makes any requests regarding this game, I will respect their wishes and respond promptly.

[1. How to Launch]
1) Right-click the downloaded ZIP file and select "Extract All...".
2) Launch "CORNPULSE.exe" inside the extracted folder.
3) Select "DEPLOY" on the title screen to start the main mode.

Do not launch the game directly from inside the ZIP or move only the EXE to another location.
The bundled DLLs, resources, locales, and other files are required for the game to run.
This release is for 64-bit Windows. A keyboard and mouse are required.
Gamepads are not supported.

Gamepad support is possible, but I am not used to playing with a gamepad,
so I cannot properly fine-tune the controls.
If any game developers who are good with gamepads could help me out, please do! (sob)

[2. Uninstalling]
This game does not require installation.
Close the game, then delete the entire extracted game folder.
Settings, suspended-run data, caches, and other data remain in %APPDATA%\CORNPULSE-Native-DX11.
Deleting that folder will also remove the game's settings and saved data.
No registry changes are required to uninstall the game.

[3. If a SmartScreen Warning Appears]
The CORNPULSE.exe in this release is unsigned. Digital signing costs money.
I don't have the money for that. Sorry.

Windows SmartScreen may display "Windows protected your PC"
for unsigned apps with little download history.
This message alone does not mean that a virus has been detected.

Make sure you downloaded the game from a distribution link shared in Fields Food's videos or posts.
If you choose to launch it, follow these steps on the warning screen:

1) Click "More info".
2) Check that the app name is "CORNPULSE.exe".
   Since it is unsigned, the publisher will be shown as "Unknown publisher".
3) Click "Run anyway".

You do not need to disable SmartScreen or your antivirus software.
The warning may appear again depending on your environment or after an update.

Checks performed:
Microsoft Defender found no threats when I scanned the game on my own system.
GPT-6 Astra also performed a static review of the code and distribution files,
and no malicious code was found within the scope examined.
Even so, please run the game at your own risk.

[4. Basic Controls (Default Settings)]
You can change key bindings and mouse sensitivity in the in-game settings.
For detailed instructions, see "MANUAL / HOW TO PLAY" on the title screen.
To exit, use the window's close button or the in-game "QUIT GAME" option.

[5. Suspending, Resuming, and PASSWORD]
To stop playing and resume another day, select "SUSPEND" on the death screen.
After restarting the game, you can continue using the resume button on the title screen.
Simply closing the window or selecting "RETURN TO TITLE"
does not save your current RUN as a suspended run.

I also recommend saving the PASSWORD displayed after suspending a run in Notepad or a similar app.
Paste it into "PASSWORD" on the title screen to resume on another PC.
The PASSWORD on the run completion screen lets you carry your card Ranks and COINS into the next playthrough.

Location of settings, suspended-run data, and other saved data:
%APPDATA%\CORNPULSE-Native-DX11

This save folder remains even if you delete the game.
If you also want to delete the save folder, make a note of any PASSWORDs you need first.

[6. Supported Play Conditions]
Proper operation is not guaranteed from the third playthrough onward
or with extreme upgrade levels such as RANK 100.
* Still, unlimited upgrades are fun, so I implemented them without a cap! (lol)
Increasing upgrades and effects may cause slowdowns or other issues.
The in-game "GENERATED MAP MODE" is experimental.

[7. Streaming, Video Uploads, and Redistribution]
You may livestream gameplay and upload gameplay videos. This is a free game, not a commercial product.
Please do not redistribute, repost, or sell CORNPULSE itself or the creator's original code and assets.
When sharing the game with others, please direct them to the official distribution page provided by the creator.

However, bundled third-party software and CC0 assets are covered by their respective licenses.
The usage terms above do not restrict the reuse or redistribution rights granted by those licenses.
For third-party software license notices, see the bundled "LICENSE.electron.txt"
and "LICENSES.chromium.html" files.

[8. Reporting Bugs]
Please report bugs in the comments section of the game release video, which I plan to publish later.
Please include:
- The game version
- What was happening when the issue occurred and what you did immediately beforehand
- Your Windows version, CPU, GPU, and RAM

[9. A Few Personal Thoughts]
CORNPULSE is my first solo game project, which began with the thought,
"I'd like to try making an FPS that I want to play."
(Although it feels presumptuous to call this "game development"...)

As someone who introduces games to an audience, I also wanted to experience for myself
what AI-assisted development can do and where the difficulties lie.

I made extensive use of AI to implement the game's code,
and most of the code was generated by AI.
I built the prototype through what is commonly called "vibe coding,"
then played it myself and decided what changes to make as development progressed.

The starting point was to try combining the manipulation of space through portals
with high-speed movement from two games I love: Splitgate and EMPULSE.

Actually making it also revealed just how many difficulties there were.
Portal-related systems were much more complex than I had imagined.
Simply implementing them could easily increase the rendering workload,
and portals placed on the floor caused all sorts of problems with the camera, movement, collision detection, and more.

The same was true of movement. Merely making it possible to move quickly
was not enough to capture the satisfying feeling of continuously chaining momentum together in EMPULSE.
I learned that small changes to speed, acceleration, air control, and how momentum is preserved after landing
can make a huge difference to how the controls feel.

AI can help turn complex systems into something functional in a short time,
but making them satisfying to play still took careful tuning and trial and error.

I realized that the satisfying feel I had taken for granted as a player was anything but automatic.
It gave me a renewed appreciation for how carefully Splitgate and EMPULSE were crafted,
including all the work that players never see.

Looking back at the entire process of making CORNPULSE,
my personal impression is that it was about 70% AI and 30% human work.

AI handled most of the coding.
I commissioned a professional illustrator to create the artwork of Iwana-chan,
and used free CC0 assets for the 3D models.
Some textures were generated with GPT,
and some voice recordings were provided by someone with voice-acting experience.
The music was made using Suno Premier, then rebuilt and finished in Ableton Live.

I handled the level design, overall game direction,
decisions about which features to include or leave out, balance adjustments, and playtesting.

As development continued, new ways to play kept emerging that I had not originally anticipated:
making huge leaps by combining portals and grappling,
luring vegetables into falling through portals,
or carrying the speed gained from Speed Paint through a portal to launch yourself out at high speed.
I decided to build on those discoveries by adding a system I call "portal elemental reactions."

By keeping those unexpected discoveries and building on the parts that were fun,
I feel that CORNPULSE gradually began to develop its own style of play.
* As I keep saying, I am well aware that it feels presumptuous to call this "game development."

I have not suddenly become someone who can write a program from scratch.
Even so, getting a small taste of making something myself
helped me understand difficulties that I could never have seen just by playing games.
It made me want to show even greater respect for the game developers
who spend enormous amounts of time and effort creating the games that entertain us.

My first goal was to make something I would want to play myself.
This is a just-for-fun FPS made for a video and for my viewers to play.
I hope fans of high-speed shooters will enjoy it.

Fields Food: The original 1047 Games content creator (self-proclaimed)
I'm a video creator, not a game developer.
https://www.youtube.com/channel/UCO9s2_k1KMrGFU9SdpybE3Q
