
## Dataset Overview: 2VO Animal Model & 9.4T MRI Sequences

This dataset contains longitudinal neuroimaging data from a rat model of chronic cerebral hypoperfusion induced by **permanent bilateral common carotid artery occlusion (Two-Vessel Occlusion, or 2VO)**. 

All magnetic resonance imaging (MRI) scans were acquired using a high-field **9.4 Tesla micro-MRI system**. 

### MRI Acquisition Sequences

The dataset for each animal/timepoint includes the following MRI sequences (TIF):

* **T2-weighted Images (`T2`)**: High-resolution structural images used for anatomical reference, evaluating tissue morphology, and identifying macrostructural changes.
* **T2 Maps (`T2_map`)**: Quantitative T2 relaxation time maps optimized for detecting localized tissue edema, neuroinflammation, and subtle ischemic microstructural alterations.
* **Pre-Contrast T1 (`T1_pre`)**: Baseline T1-weighted structural scans acquired prior to the administration of the contrast agent.
* **Post-Contrast T1 (`T1_post`)**: T1-weighted scans acquired following the intravenous injection of a Gadolinium-based contrast agent (**Gd**). This sequence is optimized for evaluating **blood-brain barrier (BBB) permeability** and mapping regional Gd-extravasation/leakage percentages over time.
