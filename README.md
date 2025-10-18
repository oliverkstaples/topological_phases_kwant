This project analyses a concrete lattice model for the Z2 topological insulator with the BHZ model. 

Kwant is not supported natively for Apple silicon Macs. 

To get around this open terminal with Rossetta and create a Conda virtual environment with Python 3.9 with a one-off x86 subshell under arch -x86_64 zsh.

(kwant-env) MacBookPro:~ NAME$ python -c "import kwant, platform; print(kwant.__version__, platform.machine())" 
1.5.0 x86_64
