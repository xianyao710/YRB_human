# YRB_human CAGE data 
human CAGE data
description for raw data should be finished later

#Homer result and processing
[Raw Homer](https://github.com/xianyao710/YRB_human/tree/master/Homer) results for 9 training sets and 1 test set.

[Raw Meme](https://github.com/xianyao710/YRB_human/tree/master/Raw_meme) results

[filtered Meme](https://github.com/xianyao710/YRB_human/tree/master/New_meme) results using theshold -evalue 1e-20

#Tomtom motif comparison and clustering

Tomtom clustering using -thresh 0.001 -evalue
[tomtom](https://github.com/xianyao710/YRB_human/tree/master/first_run/tomtom_0.001)

Graphical analysis using networkx package

![raw training motifs](https://github.com/xianyao710/YRB_human/blob/master/figure/hg_motif_cluster.png)

![filtered using 9 degree](https://github.com/xianyao710/YRB_human/blob/master/figure/hg_motif_cluster_filter.png)

6 clusters detected

#Discussion
If these analysis and processing are good enough, we can extract consensus motif for each group.
