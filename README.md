# eORCA1
Standard extended ORCA1 configuration

**_\*\* NB the code as it stands is a test configuration - the setup script has been tested and will checkout, compile and run the eORCA1 (NEMO 4.0.4) code on ARCHER2, but namelists and forcing files are intended for testing only_**

Configuration files for eORCA1

## Quick Start on ARCHER2:

```
git clone git@github.com:NOC-MSM/eORCA1.git
./eORCA1/scripts/setup/eORCA1_setup -w $PWD/test -x $PWD/test -s $PWD/eORCA1
cd test/nemo/cfgs/eORCA1/EXP00
```
Edit the project code in  `runscript.slurm` then:
```
sbatch runscript.slurm
```
This will produce a 5 day mean output from the beginning of 2000, for 1 month. The run should take 5 minutes to complete once in the machine (configured to use the short queue in the runscript).

### Forcing data:

[eORCA1](http://gws-access.ceda.ac.uk/public/jmmp_collab/eORCA1)

_this is automatically transferred when the setup script is executed_

### Important:

Nothing as of yet!
