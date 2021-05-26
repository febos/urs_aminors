
## Shalybkova AA, Mikhailova DS, Kulakovskiy IV, Fakhranurova LI, Baulin EF. Annotation of the local context of the RNA secondary structure improves the classification and prediction of A-minors. RNA. 2021 May 20:rna-078535.

## https:doi.org/10.1261/rna.078535.120

### List of files:

#### MLdataset.csv - list of A-stems with their features used for training and prediction by the machine learning algorithm (features' description see below)

#### Supplemental_text_S1.pdf - Supplementary Text S1

#### FileS1.jmol - Supplementary File S1

#### FigureS1.jpg - Supplementary Figure S1

#### SupplTableS1.pdf - Supplementary Table S1

#### SupplTableS2.xlsx - Supplementary Table S2

#### SupplTableS3.xlsx - Supplementary Table S3

#### SupplTableS4.xlsx - Supplementary Table S4

#### SupplTableS5.xlsx - Supplementary Table S5


#### Fig1.jpg - Figure 1. Distribution of clustered A-minor interactions by geometric and molecular types

#### Fig2.jpg - Figure 2. The size distribution of 1504 A-minor motifs from the representative set of RNA structures

#### Fig3.jpg - Figure 3. 10 most frequent RNA secondary structure classes of A-minor interactions

#### Fig4.jpg - Figure 4. 3D structure and RNA secondary structure scheme of two across-bulged motifs and a GAAA-11nt motif

#### Fig5.jpg - Figure 5. Different A-patch architectures of size (2,2)

#### Fig6.jpg - Figure 6. Cross-validation results on the entire dataset of A-stems and on the subgroup of threetypes: IC-LC, HP-LC, and IP-LC

#### Fig7.jpg - Figure 7. AUA A-patch from LSU rRNA, PDB ID: 5TBW

#### Fig8.jpg - Figure 8. Pseudoknot-related classes of internal loops

#### Fig9.jpg - Figure 9. Example of a classified A-minor

#### Fig10.jpg - Figure 10. Definition of an A-stem classification problem


### MLdataset.csv - description of columns:

