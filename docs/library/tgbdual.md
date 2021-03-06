# Game Boy / Game Boy Color (TGB Dual)

## Background

TGB Dual is an open source (GPLv2) GB/GBC emulator with game link cable support.

Author(s): GIGO|Hii

## Contribute to this documentation

In order to propose improvements to this document, [visit it's corresponding source page on github](https://github.com/libretro/docs/tree/master/docs/library/tgbdual.md). Changes are proposed using "Pull Requests."

## License

GPLv2

## Extensions

gb|gbc|sgb

## BIOS

The TGB Dual core does not support using BIOS image files.

## Features

| Saves | States      | Rewind | Netplay | RetroAchievements | RetroArch Cheats | Native Cheats |
|:-----:|:-----------:|:------:|:-------:|:-----------------:|:----------------:|:-------------:|
|  yes  |   yes       | yes    | yes     |        -          | yes              | no            |

| Controllers     | Rumble | Sensors | Camera | Location | Subsystem     |
|:---------------:|:------:|:-------:|:------:|:--------:|:-------------:|
|       no        |  no    |   no    |  no    |   no     |      no       |

## Options

The TBG Dual core has a few options that can be tweaked from the core options menu. The default setting is bolded:

- **GB Link Enable (Restart)** (**Off**/On) (restart): Emulates two Game Boy units side by side for multiplayer support.

??? note "*GB Link Enable - Enabled*"
    ![gb_link_enable](images\Cores\tgbdual\gb_link_enable.png)

- **Screen placement** (**horizontal**/vertical): Switches the screen layout for multiplayer support.

??? note "*Horizontal*"
    ![screen_placement_horizontal](images\Cores\tgbdual\screen_placement_horizontal.png)

??? note "*Vertical*"
    ![screen_placement_vertical](images\Cores\tgbdual\screen_placement_vertical.png)

- **Switch player screens** (**normal**/switched): Switches the player screens for multiplayer support.
- **Show player screens** (**both players**/player 1 only/player 2 only): Displays the selected player screens for multiplayer support.

## Controllers

The TGB Dual core supports one controller setting(s):

* RetroPad

![tgbdual_retropad](images/Controllers/tgbdual_retropad.png)

| TGB Dual         | [RetroPad](RetroPad)                                           |
|------------------|----------------------------------------------------------------|
| B                | ![RetroPad_B](images/RetroPad/Retro_B_Round.png)               |
|                  | ![RetroPad_Y](images/RetroPad/Retro_Y_Round.png)               |
| Select           | ![RetroPad_Select](images/RetroPad/Retro_Select.png)           |
| Start            | ![RetroPad_Start](images/RetroPad/Retro_Start.png)             |
| D-pad            | ![RetroPad_Dpad](images/RetroPad/Retro_Dpad.png)               |
| A                | ![RetroPad_A](images/RetroPad/Retro_A_Round.png)               |
|                  | ![RetroPad_X](images/RetroPad/Retro_X_Round.png)               |
| Prev Audio Mode  | ![RetroPad_L1](images/RetroPad/Retro_L1.png)                   |
| Next Audio Mode  | ![RetroPad_R1](images/RetroPad/Retro_R1.png)                   |
|                  | ![RetroPad_L2](images/RetroPad/Retro_L2_Temp.png)              |
|                  | ![RetroPad_R2](images/RetroPad/Retro_R2.png)                   |
|                  | ![RetroPad_L3](images/RetroPad/Retro_L3.png)                   |
|                  | ![RetroPad_R3](images/RetroPad/Retro_R3.png)                   |
|                  | ![RetroPad_Left_Stick](images/RetroPad/Retro_Left_Stick.png)   |
|                  | ![RetroPad_Right_Stick](images/RetroPad/Retro_Right_Stick.png) |

## Compatibility

Unknown

## External Links

* [Libretro Repository](https://github.com/libretro/tgbdual-libretro)
* [Report Core Issues Here](https://github.com/libretro/libretro-meta)
* [Official Website](http://gigo.retrogames.com/download.html#tgb-dual)
