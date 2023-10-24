# COMSOL-Models
This repository will show simulation of phonon in Al. Aluminium Phononic crystal simulation in comsol based on following data


|Name | Expression | Value | Description|
| --- | -----------|-------|------------|
| a   |  33[mm]    | 0.033m | lattice constant|
| r   |  15[mm]    |0.015 m |radius of the hole|
|d    | 2[mm]      | 0.002 m| thickness of the plate|
| k   |  0         |   0     |reduced wave vector   |
| kx  | if(k<1,pi/a*k,if(k<2,pi/a,(3-k)*pi/a))| 0 1/m |wave vector along x-axis|
|ky   |if(k<1,0,if(k<2,(k-1)*pi/a,(3-k)*pi/a))  |0 1/m |wave vector along y-axis|



|Property | Value |
|---------|-------|
|Young's Modulus (E)|70 GPa|
|Density (ρ) |2700 kg/m3|
|Poisson’s ratio (µ)|0.33|











