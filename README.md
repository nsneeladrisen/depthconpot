# depthconpot
Datasets for the hotspot predictor depthconpot <br />
train_set.tsv - Training set <br />
test_set1A.tsv - Testing set1A <br />
test_set1B.tsv - Testing set1B <br />
test_set1C.tsv - Testing set1C <br />
test_set2.tsv - Testing set2<br />

Column descriptors <br />
pdbid - PDBID <br />
chain - Chain ID <br />
aminoacid - single letter code of the amino acid <br />
aano - Residue number <br />
depth_aa_complex - Residue all atom depth in the comples <br />
depth_aa_subunit - Residue all atom depth in individual subunit <br />
depth_diff_aa - Change in depth upon complex formation (depth_aa_complex-depth_aa_subunit) <br />
conservation - conservation scores <br />
abhilesh_potential_total - contact potential of the residue <br />
hotspot_nonhotspot - 1 if the residue is actually a hotspot, 0 if it is not a hotspot
