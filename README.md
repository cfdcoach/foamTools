# foamTools

## Small tools for OpenFOAM

Most of them are shell scripts, so that you can execute them directly without compilation.

Usage
1. plotResidual: plot residuals graphically on-the-fly

Requirement: gnuplot

```
plotResidual <logfile> <parameter1> <parameter2> ... <parameterN>
```
If you want to stop plotting, execute the command as the last line printed on the screen.
