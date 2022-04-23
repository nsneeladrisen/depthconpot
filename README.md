# depthconpot
Datasets for the hotspot predictor depthconpot
train_set.tsv - Training set
test_set1.tsv - Testing set1
test_set2.tsv - Testing set2
test_set3.tsv - Testing set3
test_set4.tsv - Testing set4

Column descriptors
pdbid - PDBID
chain - Chain ID
aminoacid - single letter code of the amino acid
aano - Residue number
depth_aa_complex - Residue all atom depth in the comples
depth_aa_subunit - Residue all atom depth in individual subunit
depth_diff_aa - Change in depth upon complex formation (depth_aa_complex-depth_aa_subunit)
conservation - conservation scores
abhilesh_potential_total - contact potential of the residue
hotspot_nonhotspot - 1 if the residue is actually a hotspot, 0 if it is not a hotspot
