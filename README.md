## Benchmark command:

### benchMEM 81K cells
gmx mdrun -s benchMEM.tpr 

### benchRIB 2M cells
gmx mdrun -s benchRIB.tpr

### benchPEP 12M cells
gmx mdrun -s benchPEP.tpr -nsteps -1 -maxh 0.5 -resethway -noconfout

### ion channel 142K atoms
gmx mdrun -s ion_channel.tpr -nsteps 10000

### ceeulose & lignocellulosic biomass 3M atoms
gmx mdrun -s lignocellulose.tpr -nsteps 10000

### STMV (Satellite Tobacco Mosaic Virus) 28M atoms - standard NAMD bench
gmx mdrun -s stmv.28M.tpr -maxh 1.0 -nsteps 50000

### nvt
gmx mdrun -v -deffnm nvt

### nvt-8
gmx mdrun -v -deffnm nvt-8

### prod-long
gmx mdrun -v -deffnm prod-long




