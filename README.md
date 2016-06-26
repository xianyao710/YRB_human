# YRB_human CAGE data 
human CAGE data
description for raw data should be finished later

#Homer result and processing
[Raw Homer](https://github.com/xianyao710/YRB_human/tree/master/latest_result/homer_motif) results for 9 training sets and 1 test set. For example, group1.homer is the test set homer result in first round workflow running, train1.homer is the corresponding training set that contain other 9 groups. 

[Raw Meme](https://github.com/xianyao710/YRB_human/tree/master/latest_result/meme_motif) results

[renamed Meme](https://github.com/xianyao710/YRB_human/tree/master/latest_result/rename_meme) In order to cluster training set motifs, we have to rename the motif in each group. For example, the original Motif_1 in train1.meme file is renamed train_1_1.

#Tomtom motif comparison and clustering

Tomtom clustering using -thresh 0.0001 -evalue
[tomtom](https://github.com/xianyao710/YRB_human/tree/master/latest_result/Cluster_result/tomtom_out)

Graphical analysis using networkx package


![filtered using 9 degree](https://github.com/xianyao710/YRB_human/blob/master/latest_result/Cluster_result/human_clusters.png)

10 clusters that have more then 9 nodes were detected.

#Consensus motif for each cluster
By implementing [MotifSetReduce.pl](https://github.com/BrendelGroup/bghandbook/blob/master/demo/MotifSetReduce/MotifSetReduce.pl) for each cluster, we got [consensus motif](https://github.com/xianyao710/YRB_human/tree/master/latest_result/Cluster_result/cluster_consensus) and [seqLogo](https://github.com/xianyao710/YRB_human/tree/master/latest_result/Cluster_result/cluster_seqLogo) repectively.

#Discussion
Next step is to compare these motif to known motif database.