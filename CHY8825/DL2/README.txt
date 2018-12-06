Performing structural analysis and energy minimisation on two possible structures of a peptide from alpha-synuclein
PDB files downloaded from Blackboard and saved in H:/CHY8825/DL2
In command line, display shows all side chains
Loaded Asyn_helix
To measure distance between residues 39 and 45:
select :39@oh :45@nz
Tools -> Structure Analysis -> Distances -> Create
Distance = 8.944angstroms
To measure distance between terminal alpha-carbons (end-to-end distance):
select :35@ca :56@ca then as above
Distance: 24.297angstroms
Select whole peptide using select
Actions -> Surface -> show
Tools -> Surface/Binding Analysis -> Measure Volume and Area
Volume: 2073AU
Surface area: 1570AU
To find hydrogen bonds:
Actions -> Surface -> Hide
Tools -> Structure/Binding Analysis -> FindHBond -> Apply
Number of H-bonds: 10, mostly between backbone carbonyls and NHs in the helix
To visualise flexibility:
Tools -> Structure Analysis -> Render by attribute -> select bfactor -> Apply
More flexible in unstructured region, less at CT of helix
Deleselected model in Tools -> General Controls -> Model Panel
Built new helix with same primary structure as described in slides
Measured end-to-end distance as above (select #1:1@ca #1:22@ca)
Distance: 31.996angstroms
Compared models using Tools -> Structure Comparison -> MatchMaker (reference Asyn_helix, matched ideal_helix, restricted matching selected)
RMSD: 0.204angstroms across 8 pairs, 9.208angstroms across all 22 pairs
Energy minimisation: Tools -> Structure Editing -> Minimize Structure keeping all defaults
Saved PDB coordinates in the working directory as Asyn_helix_min.pdb
Opened Asyn_beta, minimised structure as above and saved as Asyn_beta_min.pdb
H-bonds between side chains (found as above, structure reminimised with 1000 steepest descent steps):
Tyr39-His50
H-bonds from side chain to backbone and vice versa:
Lys43-Gly47
Glu46-Glu46
Thr54-Gly36
