# Jupyter notebooks (JNBs) by Laura Harris
Each zip file comes with at least one JNB and associated example input file(s).

Available JNBs:
1) rowcopy
2) z-score - two JNBs available, one using manual calculations and the other using SciPy
3) Stouffer's combined p-value - Check out https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.combine_pvalues.html for more information on options and information on Stouffer’s Z-score method to combine p-values
5) Leave one out cross validation (LOOCV) - Check out https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.LeaveOneOut.html for more information on options and information on how this notebook implements LOOCV
6) Receiver operator characteristics (ROC) curve - Check out https://pubmed.ncbi.nlm.nih.gov/21532099/ for more information on ROC curve use in medical research
7) Adjusted p-value - JNB that calculates Mann–Whitney U test statistic and p-value, then uses Bonferroni correction to adjust the p-values for multiple hypothesis testing. The program can be converted easily to perform other post-hoc tests, such as Benjamini Hochberg. Thanks to Khemlal Nirmalkar for the example data.
8) Decision tree with random forest - JNB uses a Kaggle dataset with 10 attributes of breast cancer tumors. The JNB divides the dataset into 70% training samples and 30% testing samples. For the training set, the JNB calculates the difference between the mean and worst measurements for each attribute and adjusts by the attribute's standard error, all as provided in the dataset. The JNB then uses this metric to identify cut-offs for decision making for each attribute, then builds a decision tree based on those cut-offs. A random forest approach is used to collect the decisions from each attribute and the attribute sum guesses whether a tumor was cancerous.
9) Log curve predictions - JNB uses COVID hospitalization data to predict valleys and peaks
10) Example basic artificial neural network (ANN) - JNB that demonstrates a basic ANN using the keras package.

New to using JNBs? The Institute for Cyber-Enabled Research (ICER) at Michigan State University can help! In less than an hour, this non-credit, self-paced training workshop introduces you to JNBs and demonstrates how to use notebook features. The workshop provides example notebooks and a project where you create your own notebook, which is reviewed by a real instructor. No prior knowledge is required for this workshop but you must have access to JNB. Links to other free, self-paced training workshops are provided to help you get access to JNBs through installing Anaconda on your personal computer. Registration: https://apps.d2l.msu.edu/selfenroll/course/1337753
