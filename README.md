# UO-Outlands

My personal [Razor](https://www.razorce.com/guide/) scripts for [UO Outlands](https://uooutlands.com/).
I use them myself while playing. They are set up for my character and my guild
(container serials, options), so expect to change the config at the top of a
script before using it yourself.

## Scripts

| Script | What it does |
|---|---|
| `CFC_BossLootDropOff.razor` | Guild boss loot drop-off for CFC: moves loot from your backpack and the CFC Public Chest into the distros and guild storage, then starts `[bossresults`. Based on the YEW drop-off by Stephanius. |
| `tokenScript.razor` | Sorts boss tokens into the main and mini token bags. |
| `AutoDexxer.razor` | Auto dexxer, based on the Jaseowns script. |
| `DropOff.razor` | Sorts dungeon loot onto the shelf, the resource pile, the deposit box and the recycler, based on the Jaseowns script. |
| `RecycleWhileFarming.razor` | Recycles items while farming, based on the Jaseowns script. |

Several scripts are adapted from the community library at
[outlands.uorazorscripts.com](https://outlands.uorazorscripts.com/).

## Using a script

1. Copy the `.razor` file into the `Scripts` folder of your Razor install,
   or paste its contents into a new script in Razor.
2. Change the config block at the top (container serials, options).
   Use `>info` in game to get a serial.
