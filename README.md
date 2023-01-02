# Final Fantasy 14 Crafting Macros

Crafting macros that have been updated for the Endwalker expansion.

- [Final Fantasy 14 Crafting Macros](#final-fantasy-14-crafting-macros)
  - [Macros by Minimum Level](#macros-by-minimum-level)
  - [Macros for Endwalker](#macros-for-endwalker)
  - [Comparison Table](#comparison-table)
  - [Naming Style](#naming-style)
  - [Calculating Progress Multiplier](#calculating-progress-multiplier)

## Macros by Minimum Level

These macros are broken down into tiers based on the minimum crafting level for the required skills.  You don't need to create brand new macros every time you learn a new skill.  Instead, you can save effort by waiting for key skills.

- [Level 7](Level7CraftingMacros.md)
- [Level 18](Level18CraftingMacros.md)
- [Level 26](Level26CraftingMacros.md)
- [Level 47](Level47CraftingMacros.md)
- [Level 50](Level50CraftingMacros.md)
- [Level 54](Level54CraftingMacros.md)
- [Level 62](Level62CraftingMacros.md)
- [Level 72](Level72CraftingMacros.md)
- [Level 76](Level76CraftingMacros.md)
- [Level 80](Level80CraftingMacros.md)
- [Level 86](Level86CraftingMacros.md)

These macros have been tested out while leveling, using gear of the appropriate level for the crafts.

## Macros for Endwalker

These macros will work for Endwalker recipes. 

Early on, when you only have ~2500 Craftsmanship and ~2500 Control, you can use these macros to make all recipes up until level 87.  Up until level 86-87, you will also have a 90% or better chance at HQ output from NQ inputs.

- [L72/D30 CP467 7.5x](Level72CraftingMacros.md)
- [L72/D80 CP434 11.6x](Level72CraftingMacros.md)
- [L72/D80 CP455 14.3MM](Level72CraftingMacros.md)
- [L76/D75 CP506 14.5x](Level76CraftingMacros.md)

For the level 90 recipes (prior to using level 90 gear) you'll need a higher progress multiplier.  This comes at the cost of a lower chance of HQ output which can be compensated for by using some/all HQ inputs to the recipe.  Or buffing your control stat with food/etc.

- [L86/D75 CP506 21.1x](Level86CraftingMacros.md)
- [L76/D75 CP524 16.1x](Level76CraftingMacros.md)

## Comparison Table

| Lvl | Name                                             | Dura | Steps | Prog | EQM  | MuscMem | Manip |
| --- | ------------------------------------------------ | ---- | ----- | ---- | ---- | ------- | ----- |
| 7   | [L7/D50 CP160 2.0x](Level7CraftingMacros.md)     | 50   | 8     | 2.0  | ??.? | No      | No    |
| 7   | [L7/D50 CP178 3.0x](Level7CraftingMacros.md)     | 50   | 9     | 3.0  | ??.? | No      | No    |
| 7   | [L7/D60 CP160 5.0x](Level7CraftingMacros.md)     | 60   | 10    | 5.0  | ??.? | No      | No    |
| 18  | [L18/D60 CP182 3.0x](Level18CraftingMacros.md)   | 60   | 10    | 3.0  | ??.? | No      | No    |
| 18  | [L18/D70 CP182 4.5x](Level18CraftingMacros.md)   | 70   | 10    | 4.5  | ??.? | No      | No    |
| 18  | [L18/D65 CP238 6.0x](Level18CraftingMacros.md)   | 65   | 13    | 6.0  | ??.? | No      | No    |
| 26  | [L26/D55 CP256 4.5x](Level26CraftingMacros.md)   | 55   | 13    | 4.5  | ??.? | No      | No    |
| 26  | [L26/D65 CP274 4.5x](Level26CraftingMacros.md)   | 65   | 14    | 4.5  | ??.? | No      | No    |
| 26  | [L26/D25 CP146 1.5x](Level26CraftingMacros.md)   | 25   | 7     | 1.5  | ??.? | No      | No    |
| 72  | [L72/D30 CP467 7.5x](Level72CraftingMacros.md)   | 30   | 14    | 7.5  | 26.3 | No      | Yes   |
| 72  | [L72/D80 CP410 13.5x](Level72CraftingMacros.md)  | 80   | 15    | 13.5 | 19.3 | No      | No    |
| 72  | [L72/D80 CP434 11.6x](Level72CraftingMacros.md)  | 80   | 15    | 11.6 | 23.3 | No      | No    |
| 72  | [L72/D80 CP455 14.3MM](Level72CraftingMacros.md) | 80   | 15    | 14.3 | 23.9 | Yes     | No    |
| 76  | [L76/D75 CP506 14.5x](Level76CraftingMacros.md)  | 75   | 14    | 14.5 | 29.0 | No      | Yes   |
| 76  | [L76/D75 CP524 16.1x](Level76CraftingMacros.md)  | 75   | 15    | 16.1 | 32.1 | No      | Yes   |
| 86  | [L86/D75 CP506 21.1x](Level86CraftingMacros.md)  | 75   | 14    | 21.1 | ??.? | No      | Yes   |
| 86  | [L86/D80 CP450 15.6x](Level86CraftingMacros.md)  | 80   | 14    | 15.6 | 26.2 | No      | No    |
| 86  | [L86/D80 CP491 18.3MM](Level86CraftingMacros.md) | 80   | 15    | 18.3 | 26.2 | Yes     | No    |

- Lvl: Minimum crafting level before you can use the macro.
- Name: See the [Naming Style](#naming-style) section below.
- Dura: The maximum amount of durability consumed during execution of the macro.
- Steps: The number of productive steps in the macro.  Not including any alert sound step.  Fewer steps means the macro will complete faster.
- Prog: Amount of progress in total. See the [Naming Style](#naming-style) section below.
- EQM: Estimated Quality Multiplier (EQM) is a relative measure of how effective the macro is at increasing quality. Higher values let you use more normal quality inputs.
- MuscMem (Yes): Macros which use [Muscle Memory](https://ffxiv.consolegameswiki.com/wiki/Muscle_Memory) **without** also using [Final Appraisal](https://ffxiv.consolegameswiki.com/wiki/Final_Appraisal) are risky if used on too low of a recipe.  They run the risk of early completion before the quality has been raised.
- Manip (Yes): If you have not completed your level 65 crafting quest, you won't have access to the [Manipulation](https://ffxiv.consolegameswiki.com/wiki/Manipulation) skill.  This is an important skill in the later tiers, but you can get by without it if you are using level appropriate foods, materia and gear.

## Naming Style

All of the macros are named as follows:

`L7/D50 CP160 2.0x`

- `L7`: The macro uses no skill higher than level 7.  Whether or not it is usable at that level depends on whether your gear has enough CP on it.
- `D50`: The most that durability will be reduced by during the macro.  A macro that only uses 40 durability can be used on all recipes where the item has at least 40 durability.
- `CP160`: The number of CP required to use this macro.  You must have at least this amount of CP to succeed.  
- `2.0x`: How much progress the macro makes.  This is very important, because if you fail to increase the progress bar to 100% then it is a failed synthesis.  It does not hurt to overshoot on progress, except for macros that use [Muscle Memory](https://ffxiv.consolegameswiki.com/wiki/Muscle_Memory).

`L72/D80 CP455 14.3MM`

- `L72`: Requires skills of level 72 or lower.
- `D80`: The recipe must have 80 durability.
- `CP455`: You must have at least 455 CP to use this macro.
- ` 14.3MM`: How much progress the macro makes (14.3x your 100% progress value). The "MM" suffix indicates that you need to use caution because this macro uses [Muscle Memory](https://ffxiv.consolegameswiki.com/wiki/Muscle_Memory) without any guardrails like [Final Appraisal](https://ffxiv.consolegameswiki.com/wiki/Final_Appraisal) to prevent early completion.

## Calculating Progress Multiplier

In order to calculate which macro to use, it's important to compare the recipe difficulty against your 100% progress increase value.  Divide the difficulty value by the "progress increases by" value and that's the multiplier that you need.  Note that if you are barely reaching the progress multiplier (like "3.0x") then you should plan on using the next higher progress multiplier macro (e.g "4.5x").

![Difficulty vs Progress](imgs/DifficultyProgress1Highlight.png)
