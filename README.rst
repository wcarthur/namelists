WRF Namelist repository
=======================

This folder contains namelist files for running WRFV-3.7.1.

For a new experiment, create a new namelist.input file, and link it to the appropriate directory at run time (e.g. if running the idealised TC experiment, link it to $WRF_ROOT/test/em_tropical_cyclone/namelist.input, where $WRF_ROOT is the base path of the WRF installation.

On NCI, I have the base WRF code stored on my /short partition, and the namelists in my /home directory.

For each experiment, add a brief description in this README. Be sure to properly explain changes in the commit message.
