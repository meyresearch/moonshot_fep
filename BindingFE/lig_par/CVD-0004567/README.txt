# Antechamber was run with the following command:
/home/rzhu/miniconda3/envs/BSS/bin/antechamber -at 2 -i antechamber.pdb -fi pdb -o antechamber.mol2 -fo mol2 -c bcc -s 2 -nc 0

# ParmChk was run with the following command:
/home/rzhu/miniconda3/envs/BSS/bin/parmchk2 -s 2 -i antechamber.mol2 -f mol2 -o antechamber.frcmod

# tLEaP was run with the following command:
/home/rzhu/miniconda3/envs/BSS/bin/tleap -f leap.txt
