# ePSXe

This is my personal setup for ePSXe. 

## ePSXe CLI options

- `-adsrtrick` =>  Returns a random ADSR value. 
- `-analog` => Enables Analog Pad Emulation.
- `-anamous` => Enables Analog Pad Emulation via Mouse.
- `-bios <file>` => Loads the specified PlayStation BIOS file.
- `-c` => Enables the Dynarec core.
- `-cddmairq3` => Enables CD-ROM IRQ3 in DMA.
- `-cdfast` => Enables Fast CD-ROM Emulation.
- `-cdrom <letter>` => Selects a CD-ROM Drive Letter.
- `-cdslow` => Enables Slow CD-ROM Emulation.
- `-cdtiming` => Enables Accurate CD-ROM Timing.
- `-debug` => Enables Debugging (only in betas!).
- `-dmairqclear` => Forces DMA IRQ to always be cleared.
- `-f` => Disables BIOS Logo. (Fast Boot)
- `-ff9pal` => Enables Final Fantasy IX PAL cheat.
- `-fl` => Enables the internal framelimiter.**
- `-forcepad` => Forces SIO IRQ to always be enabled.
- `-forcespu` => Forces SPU IRQ to always be enabled.
- `-gun` => Enables Namco Gun Emulation.**
- `-h` => Displays some (not all) command-line switches. (???)
- `-hdev` => Displays a list of debug options. (???)
- `-help` => Displays some (not all) command-line switches.(???)
- `-i` => Loads the Interpreter core.*
- `-legaia` => Enables Legend of Legaia cheat.
- `-lib` => Loads libpsx.exe. (Unusable)
- `-loadbin <file>` => Loads a specified ISO image file.
- `-loadcheat <file>` => Loads a specified .cht file.
- `-loadfake` => Loads a fake file.****
- `-loadmemc0 <file>` => Loads a specified memory card file in the first slot (0).
- `-loadmemc1 <file>` => Loads a specified memory card file in the second slot (1).
- `-mouse` => Enables Mouse Emulation.
- `-noaudiocd` => Disables CDDA.
- `-noauto` => Disables automatically applied patches.
- `-nocd` => Disables CD-ROM Emulation.
- `-nocdcmd11` => Disables CD-ROM command 11. (Unusable)
- `-nocdstatus` => Changes some CD-ROM status outputs.
- `-nocdrtstatus` => Disables CD-ROM RT status. (Unusable)
- `-nogui` => Runs ePSXe without the GUI.
- `-nolog` => Disables log files.
- `-nomdec` => Disables MDEC.
- `-nomdectiming` => Disables MDEC Timing.
- `-nomemcard` => Disables Memory Card Emulation.
- `-noseekinxa` => Disables seeking during XA playback.
- `-nosound` => Disables Sound Emulation.
- `-p <num>` => Adds penalty cycles to memory access.*****
- `-paddual` => Enables a pad workaround* (Unusable)
- `-savefake <file>` => Saves a fake file.****
- `-ssv0` => Creates savestates compatible with

### ePSXe v1.4.0

- `-v` => Shows the current version of ePSXe
- `-xaread` => Enables XA Read.
- `-xasound` => Enables XA Sound Emulation.
- `-[psx exe]` => Runs the specified PSX Executable (can be a .pll, zipped)
- `-fastboot` => Disables BIOS Logo. (Fast Boot)
- `-slowboot` => Enables BIOS Logo. (Slow Boot)

> Reference: https://www.gameex.info/forums/topic/19-all-epsxe-command-line-options-attached/

# Adding game to Steam as non-steam games

1. Open Steam and click **ADD A GAME** > **Add a Non-Steam Game**
2. Browse to your ePSXe folder and select `ePSXe.exe`
3. Right click on ePSXe game added to your game list
4. Click **Properties...**
5. Click **Set Lauch Options...**
6. Set `-loadbin <PATH_TO_BIN> -fastboot -nogui`
7. Customize your icons and background images for better looking
8. Hit play and have fun!