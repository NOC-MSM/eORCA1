# eORCA1
Standard extended ORCA1 configuration

**_\*\* NB the code as it stands is a placeholder - not intended for use - the setup script has been tested and will checkout, compile and run the eORCA1 (NEMO 4.0.2) code on ARCHER, but namelists and forcing files are yet to be configured_**

Configuration files for eORCA1

## Quick Start:

```
git clone git@github.com:NOC-MSM/eORCA1.git
./eORCA1/scripts/setup/eORCA1_setup_archer -w $PWD/test -x $PWD/test -s $PWD/eORCA1
cd test/nemo/cfgs/eORCA1/EXP00
```
Edit the project code in  `runscript.pbs` then:
```
qsub runscript.pbs
```
This will produce a 5 day mean output from the beginning of XXXX. The run should take YY minutes to complete once in the machine.

### Forcing data:

[eORCA1](http://gws-access.ceda.ac.uk/public/jmmp_collab/)

_this is automatically transferred when the setup script is executed_

### Important:

None as of yet!
