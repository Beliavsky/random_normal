# random_normal
random normal variates in Fortran using the polar, Box-Muller, and ratio-of-uniforms methods

on WSL2 with gfortran -O3 I get timings

```
     method          polar      ratio_uni     box_muller
   cpu_time        13.0271        15.3004        12.3667
```

and with ifort -O3
```
     method          polar      ratio_uni     box_muller
   cpu_time        16.8491        20.3027         8.6018
```
