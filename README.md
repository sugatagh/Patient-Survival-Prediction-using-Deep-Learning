# Patient Survival Prediction using Deep Learning
 
Deriving a quick understanding of the overall health of a patient is of paramount importance in emergency healthcare situations. Often this understanding is hindered for many different reasons.

A patient in distress or in an unresponsive state may not be able to inform the healthcare professionals about chronic conditions such as heart disease, diabetes or other injuries. In particular, the intensive care units in the hospitals often lack verified medical history of the incoming patients. Also, when a patient shifts from one medical support provider to another, the clinical records of the patient may take days to transfer, which delays the treatment process. The pandemic situations present the health workers with these issues at a much larger scale as the hospitals may get overloaded with patients in severe conditions.

- Information about the medical records of a patient plays a crucial role in determining his or her survival odds to a substantial extent.

- In this project, we aim to predict survival of a patient, which is a [**binary variable**](https://en.wikipedia.org/wiki/Binary_data), based on the relevant medical records.

- A detailed [**exploratory data analysis**](https://en.wikipedia.org/wiki/Exploratory_data_analysis) on the dataset is carried out.

- We use the insights obtained from EDA in the [**data preprocessing**](https://en.wikipedia.org/wiki/Data_Preprocessing) stages, which consists of [**missing data**](https://en.wikipedia.org/wiki/Missing_data) [**imputation**](https://en.wikipedia.org/wiki/Imputation_(statistics)), [**categorical data encoding**](https://en.wikipedia.org/wiki/Categorical_variable#Categorical_variables_and_regression), and [**feature scaling**](https://en.wikipedia.org/wiki/Feature_scaling).

- We build a [**neural network**](https://en.wikipedia.org/wiki/Neural_network) and [**tune**](https://en.wikipedia.org/wiki/Hyperparameter_optimization) it to predict survival of a patient.

- The final model obtains a test [**accuracy**](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification) of $0.923513$.
