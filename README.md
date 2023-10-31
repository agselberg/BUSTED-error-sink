# Using BUSTED error sink mode

To use error-sink make sure you are using hyphy from the develop branch

The command to run BUSTED error sink is the following:

```
hyphy busted --alignment xxx --branches yyy --starting-points 5 --error-sink Yes --save-fit zzz
```

The provided Snakefile runs BUSTED error sink on both the FG and BG to emulate BUSTED-PH