```
PDB_CH			- PDB entry & RNA chain identifier, separated with an underscore (not a feature)
DSSR			- identifiers of A-stem's nucleotides in DSSR format, see https://x3dna.org/ (not a feature)
Types			- list of geometric types (I/II/X) of contained A-minors (not a feature)
SecStruct		- RNA secondary structure type of the A-stem, for example HC-LR - adenines from a classical hairpin distant to the stem; HP-LC - adenines from a pseudoknotted hairpin adjacent to the stem (not a feature)
ds			- Distance (number of stems) between the adenine stretch and the stem
dbps			- Distance (number of base pairs) between the adenine stretch and the stem
dbc			- Distance (number of classical bulges) between the adenine stretch and the stem
dbi			- Distance (number of isolated bulges) between the adenine stretch and the stem
dbp			- Distance (number of pseudoknotted bulges) between the adenine stretch and the stem
dhc			- Distance (number of classical hairpins) between the adenine stretch and the stem
dhi			- Distance (number of isolated hairpins) between the adenine stretch and the stem
dhp			- Distance (number of pseudoknotted hairpins) between the adenine stretch and the stem
dic			- Distance (number of classical internal loops) between the adenine stretch and the stem
dii			- Distance (number of isolated internal loops) between the adenine stretch and the stem
dip			- Distance (number of pseudoknotted internal loops) between the adenine stretch and the stem
djc			- Distance (number of classical junctions) between the adenine stretch and the stem
dji			- Distance (number of isolated junctions) between the adenine stretch and the stem
djp			- Distance (number of pseudoknotted junctions) between the adenine stretch and the stem
lc			- Adenines belong to a loop that is adjacent to the stem (1 - yes, 0 - no) 
lr			- Adenines belong to a loop that is distant to the stem (1 - yes, 0 - no)
al_dist			- Sequence distance (number of nucleotides) between the adenines and the left wing of the stem
al_guadist		- Sequence distance (number of guanines) between the adenines and the left wing of the stem
al_adedist		- Sequence distance (number of adenines) between the adenines and the left wing of the stem
al_cytdist		- Sequence distance (number of cytosines) between the adenines and the left wing of the stem
al_uradist		- Sequence distance (number of uraciles) between the adenines and the left wing of the stem
al_bpdist		- Number of base pairs that involve nucleotides between the adenine stretch and the left wing of the stem
al_lbpdist		- Number of closest to 5'-end nucleotides of base pairs between the adenine stretch and the left wing of the stem
al_rbpdist		- Number of closest to 3'-end nucleotides of base pairs between the adenine stretch and the left wing of the stem
al_lwingdist		- Number of left wings between the adenine stretch and the left wing of the stem
al_rwingdist		- Number of right wings between the adenine stretch and the left wing of the stem
al_stemdist		- Number of stems that involve any wings between the adenine stretch and the left wing of the stem
al_lstemdist		- Number of stems that involve left wings between the adenine stretch and the left wing of the stem
al_rstemdist		- Number of stems that involve right wings between the adenine stretch and the left wing of the stem
ar_dist			- Sequence distance (number of nucleotides) between the adenines and the right wing of the stem
ar_guadist		- Sequence distance (number of guanines) between the adenines and the right wing of the stem
ar_adedist		- Sequence distance (number of adenines) between the adenines and the right wing of the stem
ar_cytdist		- Sequence distance (number of cytosines) between the adenines and the right wing of the stem
ar_uradist		- Sequence distance (number of uraciles) between the adenines and the right wing of the stem
ar_bpdist		- Number of base pairs that involve nucleotides between the adenines and the right wing of the stem
ar_lbpdist		- Number of closest to 5'-end nucleotides of base pairs between the adenines and the right wing of the stem
ar_rbpdist		- Number of closest to 3'-end nucleotides of base pairs between the adenines and the right wing of the stem
ar_lwingdist		- Number of left wings between the adenines and the right wing of the stem
ar_rwingdist		- Number of right wings between the adenines and the right wing of the stem
ar_stemdist		- Number of stems that involve any wings between the adenines and the right wing of the stem
ar_lstemdist		- Number of stems that involve left wings between the adenines and the right wing of the stem
ar_rstemdist		- Number of stems that involve right wings between the adenines and the right wing of the stem
lr_dist			- Sequence distance (number of nucleotides) between the left wing and the right wing of the stem
lr_guadist		- Sequence distance (number of guanines) between the left wing and the right wing of the stem
lr_adedist		- Sequence distance (number of adenines) between the left wing and the right wing of the stem
lr_cytdist		- Sequence distance (number of cytosines) between the left wing and the right wing of the stem
lr_uradist		- Sequence distance (number of uraciles) between the left wing and the right wing of the stem
lr_bpdist		- Number of base pairs that involve nucleotides between the left wing and the right wing of the stem
lr_lbpdist		- Number of closest to 5'-end nucleotides of base pairs between the left wing and the right wing of the stem
lr_rbpdist		- Number of closest to 3'-end nucleotides of base pairs between the left wing and the right wing of the stem
lr_lwingdist		- Number of left wings between the left wing and the right wing of the stem
lr_rwingdist		- Number of right wings between the left wing and the right wing of the stem
lr_stemdist		- Number of stems that involve any wings between the left wing and the right wing of the stem
lr_lstemdist		- Number of stems that involve left wings between the left wing and the right wing of the stem
lr_rstemdist		- Number of stems that involve right wings between the left wing and the right wing of the stem
atotheleft		- Adenines are closer to 5'-end than the left wing of the stem (1 - yes, 0 - no)
abetweenlcloser		- Adenines are between the stem wings in sequence terms and closer to the left wing (1 - yes, 0 - no)
abetweenrcloser		- Adenines are between the stem wings in sequence terms and closer to the right wing (1 - yes, 0 - no)
atotheright		- Adenines are closer to 3'-end than the right wing of the stem (1 - yes, 0 - no)
a-1w_eq_l-1w		- Wing preceding the adenines is the wing preceding the left wing of the stem (1 - yes, 0 - no)
a-1w_eq_l0w		- Wing preceding the adenines is the left wing of the stem (1 - yes, 0 - no)
a-1w_eq_l1w		- Wing preceding the adenines is the wing following the left wing of the stem (1 - yes, 0 - no)
a1w_eq_l-1w		- Wing following the adenines is the wing preceding the left wing of the stem (1 - yes, 0 - no)
a1w_eq_l0w		- Wing following the adenines is the left wing of the stem (1 - yes, 0 - no)
a1w_eq_l1w		- Wing following the adenines is the wing following the left wing of the stem (1 - yes, 0 - no)
a-1w_eq_r-1w		- Wing preceding the adenines is the wing preceding the right wing of the stem (1 - yes, 0 - no)
a-1w_eq_r0w		- Wing preceding the adenines is the right wing of the stem (1 - yes, 0 - no)
a-1w_eq_r1w		- Wing preceding the adenines is the wing following the right wing of the stem (1 - yes, 0 - no)
a1w_eq_r-1w		- Wing following the adenines is the wing preceding the right wing of the stem (1 - yes, 0 - no)
a1w_eq_r0w		- Wing following the adenines is the right wing of the stem (1 - yes, 0 - no)
a1w_eq_r1w		- Wing following the adenines is the wing following the right wing of the stem (1 - yes, 0 - no)
l-1w_eq_r0w		- Wing preceding the left wing of the stem is the right wing of the stem (1 - yes, 0 - no)
l-1w_eq_r1w		- Wing preceding the left wing of the stem is the wing following the right wing of the stem (1 - yes, 0 - no)
l0w_eq_r-1w		- The left wing of the stem is the wing preceding the right wing of the stem (1 - yes, 0 - no)
l0w_eq_r1w		- The left wing of the stem is the wing following the right wing of the stem (1 - yes, 0 - no)
l1w_eq_r-1w		- Wing following the left wing of the stem is the wing preceding the right wing of the stem (1 - yes, 0 - no)
l1w_eq_r0w		- Wing following the left wing of the stem is the right wing of the stem (1 - yes, 0 - no)
a-1t_eq_l-1t		- Thread preceding the adenines is the thread preceding the left wing of the stem (1 - yes, 0 - no)
a-1t_eq_l1t		- Thread preceding the adenines is the thread following the left wing of the stem (1 - yes, 0 - no)
a0t_eq_l-1t		- Adenines' thread is the thread preceding the left wing of the stem (1 - yes, 0 - no)
a0t_eq_l1t		- Adenines' thread is the thread following the left wing of the stem (1 - yes, 0 - no)
a1t_eq_l-1t		- Thread following the adenines is the thread preceding the left wing of the stem (1 - yes, 0 - no)
a1t_eq_l1t		- Thread following the adenines is the thread following the left wing of the stem (1 - yes, 0 - no)
a-1t_eq_r-1t		- Thread preceding the adenines is the thread preceding the right wing of the stem (1 - yes, 0 - no)
a-1t_eq_r1t		- Thread preceding the adenines is the thread following the right wing of the stem (1 - yes, 0 - no)
a0t_eq_r-1t		- Adenines' thread is the thread preceding the right wing of the stem (1 - yes, 0 - no)
a0t_eq_r1t		- Adenines' thread is the thread following the right wing of the stem (1 - yes, 0 - no)
a1t_eq_r-1t		- Thread following the adenines is the thread preceding the right wing of the stem (1 - yes, 0 - no)
a1t_eq_r1t		- Thread following the adenines is the thread following the right wing of the stem (1 - yes, 0 - no)
l-1t_eq_r1t		- Thread preceding the left wing of the stem is the thread following the right wing of the stem (1 - yes, 0 - no)
l1t_eq_r-1t		- Thread following the left wing of the stem is the thread preceding the right wing of the stem (1 - yes, 0 - no)
a-1t_bc			- Thread preceding the adenines belongs to a classical bulge (1 - yes, 0 - no)
a-1t_bi			- Thread preceding the adenines belongs to an isolated bulge (1 - yes, 0 - no)
a-1t_bp			- Thread preceding the adenines belongs to a pseudoknotted bulge (1 - yes, 0 - no)
a-1t_hc			- Thread preceding the adenines belongs to a classical hairpin (1 - yes, 0 - no)
a-1t_hi			- Thread preceding the adenines belongs to an isolated hairpin (1 - yes, 0 - no)
a-1t_hp			- Thread preceding the adenines belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
a-1t_ic			- Thread preceding the adenines belongs to a classical internal loop (1 - yes, 0 - no)
a-1t_ii			- Thread preceding the adenines belongs to an isolated internal loop (1 - yes, 0 - no)
a-1t_ip			- Thread preceding the adenines belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
a-1t_jc			- Thread preceding the adenines belongs to a classical junction (1 - yes, 0 - no)
a-1t_ji			- Thread preceding the adenines belongs to an isolated junction (1 - yes, 0 - no)
a-1t_jp			- Thread preceding the adenines belongs to a pseudoknotted junction (1 - yes, 0 - no)
a-1t_fl			- Length (number of nucleotides) of the thread preceding the adenines (1 - yes, 0 - no)
a-1t_gcont		- Number of guanines of the thread preceding the adenines
a-1t_acont		- Number of adenines of the thread preceding the adenines
a-1t_ccont		- Number of cytosines of the thread preceding the adenines
a-1t_ucont		- Number of uraciles of the thread preceding the adenines
a-1w_fl			- Length (number of nucleotides) of the wing preceding the adenines
a-1w_gcont		- Number of guanines of the wing preceding the adenines
a-1w_acont		- Number of adenines of the wing preceding the adenines
a-1w_ccont		- Number of cytosines of the wing preceding the adenines
a-1w_ucont		- Number of uraciles of the wing preceding the adenines
a0t_bc			- Adenines' thread belongs to a classical bulge (1 - yes, 0 - no)
a0t_bi			- Adenines' thread belongs to an isolated bulge (1 - yes, 0 - no)
a0t_bp			- Adenines' thread belongs to a pseudoknotted bulge (1 - yes, 0 - no)
a0t_hc			- Adenines' thread belongs to a classical hairpin (1 - yes, 0 - no)
a0t_hi			- Adenines' thread belongs to an isolated hairpin (1 - yes, 0 - no)
a0t_hp			- Adenines' thread belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
a0t_ic			- Adenines' thread belongs to a classical internal loop (1 - yes, 0 - no)
a0t_ii			- Adenines' thread belongs to an isolated internal loop (1 - yes, 0 - no)
a0t_ip			- Adenines' thread belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
a0t_jc			- Adenines' thread belongs to a classical junction (1 - yes, 0 - no)
a0t_ji			- Adenines' thread belongs to an isolated junction (1 - yes, 0 - no)
a0t_jp			- Adenines' thread belongs to a pseudoknotted junction (1 - yes, 0 - no)
a0t_fl			- Length (number of nucleotides) of the adenines' thread
a0t_gcont		- Number of guanines of the adenines' thread
a0t_acont		- Number of adenines of the adenines' thread
a0t_ccont		- Number of cytosines of the adenines' thread
a0t_ucont		- Number of uraciles of the adenines' thread
a1t_bc			- Thread following the adenines belongs to a classical bulge (1 - yes, 0 - no)
a1t_bi			- Thread following the adenines belongs to an isolated bulge (1 - yes, 0 - no)
a1t_bp			- Thread following the adenines belongs to a pseudoknotted bulge (1 - yes, 0 - no)
a1t_hc			- Thread following the adenines belongs to a classical hairpin (1 - yes, 0 - no)
a1t_hi			- Thread following the adenines belongs to an isolated hairpin (1 - yes, 0 - no)
a1t_hp			- Thread following the adenines belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
a1t_ic			- Thread following the adenines belongs to a classical internal loop (1 - yes, 0 - no)
a1t_ii			- Thread following the adenines belongs to an isolated internal loop (1 - yes, 0 - no)
a1t_ip			- Thread following the adenines belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
a1t_jc			- Thread following the adenines belongs to a classical junction (1 - yes, 0 - no)
a1t_ji			- Thread following the adenines belongs to an isolated junction (1 - yes, 0 - no)
a1t_jp			- Thread following the adenines belongs to a pseudoknotted junction (1 - yes, 0 - no)
a1t_fl			- Length (number of nucleotides) of the thread following the adenines
a1t_gcont		- Number of guanines of the thread following the adenines
a1t_acont		- Number of adenines of the thread following the adenines
a1t_ccont		- Number of cytosines of the thread following the adenines
a1t_ucont		- Number of uraciles of the thread following the adenines
a1w_fl			- Length (number of nucleotides) of the wing following the adenines
a1w_gcont		- Number of guanines of the wing following the adenines
a1w_acont		- Number of adenines of the wing following the adenines
a1w_ccont		- Number of cytosines of the wing following the adenines
a1w_ucont		- Number of uraciles of the wing following the adenines
l-1t_bc			- Thread preceding the left wing of the stem belongs to a classical bulge (1 - yes, 0 - no)
l-1t_bi			- Thread preceding the left wing of the stem belongs to an isolated bulge (1 - yes, 0 - no)
l-1t_bp			- Thread preceding the left wing of the stem belongs to a pseudoknotted bulge (1 - yes, 0 - no)
l-1t_hc			- Thread preceding the left wing of the stem belongs to a classical hairpin (1 - yes, 0 - no)
l-1t_hi			- Thread preceding the left wing of the stem belongs to an isolated hairpin (1 - yes, 0 - no)
l-1t_hp			- Thread preceding the left wing of the stem belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
l-1t_ic			- Thread preceding the left wing of the stem belongs to a classical internal loop (1 - yes, 0 - no)
l-1t_ii			- Thread preceding the left wing of the stem belongs to an isolated internal loop (1 - yes, 0 - no)
l-1t_ip			- Thread preceding the left wing of the stem belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
l-1t_jc			- Thread preceding the left wing of the stem belongs to a classical junction (1 - yes, 0 - no)
l-1t_ji			- Thread preceding the left wing of the stem belongs to an isolated junction (1 - yes, 0 - no)
l-1t_jp			- Thread preceding the left wing of the stem belongs to a pseudoknotted junction (1 - yes, 0 - no)
l-1t_fl			- Length (number of nucleotides) of the thread preceding the left wing of the stem
l-1t_gcont		- Number of guanines of the thread preceding the left wing of the stem
l-1t_acont		- Number of adenines of the thread preceding the left wing of the stem
l-1t_ccont		- Number of cytosines of the thread preceding the left wing of the stem
l-1t_ucont		- Number of uraciles of the thread preceding the left wing of the stem
l-1w_fl			- Length (number of nucleotides) of the wing preceding the left wing of the stem
l-1w_gcont		- Number of guanines of the wing preceding the left wing of the stem
l-1w_acont		- Number of adenines of the wing preceding the left wing of the stem
l-1w_ccont		- Number of cytosines of the wing preceding the left wing of the stem
l-1w_ucont		- Number of uraciles of the wing preceding the left wing of the stem
l0w_fl			- Length (number of nucleotides) of the left wing of the stem
l0w_gcont		- Number of guanines of the left wing of the stem
l0w_acont		- Number of adenines of the left wing of the stem
l0w_ccont		- Number of cytosines of the left wing of the stem
l0w_ucont		- Number of uraciles of the left wing of the stem
l1t_bc			- Thread following the left wing of the stem belongs to a classical bulge (1 - yes, 0 - no)
l1t_bi			- Thread following the left wing of the stem belongs to an isolated bulge (1 - yes, 0 - no)
l1t_bp			- Thread following the left wing of the stem belongs to a pseudoknotted bulge (1 - yes, 0 - no)
l1t_hc			- Thread following the left wing of the stem belongs to a classical hairpin (1 - yes, 0 - no)
l1t_hi			- Thread following the left wing of the stem belongs to an isolated hairpin (1 - yes, 0 - no)
l1t_hp			- Thread following the left wing of the stem belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
l1t_ic			- Thread following the left wing of the stem belongs to a classical internal loop (1 - yes, 0 - no)
l1t_ii			- Thread following the left wing of the stem belongs to an isolated internal loop (1 - yes, 0 - no)
l1t_ip			- Thread following the left wing of the stem belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
l1t_jc			- Thread following the left wing of the stem belongs to a classical junction (1 - yes, 0 - no)
l1t_ji			- Thread following the left wing of the stem belongs to an isolated junction (1 - yes, 0 - no)
l1t_jp			- Thread following the left wing of the stem belongs to a pseudoknotted junction (1 - yes, 0 - no)
l1t_fl			- Length (number of nucleotides) of the thread following the left wing of the stem
l1t_gcont		- Number of guanines of the thread following the left wing of the stem
l1t_acont		- Number of adenines of the thread following the left wing of the stem
l1t_ccont		- Number of cytosines of the thread following the left wing of the stem
l1t_ucont		- Number of uraciles of the thread following the left wing of the stem
l1w_fl			- Length (number of nucleotides) of the wing following the left wing of the stem
l1w_gcont		- Number of guanines of the wing following the left wing of the stem
l1w_acont		- Number of adenines of the wing following the left wing of the stem
l1w_ccont		- Number of cytosines of the wing following the left wing of the stem
l1w_ucont		- Number of uraciles of the wing following the left wing of the stem
r-1t_bc			- Thread preceding the right wing of the stem belongs to a classical bulge (1 - yes, 0 - no)
r-1t_bi			- Thread preceding the right wing of the stem belongs to an isolated bulge (1 - yes, 0 - no)
r-1t_bp			- Thread preceding the right wing of the stem belongs to a pseudoknotted bulge (1 - yes, 0 - no)
r-1t_hc			- Thread preceding the right wing of the stem belongs to a classical hairpin (1 - yes, 0 - no)
r-1t_hi			- Thread preceding the right wing of the stem belongs to an isolated hairpin (1 - yes, 0 - no)
r-1t_hp			- Thread preceding the right wing of the stem belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
r-1t_ic			- Thread preceding the right wing of the stem belongs to a classical internal loop (1 - yes, 0 - no)
r-1t_ii			- Thread preceding the right wing of the stem belongs to an isolated internal loop (1 - yes, 0 - no)
r-1t_ip			- Thread preceding the right wing of the stem belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
r-1t_jc			- Thread preceding the right wing of the stem belongs to a classical junction (1 - yes, 0 - no)
r-1t_ji			- Thread preceding the right wing of the stem belongs to an isolated junction (1 - yes, 0 - no)
r-1t_jp			- Thread preceding the right wing of the stem belongs to a pseudoknotted junction (1 - yes, 0 - no)
r-1t_fl			- Length (number of nucleotides) of the thread preceding the right wing of the stem
r-1t_gcont		- Number of guanines of the thread preceding the right wing of the stem
r-1t_acont		- Number of adenines of the thread preceding the right wing of the stem
r-1t_ccont		- Number of cytosines of the thread preceding the right wing of the stem
r-1t_ucont		- Number of uraciles of the thread preceding the right wing of the stem
r-1w_fl			- Length (number of nucleotides) of the wing preceding the right wing of the stem
r-1w_gcont		- Number of guanines of the wing preceding the right wing of the stem
r-1w_acont		- Number of adenines of the wing preceding the right wing of the stem
r-1w_ccont		- Number of cytosines of the wing preceding the right wing of the stem
r-1w_ucont		- Number of uraciles of the wing preceding the right wing of the stem
r0w_gcont		- Number of guanines of the right wing of the stem
r0w_acont		- Number of adenines of the right wing of the stem
r0w_ccont		- Number of cytosines of the right wing of the stem
r0w_ucont		- Number of uraciles of the right wing of the stem
r1t_bc			- Thread following the right wing of the stem belongs to a classical bulge (1 - yes, 0 - no)
r1t_bi			- Thread following the right wing of the stem belongs to an isolated bulge (1 - yes, 0 - no)
r1t_bp			- Thread following the right wing of the stem belongs to a pseudoknotted bulge (1 - yes, 0 - no)
r1t_hc			- Thread following the right wing of the stem belongs to a classical hairpin (1 - yes, 0 - no)
r1t_hi			- Thread following the right wing of the stem belongs to an isolated hairpin (1 - yes, 0 - no)
r1t_hp			- Thread following the right wing of the stem belongs to a pseudoknotted hairpin (1 - yes, 0 - no)
r1t_ic			- Thread following the right wing of the stem belongs to a classical internal loop (1 - yes, 0 - no)
r1t_ii			- Thread following the right wing of the stem belongs to an isolated internal loop (1 - yes, 0 - no)
r1t_ip			- Thread following the right wing of the stem belongs to a pseudoknotted internal loop (1 - yes, 0 - no)
r1t_jc			- Thread following the right wing of the stem belongs to a classical junction (1 - yes, 0 - no)
r1t_ji			- Thread following the right wing of the stem belongs to an isolated junction (1 - yes, 0 - no)
r1t_jp			- Thread following the right wing of the stem belongs to a pseudoknotted junction (1 - yes, 0 - no)
r1t_fl			- Length (number of nucleotides) of the thread following the right wing of the stem
r1t_gcont		- Number of guanines of the thread following the right wing of the stem
r1t_acont		- Number of adenines of the thread following the right wing of the stem
r1t_ccont		- Number of cytosines of the thread following the right wing of the stem
r1t_ucont		- Number of uraciles of the thread following the right wing of the stem
r1w_fl			- Length (number of nucleotides) of the wing following the right wing of the stem
r1w_gcont		- Number of guanines of the wing following the right wing of the stem
r1w_acont		- Number of adenines of the wing following the right wing of the stem
r1w_ccont		- Number of cytosines of the wing following the right wing of the stem
r1w_ucont		- Number of uraciles of the wing following the right wing of the stem
stem_bp1		- 1st base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp2		- 2nd base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp3		- 3rd base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp4		- 4th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp5		- 5th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp6		- 6th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp7		- 7th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp8		- 8th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp9		- 9th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_bp10		- 10th base pair of the stem (GC = 6; CG = 5; AU = 4; UA = 3; GU = 2; UG = 1; 0 else)
stem_gccont		- Number of G-C base pairs of the stem
stem_aucont		- Number of A-U base pairs of the stem
stem_gucont		- Number of G-U base pairs of the stem
towersize		- Size of the tower that the stem belongs to
numintower		- Ordinal number of the stem within the tower
towerpseudo		- The tower is pseudoknotted (1 - yes, 0 - no)
towerh			- The tower ends with a hairpin (1 - yes, 0 - no)
pseudo			- The stem is pseudoknotted (1 - yes, 0 - no)
numinecf		- Ordinal number of the stem within the ECR
abab			- The stem is involved in an H-knot (1 - yes, 0 - no)
abacbc			- The stem is involved in a kissing loops structure (1 - yes, 0 - no)
fi			- position of the first adenine within its thread
num_of_a		- Number of adenines of the stretch
aloop_other_len		- Total length (number of nucleotides) of the loop of the adenines stretch except the adenines' thread 
aloop_other_gcont	- Number of guanines of the loop of the adenines stretch except the adenines' thread 
aloop_other_acont	- Number of adenines of the loop of the adenines stretch except the adenines' thread 
aloop_other_ccont	- Number of cytosines of the loop of the adenines stretch except the adenines' thread 
aloop_other_ucont	- Number of uraciles of the loop of the adenines stretch except the adenines' thread 
a-5_nucl		- Base in the -5 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a-4_nucl		- Base in the -4 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a-3_nucl		- Base in the -3 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a-2_nucl		- Base in the -2 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a-1_nucl		- Base in the -1 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a1_nucl			- Base in the +1 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a2_nucl			- Base in the +2 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a3_nucl			- Base in the +3 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a4_nucl			- Base in the +4 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
a5_nucl			- Base in the +5 position relative to the adenines (G = 4; A = 3; C = 2; U = 1; 0 else)
pos			- target feature (1 - positive; 0 - negative)
```

