# GROMACS 5.0.6 with sphero-cylindrical confinement<br>
Link for downloading: https://drive.google.com/file/d/1mfEZnRTf0r9YTLqFP37IjdORIr0wlw-p/view?usp=sharing

## Documentation<br>
This is a modified version of GROMACS 5.0.6 which has been modified to include a capsule shaped confinement.<br>
The flat bottom position restraint has been tweaked to include the shape.<br>

### usage<br>
```[ position_restraints ]```<br>
```<id> <type> <shape> <radius> <force constant> <length> <centre x> <centre y> <centre z>```<br>
** the length is the length of the cylinderical part only (excluding end caps)<br>

Example:<br>
```1       2       6       6.157   310.000 32.400  6.157   6.157   22.357```<br>

Please refer to GROMACS manual for details on the syntax for flat bottomed position restraints.<br>
https://manual.gromacs.org/current/reference-manual/functions/restraints.html<br>
