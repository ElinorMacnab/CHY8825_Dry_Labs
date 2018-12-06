Docking known DDR1 ligands against DDR2 and building a new DDR2 ligand
Fetched DDR1 (5fdx) from PDB to Chimera
Deleted chain B, then all but the ligand (Select -> chain -> B, Actions -> Atoms/Bonds -> delete, Select -> Residue -> 5X1, Select -> Invert (selected models), Actions -> Atoms/Bonds -> delete)
Saved PDB as H:\CHY8825\DL4\DDR1_ligand.pdb
Closed in model panel
Refetched DDR1 as above
Removed everything but the protein (Select -> Residue -> all nonstandard, Actions -> Atoms/Bonds -> delete)
Saved PDB in working directory as DDR1_cleaned.pdb
Reopened ligand file and moved ligand out of binding site
Opened Vina (Tools -> Surface/Binding Analysis -> AutoDock Vina) and resized selection box to cover protein
Set options as instructed and saved output file in working directory as positive_control_1
Saved results in working directory as positive_control_1_results.pdbqt
Fetched DDR1 again and viewed side by side with best docked pose (binding score -9.6)
Ligand is in same place but opposite orientation
Ligands represented as ball and stick; publication 3 used; saved image as crystal_vs_docked.png
Opened DDR2fixed(1).pdb from DL3 and docked with DDR1_ligand (top binding score -8.7 but in different position?)
Fetched all DDR1 structures from DL3 and superimposed with MatchMaker (saved PDB as DDR1_overlay)
Deleted all non-inhibitors and saved as DDR1_inhibitors
Docked all ligands separately to DDR2
3ZOS: -9.2
4BKJ: -7.6
4CKR: -12.5
5BVK: -8.1
5BVN: -8.1
5BVO: -10.5
5BVW: -9.1
5FDP: -8.2
6GWR: -11.2
Inspected best pose for 4CKR ligand with DDR2
H-bonds from Val145 to N at far end of saturated ring and from Asp166 to carbonyl oxygen; aromatic interaction between Phe167 and fused aromatic ring?
Drew out 3 best binders in ChemDraw, kept most of 4CKR and added i-Pr group from 6GWR and a methyl to fill up apparent cavity
Docked new ligand into DDR2
Me up => -10.4, Me down => -9.7, no Me => -11.2
Tried replacing linker O with CF2 => -10.9
Made figure with best binding new ligand and saved as new_ligand.png