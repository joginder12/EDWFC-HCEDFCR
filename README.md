# Predicting drug‑resistant miRNAs in cancer (EDWFC-HCEDFCR)
## Abstract
MicroRNAs (miRNAs) are small noncoding RNAs that play a vital role in controlling drug sensitivity/resistance in cancer.
Hence, the effectiveness of cancer treatment can be significantly improved by identifying these miRNAs. We reviewed the
studies that emphasize the identification of miRNAs associated with drug resistance in cancer. Two computational methods
are also developed to identify the miRNAs associated with drug resistance. In the first method, the Euclidean distance with
weighted fold change (EDWFC) score is developed. Here, the Euclidean distance and fold change, computed using the averages
of control and resistant expressions, are multiplied by varying the power of fold change to minimize the average rank of
miRNAs. The miRNAs are then sorted in descending order according to the EDWFC value which provides superior results as
compared to existing feature/gene selection methods in terms of multiple performance measures. In the second method, namely
the histogram-based clustering and Euclidean distance with fold change-based ranking (HCEDFCR), the miRNAs are first
divided into different clusters using a novel histogram-based clustering method. Then, the product of the Euclidean distance
and the fold change value, using the control and resistant miRNA expressions, are used to rank the clusters and the miRNAs
inside the clusters. Finally, a portion of the miRNAs is selected from the top of the rank list in every cluster. For most of the
datasets, the top 20 miRNAs selected using the first method and the first three miRNAs of the top three clusters obtained using
the second method contain the miRNAs associated with cancer drug resistance.

## Datasets

## Cite the Article
Kundu, A., Singh, J., Pal, J. K., & Ray, S. S. (2022). Predicting drug-resistant miRNAs in cancer. Network Modeling Analysis in Health Informatics and Bioinformatics, 12(1), 6.

@article{kundu2022predicting,
  title={Predicting drug-resistant miRNAs in cancer},
  author={Kundu, Amrita and Singh, Joginder and Pal, Jayanta Kumar and Ray, Shubhra Sankar},
  journal={Network Modeling Analysis in Health Informatics and Bioinformatics},
  volume={12},
  number={1},
  pages={6},
  year={2022},
  publisher={Springer}
}
