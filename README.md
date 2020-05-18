
## Description of RNA secondary structure context improves classification and prediction of A-minor motifs

### List of files:

#### MLdataset.csv - list of A-stems with their features used for training and prediction by the machine learning algorithm (features' description see below)


### MLdataset.csv - description of columns:

```
PDB_CH			- PDB entry & RNA chain identifier, separated with an underscore (not a feature)
DSSR			- 
Types			- 
SecStruct		- 
ds			- 
dbps			- 
dbc			- 
dbi			- 
dbp			- 
dhc			- 
dhi			- 
dhp			- 
dic			- 
dii			- 
dip			- 
djc			- 
dji			- 
djp			- 
lc			- 
lr			- 
al_dist			- 
al_guadist		- 
al_adedist		- 
al_cytdist		- 
al_uradist		- 
al_bpdist		- 
al_lbpdist		- 
al_rbpdist		- 
al_lwingdist		- 
al_rwingdist		- 
al_stemdist		- 
al_lstemdist		- 
al_rstemdist		- 
ar_dist			- 
ar_guadist		- 
ar_adedist		- 
ar_cytdist		- 
ar_uradist		- 
ar_bpdist		- 
ar_lbpdist		- 
ar_rbpdist		- 
ar_lwingdist		- 
ar_rwingdist		- 
ar_stemdist		- 
ar_lstemdist		- 
ar_rstemdist		- 
lr_dist			- 
lr_guadist		- 
lr_adedist		- 
lr_cytdist		- 
lr_uradist		- 
lr_bpdist		- 
lr_lbpdist		- 
lr_rbpdist		- 
lr_lwingdist		- 
lr_rwingdist		- 
lr_stemdist		- 
lr_lstemdist		- 
lr_rstemdist		- 
atotheleft		- 
abetweenlcloser		- 
abetweenrcloser		- 
atotheright		- 
a-1w_eq_l-1w		- 
a-1w_eq_l0w		- 
a-1w_eq_l1w		- 
a1w_eq_l-1w		- 
a1w_eq_l0w		- 
a1w_eq_l1w		- 
a-1w_eq_r-1w		- 
a-1w_eq_r0w		- 
a-1w_eq_r1w		- 
a1w_eq_r-1w		- 
a1w_eq_r0w		- 
a1w_eq_r1w		- 
l-1w_eq_r0w		- 
l-1w_eq_r1w		- 
l0w_eq_r-1w		- 
l0w_eq_r1w		- 
l1w_eq_r-1w		- 
l1w_eq_r0w		- 
a-1t_eq_l-1t		- 
a-1t_eq_l1t		- 
a0t_eq_l-1t		- 
a0t_eq_l1t		- 
a1t_eq_l-1t		- 
a1t_eq_l1t		- 
a-1t_eq_r-1t		- 
a-1t_eq_r1t		- 
a0t_eq_r-1t		- 
a0t_eq_r1t		- 
a1t_eq_r-1t		- 
a1t_eq_r1t		- 
l-1t_eq_r1t		- 
l1t_eq_r-1t		- 
a-1t_bc			- 
a-1t_bi			- 
a-1t_bp			- 
a-1t_hc			- 
a-1t_hi			- 
a-1t_hp			- 
a-1t_ic			- 
a-1t_ii			- 
a-1t_ip			- 
a-1t_jc			- 
a-1t_ji			- 
a-1t_jp			- 
a-1t_fl			- 
a-1t_gcont		- 
a-1t_acont		- 
a-1t_ccont		- 
a-1t_ucont		- 
a-1w_fl			- 
a-1w_gcont		- 
a-1w_acont		- 
a-1w_ccont		- 
a-1w_ucont		- 
a0t_bc			- 
a0t_bi			- 
a0t_bp			- 
a0t_hc			- 
a0t_hi			- 
a0t_hp			- 
a0t_ic			- 
a0t_ii			- 
a0t_ip			- 
a0t_jc			- 
a0t_ji			- 
a0t_jp			- 
a0t_fl			- 
a0t_gcont		- 
a0t_acont		- 
a0t_ccont		- 
a0t_ucont		- 
a1t_bc			- 
a1t_bi			- 
a1t_bp			- 
a1t_hc			- 
a1t_hi			- 
a1t_hp			- 
a1t_ic			- 
a1t_ii			- 
a1t_ip			- 
a1t_jc			- 
a1t_ji			- 
a1t_jp			- 
a1t_fl			- 
a1t_gcont		- 
a1t_acont		- 
a1t_ccont		- 
a1t_ucont		- 
a1w_fl			- 
a1w_gcont		- 
a1w_acont		- 
a1w_ccont		- 
a1w_ucont		- 
l-1t_bc		- 
l-1t_bi		- 
l-1t_bp		- 
l-1t_hc		- 
l-1t_hi		- 
l-1t_hp		- 
l-1t_ic		- 
l-1t_ii		- 
l-1t_ip		- 
l-1t_jc		- 
l-1t_ji		- 
l-1t_jp		- 
l-1t_fl		- 
l-1t_gcont		- 
l-1t_acont		- 
l-1t_ccont		- 
l-1t_ucont		- 
l-1w_fl		- 
l-1w_gcont		- 
l-1w_acont		- 
l-1w_ccont		- 
l-1w_ucont		- 
l0w_fl			- 
l0w_gcont		- 
l0w_acont		- 
l0w_ccont		- 
l0w_ucont		- 
l1t_bc			- 
l1t_bi			- 
l1t_bp			- 
l1t_hc			- 
l1t_hi			- 
l1t_hp			- 
l1t_ic			- 
l1t_ii			- 
l1t_ip			- 
l1t_jc			- 
l1t_ji			- 
l1t_jp			- 
l1t_fl			- 
l1t_gcont		- 
l1t_acont		- 
l1t_ccont		- 
l1t_ucont		- 
l1w_fl			- 
l1w_gcont		- 
l1w_acont		- 
l1w_ccont		- 
l1w_ucont		- 
r-1t_bc			- 
r-1t_bi			- 
r-1t_bp			- 
r-1t_hc			- 
r-1t_hi			- 
r-1t_hp			- 
r-1t_ic			- 
r-1t_ii			- 
r-1t_ip			- 
r-1t_jc			- 
r-1t_ji			- 
r-1t_jp			- 
r-1t_fl			- 
r-1t_gcont		- 
r-1t_acont		- 
r-1t_ccont		- 
r-1t_ucont		- 
r-1w_fl			- 
r-1w_gcont		- 
r-1w_acont		- 
r-1w_ccont		- 
r-1w_ucont		- 
r0w_gcont		- 
r0w_acont		- 
r0w_ccont		- 
r0w_ucont		- 
r1t_bc				- 
r1t_bi				- 
r1t_bp				- 
r1t_hc				- 
r1t_hi				- 
r1t_hp				- 
r1t_ic				- 
r1t_ii				- 
r1t_ip				- 
r1t_jc				- 
r1t_ji				- 
r1t_jp				- 
r1t_fl				- 
r1t_gcont		- 
r1t_acont		- 
r1t_ccont		- 
r1t_ucont		- 
r1w_fl				- 
r1w_gcont		- 
r1w_acont		- 
r1w_ccont		- 
r1w_ucont		- 
stem_bp1		- 
stem_bp2		- 
stem_bp3		- 
stem_bp4		- 
stem_bp5		- 
stem_bp6		- 
stem_bp7		- 
stem_bp8		- 
stem_bp9		- 
stem_bp10		- 
stem_gccont		- 
stem_aucont		- 
stem_gucont		- 
towersize		- 
numintower		- 
towerpseudo		- 
towerh			- 
pseudo			- 
numinecf		- 
abab			- 
abacbc			- 
fi			- 
num_of_a		- 
aloop_other_len		- 
aloop_other_gcont	- 
aloop_other_acont	- 
aloop_other_ccont	- 
aloop_other_ucont	- 
a-5_nucl		- 
a-4_nucl		- 
a-3_nucl		- 
a-2_nucl		- 
a-1_nucl		- 
a1_nucl			- 
a2_nucl			- 
a3_nucl			- 
a4_nucl			- 
a5_nucl			- 
pos			- target feature (1 - positive; 0 - negative)
```

