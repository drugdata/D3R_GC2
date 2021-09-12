###################################

PDB files are provided for the crystallographic ligand poses to be predicted for the Grand Challenge 2 target, FXR. 

Among the 36 co-crystal structures, 13 have one copy (chain A) of the protein-ligand complex, 22 have two copies 
(chain A and chain C), and one has four copies (chains A, C, E and G). The structures provided by Roche were reviewed 
by D3R crystallographers and re-refined as needed. The resulting PDB files are provided in the RAW_ALL folder. This 
also contains the apo structure provided with the challenge package, 1dvwb.pdb. In order to facilitate evaluation of 
pose predictions, three other folders provide the structures of the chain A, C, E and G copies, separated and 
superposed independently to the apo structure.

Although there are 36 ligands, 40 PDB files are provided for chain A. This is because four of the ligand structures 
have double occupancies, for either all or part of the ligand, as follows:

   1uxjy - 70:30 ligand occupancies (whole ligand)
   1txca - 50:50 ligand occupancies (whole ligand)
   1kjyp - 50:50 ligand occupancies (part of the ligand)
   1dqzc - 51:49 ligand occupancies (part of the ligand)

For each of these cases, we supply two separate PDB files, designated AA and AB, one with each of the alternative 
crystallographic poses; e.g., 1uxjy-AA.pdb and 1uxjy-AB.pdb.

25 PDB files are provided for chain C. These are from the 22 structures with two copies of the protein, one structure 
with four copies, and two cases, 1uxjy and 1txca, with double occupancies (70:30 and 50:50, respectively) for the whole 
chain C ligand. The corresponding files names are rendered as, for example, 1uxjy-CA.pdb and 1uxjy-CB.pdb.

2 PDB files are provided for chains E_and_G, both drawn from the one structure with four copies of the protein, 1ytut. 

In evaluating pose predictions for these cases, we will compute and consider RMSDs relative 
to both alternative poses.

###################################