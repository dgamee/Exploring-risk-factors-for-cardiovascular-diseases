#  Exploring risks factors for cardiovascular diseases

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

 This dataset contains detailed information on the risk factors for cardiovascular disease. It includes information on age, gender, height, weight, blood pressure values, cholesterol levels, glucose levels, smoking habits and alcohol consumption of over 70 thousand individuals. 
A number of characteristics about the patient are included in each row

>● Age: Age of participant (integer)
>
>● Gender: Gender of participant (male/female)..
>
>● Height: Height measured in centimeters (integer)
>
>● Weight: Weight measured in kilograms (integer)
>
>● Ap_hi: Systolic blood pressure reading taken from patient (integer)
>
>● Ap_lo : Diastolic blood pressure reading taken from patient (integer)
>
>● Cholesterol : Total cholesterol level read as mg/dl on a scale 0 - 5+ units( integer). Each unit denoting increase/decrease by 20 mg/dL respectively. 
>
>● Gluc : Glucose level read as mmol/l on a scale 0 - 16+ units( integer). Each unit denoting increase Decreaseby 1 mmol/L respectively.
>
>● Smoke  : Whether person smokes or not(binary; 0= No , 1=Yes).
>
>● Alco ​­ : Whether person drinks alcohol or not(binary; 0 =No ,1 =Yes ).
>
>● Active : whether person physically active or not( Binary ;0 =No,1 = Yes ).
>
>● Cardio ­­ : whether person suffers from cardiovascular diseases or not(Binary ;0 – no , 1 ­‑yes ).
>

Data Source: If you use this dataset in your research, please credit the original authors. [Source](https://data.world/kudem/heart-disease-dataset).


 Identify any trends between the different values for each attribute and the development for cardiovascular disease among individuals represented by this dataset .
Age, gender, weight, lifestyle practices like smoking & drinking alcohol are all key influences when analyzing this problem set.

## Columns
<table>
<thead>
<tr>
<th>Column name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>age</strong></td>
<td>Age of the individual. (Integer)</td>
</tr>
<tr>
<td><strong>gender</strong></td>
<td>Gender of the individual. (String)</td>
</tr>
<tr>
<td><strong>height</strong></td>
<td>Height of the individual in centimeters. (Integer)</td>
</tr>
<tr>
<td><strong>weight</strong></td>
<td>Weight of the individual in kilograms. (Integer)</td>
</tr>
<tr>
<td><strong>ap_hi</strong></td>
<td>Systolic blood pressure reading. (Integer)</td>
</tr>
<tr>
<td><strong>ap_lo</strong></td>
<td>Diastolic blood pressure reading. (Integer)</td>
</tr>
<tr>
<td><strong>cholesterol</strong></td>
<td>Cholesterol level of the individual. (Integer)</td>
</tr>
<tr>
<td><strong>gluc</strong></td>
<td>Glucose level of the individual. (Integer)</td>
</tr>
<tr>
<td><strong>smoke</strong></td>
<td>Smoking status of the individual. (Boolean)</td>
</tr>
<tr>
<td><strong>alco</strong></td>
<td>Alcohol consumption status of the individual. (Boolean)</td>
</tr>
<tr>
<td><strong>active</strong></td>
<td>Physical activity level of the individual. (Boolean)</td>
</tr>
<tr>
<td><strong>cardio</strong></td>
<td>Presence or absence of cardiovascular disease. (Boolean)</td>
</tr>
</tbody>
</table>

<a id='conclusions'></a>
## Conclusion
Based on the dataset, it is clear that cardiovascular diseases are a significant concern, with nearly half of the patients in the dataset having some form of the condition. It is interesting to note that people with a higher body mass index tend to be at higher risk for both high blood pressure and cardiovascular diseases. Additionally, patients who consume alcohol tend to have an increased BMI, which may contribute to their risk for cardiovascular diseases.

Another important finding from the data is that people over the age of 53 are more prone to cardiovascular diseases, with the risk increasing as age increases. It is also notable that while cholesterol levels are positively correlated with the risk of cardiovascular diseases, people with a cholesterol level of 3 are at a particularly high risk.

Overall, the data suggests that lifestyle factors such as physical activity, smoking, and alcohol consumption can have a significant impact on the risk of cardiovascular diseases. This information could be used by healthcare professionals to develop more targeted interventions and preventative measures for patients at risk for these conditions.

