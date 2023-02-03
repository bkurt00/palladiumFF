<!DOCTYPE html>
<html>
<title>Palladium ForceField For Cis-Trans Square Planar Complexes</title>

<head>
</head>

<body>

    <p> <b> Palladium Amber force field files and assign.py program for square planar cis-trans palladium simulations</b> </p>
    <p> <b>Please cite this article: </b> "DEVELOPMENT OF ASSIGN.PY PROGRAM AND AMBER FORCE FIELD FOR MOLECULAR DYNAMICS SIMULATIONS OF CIS-TRANS PALLADIUM COMPOUNDS, Barış KURT, 2023" </p>
    <p>
        <b>HOW TO RUN PROGRAM:</b></p>
    <ul>
        <li>
            -set up python3 and download "assign" folder and run assign.py with this command: <span style="border: 1px solid black"><code>python3 assign.py</code> </span>
        </li>

    </ul>
    <b>I WANT TO USE THIS TECHNIQUE FOR ANOTHER METAL (E.g. PLATINUM) WHAT SHOULD I DO?</b></p>

    <ul>
        <li>
            You can add your novel metal parameters into <span style="border: 1px solid black">assign/data</span> folder. For this: bond parameters must be added into gaff2_bonds.dat angle parameters must be added into gaff2_angles.dat dihedral parameters mus be added into gaff2_dihedral.dat exc..
        </li>
    </ul>

    <b>I WANT TO TEST THE REPRODUCIBILITY OF THE RESULTS MYSELF, WHERE CAN I FIND FILES?</b>

    <ul>
        <li>
            <p>in <span style="border: 1px solid black">resp_mol2_top_crd </span> folder, you can find result.frcmod files. These files obtained with assign.py. Since these files were obtained during the development of assign.py, there may be some differences between the file you obtained and here. In this folder, also there are prmtop, coordinate and numbering system mol2 files with resp charges files: <span style="border: 1px solid black"> a.mol2, a.top, a.crd, result.frcmod </span> Other details about the program can be found in the article.
            </p>
        </li>
    </ul>
    <b> I WANT TO SEE ALL PALLADIUM CIS TRANS FORCE FIELDS IN ONE FILE WHERE CAN I FIND IT?</b>
    <ul>
        <li>
            All palladium parameters in <span style="border: 1px solid black">paladdiumFF/assign/data/Pd_son.dat</span>
        </li>
    </ul>


</body>

</html>