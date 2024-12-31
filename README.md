# blinx-igt

`blinx-igt` is patch for Blinx: The Time Sweeper that primarily allows for displaying a timer in-game for speedrunning purposes. It also comes with some nifty additions, such as enabling or limiting [FDM](#fdm) for all controllers and toggles for making camera movement non-inverted.

## Supported Versions
`blinx-igt` supports both Original Release and Platinum Hits versions of Blinx: The Time Sweeper. If your game executable (`default.xbe`) matches any of the below hashes, it's supported:

| Name             | MD5                                | Download                                                                                    |
|------------------|------------------------------------|---------------------------------------------------------------------------------------------|
| Original Release | `9b066d046469935de106841c03dc0b50` | [Link](https://github.com/itsybitsypixel/blinx-igt/releases/latest/download/US_v1.0_OR.bps) |
| Platinum Hits    | `f3dce4912ad4767a4e4173c27cc6adf0` | [Link](https://github.com/itsybitsypixel/blinx-igt/releases/latest/download/US_v1.0_PH.bps) |

## Apply Patch
You can use any program that supports patching with .BPS files, but I recommend using Marc Robledo's [website](https://www.marcrobledo.com/RomPatcher.js/). If you get a mismatched checksum, double check that you've downloaded the right patch version and that your executable is [supported](#supported-versions).

## FDM
FDM (Full Diagonal Movement) is a technique in Blinx: The Time Sweeper that allows for faster movement if the movement stick is held diagonally, since the game doesn't normalize player input. The increase is based on what controller your using and since most controllers' shells limit how much the stick can be moved this isn't really an issue, but there's still fluctuations between controllers and modifying your controller to allow for more diagonal movement is a viable way to get an advantage.

## Thanks
Big thanks to the Blinx Corps Discord and the speedrunners there who have helped this reach v1.0; a lovely bunch of people! A special thanks to Miku_ds who has playtested `blinx-igt` throughout development!
