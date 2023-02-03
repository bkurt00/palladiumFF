# palladiumFF
Palladium Amber force field files and assign.py program for square planar cis-trans palladium simulations
Please cite this article: "DEVELOPMENT OF ASSIGN.PY PROGRAM AND AMBER FORCE FIELD FOR MOLECULAR DYNAMICS SIMULATIONS OF CIS-TRANS PALLADIUM COMPOUNDS, Barış KURT, 2023"
######################################################
HOW TO RUN PROGRAM:
You may change PARMCHK.DAT (dat/antechamber/PARMCHK.DAT) to run assign.py. Modified PARMCHK.DAT is PARMCHK_modified.DAT in this directory. 
!!!Please be sure to back up the original parmchk.dat file before using the modified parmchk.dat.
1) Make a back up original PARMCHK.DAT 
2) Copy PARMCHK_modified.DAT into dat/antechamber/ and rename it "PARMCHK.DAT"
3) set up python3 and download "assign" folder and run assign.py with this command:
 "python3 assign.py"
######################################################
*You can add your parameters into assign/data folder. For this:
bond parameters must be added into gaff2_bonds.dat
angle parameters must be added into gaff2_angles.dat
dihedral parameters mus be added into gaff2_dihedral.dat exc..
######################################################
**in resp_mol2_top_crd folder, you can find result.frcmod files. These files obtained with assign.py. Since these files were obtained during the development of assign.py, 
there may be some differences between the file you obtained and here. In this folder, also there are prmtop, coordinate and mol2 files with resp charges...
Other details about the program can be found in the article.
######################################################
***All palladium parameters in paladdiumFF/assign/data/Pd_son.dat
######################################################
