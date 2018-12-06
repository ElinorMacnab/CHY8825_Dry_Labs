Investigating the structure and function of DDR2 and carrying out homology modelling using Uniprot, the PDB, Clustal and Phyre2
Found DDR2 human entry in Uniprot (Q16832)
X-ray structure known for aa 26-190; NMR for 26-186
Kinase domain is aa 563-849 - no structure available
Ran BLAST on kinase domain against human proteome
DDR1 has 68.2% similarity (ignoring DDR2 isoform and an uncharacterised protein)
Ran BLAST again against only proteins with known 3D structures - also highlighted DDR1
PDB codes: 3ZOS, 4AG4, 4BKJ, 4CKR, 5BVK, 5BVN, 5BVO, 5BVW, 5FDP, 5FDX, 6GWR
Kinase domain is 610-905 - best resolution structure for that region is 4BKJ
Searched that code in PDB and found a crystal structure of DDR1 kinase domain bound to imatinib
Aligned kinase domain primary structures in ClustalW
68.58% identical, 14.19% strongly similar, 8.11% weakly similar (22.30% similar)
Set a Phyre2 model running on DDR2
In Chimera, opened DDR2_fixed.pdb (a premade DDR2 kinase structure) and PDB code 5FDX (DDR1 kinase)
Selected backbones of the two models (Select -> Structure -> backbone -> full)
Superimposed backbones (Tools -> Structure Comparison -> Matchmaker, reference 5fdx, matching DDRfixed(1).pdb, matching restricted)
RMSD 0.639A across 216 pairs, 2.101A across 267 pairs
Aligned DDR2fixed to 5fdx chain B (Tools -> Sequence -> Match->Align)
Strongly conserved at positions 93-160 and 193-350 (DDR2 42-108 and 129-284, DDR1 651-717 and 747-902), most diverse at positions 1-91 (DDR2 1-40, DDR1 577-649) and 161-192 
(DDR2 109-128, DDR1 718-746), the first of which is in the binding site
Figure creation:
Presets - Publication 3
Select -> Residue -> 5X1 (ligand)
Actions -> Atoms/Bonds -> sphere
Selected diverse regions on match results
Coloured DDR2 diverse regions green and DDR1 diverse regions red
Saved image in working directory as DDR2_DDR1_superimposed