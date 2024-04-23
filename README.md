# Built a Parkinson's Disease Detection Model using Support Vector Machine

Dataset Source : https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set

# Method Used
Support vector machine (SVM):
Support Vector Machine (SVM) are a set of supervised learning methods used for classification, regression, and outlier detection. Advantages of support vector machines: Effective for high-dimensional spaces. It is still valid if the number of measurements is greater than the number of samples.

# Model Explanation
Parkinson’s disease can be detected using speech. The phonation is the most affected part of the speech i.e. the sound we make when we pronounce the vowels. We have used the database of the speech samples containing the phonation from the affected and healthy people. Speech signals or the voice samples consists of voice samples of people. The samples of healthy people are also collected for the comparative study. The Test Data belongs to 56 subjects. During the collection of this dataset, 48 people are asked to say only the sustained vowels 'a' and 'o' three times respectively. Total of 195 recordings are obtained from the repository. In the training phase the pre-processing of these signals is done for feature extraction by SVM feature in Scikit-learn. The features extracted are jitter, shimmer, NHR, HNR, mean and median pitch, number of pulses and periods, minimum and maximum period, SD, SD of period, number and degree of voice breaks. All these features differ from patient to patient depending upon the fact how much Parkinson’s disease has progressed. After extracting all the features we will do dimensionality reduction of the features using particle swarm optimization(PSO), In this optimization method it works like swarm particle and reduce the features selection to a minimum, optimization involves in achieving better result in less computation, after selection of the features, The features are used to train the SVM classifier and the model is trained.


![Model image](https://github.com/AmanBhagat23/Parkinsons_Disease_Detection_Model/assets/145958790/c3f7f767-94ec-4f66-a1fb-2632bd33e110)
