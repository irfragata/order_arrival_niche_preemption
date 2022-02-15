The file Coexistence_data_final_corr.csv contains all the raw data obtained during the study. This file was corrected a single time. This was due to the preliminary analysis and outlier detection analysis singling out two rows were there was an abnormal number of Te/Tu individuals.

Relative to the columns of the file:
Box - The number of the replicate box for each treatment/block.There are at maximum 10 boxes. Box 1-5 are from block 1 and 6-10 block 2.
Treatment - Codes for different treatments used in the experiment. We varied the initial ratio of the two mite’s species, according to the following experimental treatments: 10 T. evansi females with 10 T. urticae females (10Te10Tu), 19 T. evansi with 1 T. urticae female and reciprocal (19Te1Tu and 1Te19Tu), 20 T. evansi females (20Te), 20 T. urticae females (20Tu). To test for the effects of order of arrival we introduced 10 T. evansi females 48h before 10 T. urticae females and the reciprocal treatment (10Te48h10Tu and 10Te10Tu48h) and we introduced 19 T. evansi females 48h before introducing 1 T. urticae female and the reciprocal treatment (19Te48h1Tu and 1Te19Tu48h).
Block - Corresponds to the number of the block. The 2 blocks were done in consecutive weeks
Leaf - The number identifying the leaf that was analysed. There are 4 different leaves, from 2 to 5, 2 being the oldest leaf and 5 the youngest.
Leaflet - The smallest unit of each leaf. Each leaf has usually 5 leaflets, except for leaf number 2, were leaflets 2, 3, and 4 are united in a single leaflet.
Direction - whether the mites were found on the upper (darked green) or lower (lighter green) part of the leaflet
Te - Number of Te adult females counted after 14 days
Tu - Number of Tu adult females counted after 14 days

Leaf conversion file:
This file is used to obtain the age for the leaves from each treatment. Old codes for being added first to the box, new to being added after 14 days of female instalment

LeafDisk_exp file:
This file has the data from the leaf disk experiment that was performed with only one female per species. The columns correspond to
- Leaf_Pairs - from which leaves were the two disks cut from
- Arena - The number of the arena (between 1 and 10)
- Treatment - the species that was tested
- Inst_Te, Inst_Tu - number of Te and Tu females installed in each disk, respectively (this is redundant with the treatment column)
-Number Te, Numb Tu - number of Te and Tu adult females obtained in each leaf disk after one generation.

qPCR_results_Te_Tu_Out file:

Quantitative gene expression (Cq) data obtained for Te and Tu outbred populations and the induction (Santpoort) and suppression (Vicosa) controls (note that R was crashing with the ç on Viçosa, so it is coded as Vicosa on the file). We tested 4 genes, actin (the control), Pr1a, PPO-D and PI-IIc. Each samples was quantified three times, and the analyses were done with the averages of these three technical replicates.



