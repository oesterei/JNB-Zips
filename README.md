# Jupyter notebooks (JNBs)
Each zip file comes with at least one JNB and associated example input file(s).

Available JNBs:
1) rowcopy
2) z-score - two JNBs available, one using manual calculations and the other using SciPy
3) Stouffer's combined p-value - Check out https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.combine_pvalues.html for more information on options and information on Stouffer’s Z-score method to combine p-values
4) Cross validation (CV) - Contains 2 Python scripts, one performing k-fold CV and the other performing leave one out cross validation (LOOCV) using SK-learn. For LOOCV, check out https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.LeaveOneOut.html for more information on options and information.
5) Receiver operator characteristics (ROC) curve - Contains 2 Python scripts, one performing ROC on multiple samples and one performing ROC and k-fold CV on a single sample. Check out https://pubmed.ncbi.nlm.nih.gov/21532099/ for more information on ROC curve use in medical research
6) Adjusted p-value - JNB that calculates Mann–Whitney U test statistic and p-value, then uses Bonferroni correction to adjust the p-values for multiple hypothesis testing. The program can be converted easily to perform other post-hoc tests, such as Benjamini Hochberg. Thanks to Khemlal Nirmalkar for the example data.
7) Conceptual random forest - JNB uses a Kaggle dataset with 10 attributes of breast cancer tumors. The JNB divides the dataset into 70% training samples and 30% testing samples. For the training set, the JNB calculates the difference between the mean and worst measurements for each attribute and adjusts by the attribute's standard error, all as provided in the dataset. The JNB then uses this metric to identify cut-offs for decision making for each attribute, then builds a decision tree based on those cut-offs. A random forest approach is used to collect the decisions from each attribute and the attribute sum guesses whether a tumor was cancerous.
8) Random forest via SKLearn - JNB uses same dataset as the #7. The JNB divides the dataset into 70% training samples and 30% testing samples then generates a random forest from all 10 attributes. The notebook then identified the most important attributes and refines data collection by re-generating a random forest from selected attributes for accuracy comparison.
9) Log curve predictions - JNB uses COVID hospitalization data to predict valleys and peaks
10) Example basic artificial neural network (ANN) - JNB that demonstrates a basic ANN using the keras package.
11) PCAexample performs log2 normalization on a dataset followed by principal component analysis (PCA).
12) RNA-Seq by Expectation Maximization (RSEM) adjusts for overall read depth (the sum of the read counts per sample).

New to using JNBs? Check out the JNB training in my Courses repository. In less than an hour, this non-credit, self-paced training workshop introduces you to JNBs and demonstrates how to use notebook features. The workshop provides example notebooks and a project where you create your own notebook, which is reviewed by a real instructor. No prior knowledge is required for this workshop but you must have access to JNB. Access to JNBs through installing Anaconda on your personal computer is best, and instructions for installing Anaconda are also in my Courses repository.
