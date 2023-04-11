**UPDATE: 12/04/2023:**
**assign_v2.py has been added. you can use assign_v2.py instead of assign.py. 
*assign_v2.py is optimized version of assign.py.

Palladium ForceField For Cis-Trans Square Planar Complexes

**Palladium Amber force field files and assign.py program for square planar cis-trans palladium simulations**

**Please cite this article:** "DEVELOPMENT OF ASSIGN.PY PROGRAM AND AMBER FORCE FIELD FOR MOLECULAR DYNAMICS SIMULATIONS OF CIS-TRANS PALLADIUM COMPOUNDS, Barış KURT, 2023"

**HOW TO RUN PROGRAM:**

*   \-set up python3 and download "assign" folder and run assign.py with this command: `python3 assign.py`

**I WANT TO USE THIS TECHNIQUE FOR ANOTHER METAL (E.g. PLATINUM) WHAT SHOULD I DO?**

*   You can add your novel metal parameters into assign/data folder. For this: bond parameters must be added into gaff2\_bonds.dat angle parameters must be added into gaff2\_angles.dat dihedral parameters mus be added into gaff2\_dihedral.dat exc..

**I WANT TO TEST THE REPRODUCIBILITY OF THE RESULTS MYSELF, WHERE CAN I FIND FILES?**

*   in resp\_mol2\_top\_crd folder, you can find result.frcmod files. These files obtained with assign.py. Since these files were obtained during the development of assign.py, there may be some differences between the file you obtained and here. In this folder, also there are prmtop, coordinate and numbering system mol2 files with resp charges files: a.mol2, a.top, a.crd, result.frcmod Other details about the program can be found in the article. 
*   To simulate a novel molecule:
*   1. obtain novel result.frcmod file ( with g.mol2 and g2.mol2) using assign.py
*   2. in tleap enter:
*   `loadamberparams result.frcmod`
*   `loadmol2 g2.mol2`
*   then **if you need**; load gaff2.dat and Pd_son.dat (paladdiumFF/assign/data/Pd_son.dat) parameters too.
    

**I WANT TO SEE ALL PALLADIUM CIS TRANS FORCE FIELDS IN ONE FILE WHERE CAN I FIND IT?**

*   All palladium parameters in paladdiumFF/assign/data/Pd_son.dat

**ATTENTION ABOUT PARMCHK.DAT**
Some parameters may need to be added to dat/antechamber/PARCMHK.DAT for parmchk2 to run. These parameters can be found in PARMCHK_additional.DAT. Make sure to make a  backup of the original parmchk.dat file before doing this. No responsibility is accepted.
