# Cardiac-Arrest-Analysis-and-Prediction


<p>Health risks are based on many factors such as age, gender, number previous chest pain experiences, blood pressure, cholesterol etc. In this project we categorised by using each attribute into healthy and unhealthy categories. Techniques such as Data pre-processing, EDA (Exploratory Data Analysis) to analyse the data in order to extract the information from the features, applied various machine learning models on the provided data to predict if there are any chances of cardiac arrests.</p>

<ol>
<li>age: The person's age in years</li>
<li>sex: The person's sex (1 = male, 0 = female)</li>
<li>cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)</li>
<li>trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)</li>
<li>chol: The person's cholesterol measurement in mg/dl</li>
<li>fbs: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)</li>
<li>restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)</li>
<li>thalach: The person's maximum heart rate achieved</li>
<li>exang: Exercise induced angina (1 = yes; 0 = no)</li>
<li>oldpeak: ST depression induced by exercise relative to rest</li>
<li>slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)</li>
<li>ca: The number of major vessels (0-3)</li>
<li>thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)</li>
<li>target: Heart disease (0 = no, 1 = yes)</li>
</ol>

### Dataset
<p>
The dataset which has been used in this project is collected from the Kaggle. The data is collected from the 4 hospitals in the United states of America. The data was collected in the form of observations from the hospitals. As the data is collected by using the resources of the hospitals the data is said to be as first-party data. All the data in the dataset is in the discrete data format because the data can be counted and has a limited number of values. As the data is of first-party it is more reliable and it can be reckoned as the Internal data.
The data in the dataset is organised, data types are defined and the data is totally quantitative. This makes the dataset structured. As the data is organised and neat to perform the analysis, this dataset was not required to do the data transformation. All the data attributes followed the same measuring metrics throughout the field.
This dataset is reliable, original, comprehensive, current and cited. Every good solution is found by avoiding bad data. Data anonymization is also completed beforehand on this dataset by the publishers of data.
</p>

### Box Plot for null value identification:

<img src="https://github.com/msrcharan/Cardiac-Arrest-Analysis-and-Prediction/blob/master/Images/boxplot.png" width="300px" height="300px">

### Metadata:

<p style="text-align:center;"><img src="https://github.com/msrcharan/Cardiac-Arrest-Analysis-and-Prediction/blob/master/Meta/metadata1.png" width="300px" height="300px"></p>

<p style="text-align:center;"><img src="https://github.com/msrcharan/Cardiac-Arrest-Analysis-and-Prediction/blob/master/Meta/metadata2.jpg" width="300px" height="300px"></p>

### Conclusion

<p>We know which characteristics to examine on a frequent basis based on the model and feature analysis. The most evident indication, in my opinion, is chest discomfort. Only a typical angina is closely linked to heart disease among the three forms of chest pain. If you have any form of chest pain, you should see a doctor. Furthermore, everyone should keep an eye on their resting blood pressure. The optimal resting blood pressure is less than 120mmHg, but if your blood pressure is far lower than that, you are at high risk of heart disease. Furthermore, when blood pressure exceeds 150mmHg, the issue is not limited to the heart.
There are several technological gadgets that can measure heart rate, making it easy to keep track of your own. Keep track of your maximum heart rate to ensure that your heart is still in good working order.
No matter how healthy we are, we must do an annual examination because other features can not be taken care of by ourselves. Finally, don't forget the older we are, the higher the risks are
</p>
