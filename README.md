Benchmark command:

## benchMEM 81K cells
gmx mdrun -s benchMEM.tpr 

## benchRIB 2M cells
gmx mdrun -s benchRIB.tpr

## benchPEP 12M cells
gmx mdrun -s benchPEP.tpr -nsteps -1 -maxh 0.5 -resethway 
