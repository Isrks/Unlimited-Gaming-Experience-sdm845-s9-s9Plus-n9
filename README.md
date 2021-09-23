# Unlimited-Gaming-Experience-sdm845-s9-s9-n9
Hi, the objective of this module for magisk is to disable the performance restriction due to temperature when starting a game that requires too many resources, such as CoD Mobile, Genshin Impact, PUBG Mobile, etc.
This module can drain a lot of battery in games that require a lot of performance.

Specific features of this module:

 - Disables CPU performance limiter due to temperature.
 - Disable GPU performance limiter due to temperature.
 - Disables automatic brightness reduction due to temperature.
 - Enables the use of all CPU cores without frequency limit for all games (Without the module the games are limited to a frequency of 1056Mhz in the large CPU cores).
 - Enables the use of all cores in all tasks.
 - GPU frequency always at maximum while screen is on (This feature is temporary, I will change it when I find a better way to use the GPU to the maximum in certain tasks).

It is recommended that you uninstall or disable any other module that "claims to remove performance limits due to temperature" as it may not work properly with this module.
It is mandatory that you manually disable the following samsung applications for this module to function properly.

 - Game Launcher (com.samsung.android.game.gamehome)
 - Game Booster (com.samsung.android.game.gametools)
 - Game Optimizing service (com.samsung.android.game.gos)

But if you want you can use my "com.samsung.android.game disabler" module to do it automatically.


If you are going to use my modifications in your projects please give me credits.

In case the module leaves your device in bootloop, to remove it you must enter recovery mode and go to the following address (/ data / adb / modules /) and delete the folder "UnlimitedGamingExperienceByIsrks", after that you can restart and your device will start normally.

I am not responsible for any damage to your device, you, third parties, and any other type of damage, use at your own risk.

Sorry about my English, I used a translator to write this.
