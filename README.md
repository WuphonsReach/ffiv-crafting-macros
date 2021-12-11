# Final Fantasy 14 Crafting Macros

Crafting macros that have been updated for the Endwalker expansion.


- [Final Fantasy 14 Crafting Macros](#final-fantasy-14-crafting-macros)
  - [Guide](#guide)
    - [Naming Style](#naming-style)
  - [Level 7](#level-7)
    - [L7/D30 CP178 1.0x](#l7d30-cp178-10x)
    - [L7/D30 CP178 2.0x](#l7d30-cp178-20x)
    - [L7/D50 CP160 2.0x](#l7d50-cp160-20x)
    - [L7/D50 CP178 3.0x](#l7d50-cp178-30x)
  - [Level 18](#level-18)
    - [L18/D40 CP182 X1.5](#l18d40-cp182-x15)
    - [L18/D40 CP182 3.0x](#l18d40-cp182-30x)
    - [L18/D60 CPxxx X1.5](#l18d60-cpxxx-x15)
    - [L18/D70 CP200 X3.0](#l18d70-cp200-x30)
    - [L18/D70 CP200 X4.5](#l18d70-cp200-x45)
  - [Level 81-ish](#level-81-ish)

## Guide

### Naming Style

`L7/D50 CP160 2.0x`

- `L7`: The macro uses no skill higher than level 7.  Whether or not it is usable at that level depends on whether your gear has enough CP on it.
- `D50`: The most that durability will be reduced by during the macro.  For some macros, they are designed to never use more than 30 durability before using Master's Mend to restore durability.  Or they never use more than 50 durability in total.  A macro that only uses 40 durability can be used on all recipes where the item has at least 40 durability.
- `CP160`: The number of CP required to use this macro.  
- `2.0x`: How much progress the macro makes.  This is very important, because if you fail to increase the progress bar to 100% is a failed synthesis.  You can estimate what multiplier you will need by taking the difficulty of the recipe and dividing by the "at 100% progress will increase by ###" value. It does not hurt too much to overshoot on progress.

## Level 7

Prior to level 7, you'll only have "Basic Synthesis" and "Basic Touch" (level 5).  There's not much point in creating macros for levels 1-6 since you will jump past them so fast.  However, once you have "Master's Mend" at level 7 it is worth trying to piece together something more advanced.  You're still too low to get 100% HQ on every combine as you would need all HQ inputs for the most part.


### L7/D30 CP178 1.0x
```
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Master's Mend" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Craft finished <se.1>
```

### L7/D30 CP178 2.0x
```
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Master's Mend" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Craft finished <se.1>
```

### L7/D50 CP160 2.0x
```
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Master's Mend" <wait.3>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

### L7/D50 CP178 3.0x
```
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Master's Mend" <wait.3>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

## Level 18

At level 18, you gain "Standard Touch", plus you picked up "Waste Not" and "Veneration" at level 15.  This gives a boost in being able to get a HQ result from your macros without needing all input materials as HQ.

TODO: Rewrite these macros to use "Standard Touch" in combination with "Basic Touch".  I also need to double-check the label values for durability / CP used.

### L18/D40 CP182 X1.5
```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

### L18/D40 CP182 3.0x
```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

### L18/D60 CPxxx X1.5
```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

### L18/D70 CP200 X3.0
```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

### L18/D70 CP200 X4.5
```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro #1 complete <se.1>
```

## Level 81-ish

Norah gave me this one for use on the level 81 leves / collections.

```
/ac Reflect <wait.3>
/ac Innovation <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac Innovation <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac Groundwork <wait.3>
```
