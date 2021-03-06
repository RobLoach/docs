# 3DO (4DO)

## Background

4DO is an open-source, low-level emulator for the 3DO Game Console based on the FreeDO source code.

Author(s): JohnnyDude|FreeDO team

## Contribute to this documentation

In order to propose improvements to this document, [visit it's corresponding source page on github](https://github.com/libretro/docs/tree/master/docs/library/4DO.md). Changes are proposed using "Pull Requests."

## License

Non-commercial

## Extensions

iso|cue

## BIOS

|   Filename   |      Description                |              md5sum              |
|:------------:|:-------------------------------:|:--------------------------------:|
| panafz10.bin | Panasonic FZ-10 BIOS - Required | 51f2f43ae2f3508a14d9f56597e2d3ce |

## Features

| Saves | States      | Rewind | Netplay | RetroAchievements | RetroArch Cheats | Native Cheats |
|:-----:|:-----------:|:------:|:-------:|:-----------------:|:----------------:|:-------------:|
|  yes  |     yes     |   yes  |   yes   |         no        |   no             | no            |

| Controllers     | Rumble | Sensors | Camera | Location | Subsystem     |
|:---------------:|:------:|:-------:|:------:|:--------:|:-------------:|
|        no       |   no   |    no   |   no   |    no    |       no      |

## Options

The 4DO core has the following options that can be tweaked from the core options menu. The default setting is bolded.

- **High Resolution (restart)** (**Off**/On): Doubles internal resolution.

??? note "*Disabled*"
    ![high_resolution_disabled](images/Cores/4DO/high_resolution_disabled.png)

??? note "*Enabled*"
    ![high_resolution_enabled](images/Cores/4DO/high_resolution_enabled.png)

## Controllers

The 4DO core supports one controller setting(s):

* RetroPad

![4do_retropad](images/Controllers/4do_retropad.png)

| 4DO           | [RetroPad](RetroPad)                                           |
|---------------|----------------------------------------------------------------|
| B             | ![RetroPad_B](images/RetroPad/Retro_B_Round.png)               |
| A             | ![RetroPad_Y](images/RetroPad/Retro_Y_Round.png)               |
| X (Stop)      |  ![RetroPad_Select](images/RetroPad/Retro_Select.png)          |
| P (Play/Pause | ![RetroPad_Start](images/RetroPad/Retro_Start.png)             |
| D-pad         |  ![RetroPad_Dpad](images/RetroPad/Retro_Dpad.png)              |
| C             | ![RetroPad_A](images/RetroPad/Retro_A_Round.png)               |
|               | ![RetroPad_X](images/RetroPad/Retro_X_Round.png)               |
| L             | ![RetroPad_L1](images/RetroPad/Retro_L1.png)                   |
| R             | ![RetroPad_R1](images/RetroPad/Retro_R1.png)                   |
|               | ![RetroPad_L2](images/RetroPad/Retro_L2_Temp.png)              |
|               | ![RetroPad_R2](images/RetroPad/Retro_R2.png)                   |
|               | ![RetroPad_L3](images/RetroPad/Retro_L3.png)                   |
|               | ![RetroPad_R3](images/RetroPad/Retro_R3.png)                   |
|               | ![RetroPad_Left_Stick](images/RetroPad/Retro_Left_Stick.png)   |
|               | ![RetroPad_Right_Stick](images/RetroPad/Retro_Right_Stick.png) |

## Compatibility

[4DO Compatibility List](http://wiki.fourdo.com/Compatibility_List)

| Game                                      | Issue                                                                  |
|:-----------------------------------------:|:----------------------------------------------------------------------:|
|**Advanced Dungeons & Dragons - Deathkeep**|Random softlocks (music related?).                                      |
|**Alone in the Dark**                      |Unreadable text within books. Audio glitches.                           |
|**DinoPark Tycoon**                        |Graphics glitches.                                                      |
|**Eye of Typhoon, The**                    |Runs too fast.                                                          |
|**Horde, The**                             |Graphics glitches. Minor graphical inaccuracy in bird's eye map.        |
|**Primal Rage**                            |Audio glitches.                                                         |
|**Psychic Detective**                      |Audio glitches. Sound is sometimes static during videos.                |
|**Shadow - War of Succession**             |Runs too fast.                                                          |
|**Tetsujin Return**                        |Graphics glitches. Missing graphics for obstacles in the driving scenes.|

## External Links

* [Libretro Repository](https://github.com/libretro/4do-libretro)
* [Report Core Issues Here](https://github.com/libretro/libretro-meta/issues)
* [Official Website](http://www.fourdo.com/)
* [Official Repository](https://sourceforge.net/projects/fourdo/)
