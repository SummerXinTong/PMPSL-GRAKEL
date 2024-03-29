Four improved multi-label classifiers to identify subcellular locations of human, animal, Gram-negative bacterial and eukaryotic proteins are proposed. Each protein is represented by its GO information and statistical results of GO information in the training dataset. The random k-labELsets (RAKEL) algorithm is adopted to tackle proteins with multiple locations and the random forest is selected as the basic classification algorithm.

The flowchart to show the construction and evaluation procedures of four classifiers is illustrated below.

![image](https://github.com/SummerXinTong/pLoc-RAKEL/blob/main/Figure.jpg)

Dataset folder: Four protein benchmark datasets for human, animal, Gram-negative bacterial and eukaryotic proteins.

Code folder: Codes for evaluating classifiers and calculating performance measurements.

Result folder: Predicted results of four classifiers under jackknife test. In each CSV file, the first column stands for the true classes and the second column stands for the predicted classes.
