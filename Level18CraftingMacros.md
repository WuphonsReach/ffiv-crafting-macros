# Level 18

At level 18, you gain "Standard Touch", plus you picked up "Waste Not" and "Veneration" at level 15.  This gives a boost in being able to get a HQ result from your macros without needing all input materials as HQ.

TODO: Rewrite these macros to use "Standard Touch" in combination with "Basic Touch".  I also need to double-check the label values for durability / CP used.

- [Level 18](#level-18)
  - [L18/D40 CP182 X1.5](#l18d40-cp182-x15)
  - [L18/D40 CP182 3.0x](#l18d40-cp182-30x)
  - [L18/D60 CPxxx X1.5](#l18d60-cpxxx-x15)
  - [L18/D70 CP200 X3.0](#l18d70-cp200-x30)
  - [L18/D70 CP200 X4.5](#l18d70-cp200-x45)

## L18/D40 CP182 X1.5
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

## L18/D40 CP182 3.0x
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

## L18/D60 CPxxx X1.5
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

## L18/D70 CP200 3.0x

This macro could have the last "Basic Touch" removed if you need a macro that is capable of making a durability 60 recipe.  You might have trouble getting 100% HQ by doing so, but maybe there's a recipe where you don't have 70 durability to play with.

```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro Complete <se.1>
```

## L18/D70 CP182 4.5x

This macro could have the last "Standard Touch" removed if you need a macro that is capable of making a durability 60 recipe. You might have trouble getting 100% HQ by doing so, but maybe there's a recipe where you don't have 70 durability to play with.

```
/ac "Waste Not" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
/ac "Veneration" <wait.2>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/ac "Basic Synthesis" <wait.3>
/echo Macro Complete <se.1>
```
