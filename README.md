# ML-Course-Project

# Dataset Information

The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes 50 features representing 101766 diabetes patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria:

* It is an inpatient encounter (a hospital admission).
* It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
* The length of stay was at least 1 day and at most 14 days.
* Laboratory tests were performed during the encounter.
* Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

# Overview

The project is based on a binary classiﬁcation problems wherein our aim is to predict whether a diabetic patient will be readmitted to the hospital or not based on the treatment received by the patient.The dataset contains 50 features and 1,01,766 instances representing the patient and hospital outcomes. At ﬁrst,data preprocessing was performedtoremoveredundant/invalidvalues.Thedatasetwas trained using Logistic Regression,SVM(both rbf and polynomial kernel),Random forest classiﬁer,MLP(3 hidden layers and 4 hidden layers) and K-Nearest Neighbour(KNN) method.The predicted accuracies are 0.6283(Logistic Regression),0.6315(SVM with ‘poly’ kernel),0.6153(Random forest),0.8317(MLP(3 hidden layers) with sigmoid) and 0.9169(KNN with 5 neighbours).The MLP and KNN models performed signiﬁcantly better than the other three model.KNNprovedtobethebestmodelwithaccuracyclose to the state of the art accuracy of 95 %.

Look at the **code** and **report** for more details
