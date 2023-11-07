# PythonMedicineAnalytics-
Progress:
1. Load the Dataset.xlsx file into the DataFrame. The correct Header is formed so that the names of the signs correspond to the signs themselves and index_col so that each patient corresponds to the medical history number.
 
Figure.1.1 The result of the completed work
2. Use the df.describe () method to display the work results in a separate DataFrame. This will provide information regarding the symptoms.
![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/e6bba5ec-61ef-4f01-9a75-f8602d2eec8b)
  ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/c5693f71-9fbd-44ea-acb8-f83b30d1f94a)

  Figure.1.2 The result of the completed work

3. Using the df.drop() method, remove all signs containing missing values marked in the table as NaN (Not a Number) or those patients containing too many missing values (for example, patient with ID 995). To do this, you can use the df.isna() method, which will determine the position of these missing values.
 ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/26e922f9-a413-431a-9391-8fc1ec6cda06)

Figure.1.3 The result of the completed work
 ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/a6d7f9b8-b5fb-4fcf-9ce2-13468a5d0717)

Figure 1.4 The result of the completed work
4. Next, you need to use the df.plot() method to plot all features. Using the axhline() method, determine in which patients the values of the signs exceed the average value and the median (for any 2 selected signs, for example AD syst and AD diast).
 ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/930e0fa8-01b1-488a-a6ed-54624beaa0b2)
![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/32ffe9c5-e8ca-442e-bedf-dfc61eb162b5)

Figure 1.5 The result of using df.plot

5. Using the ps.pivot_table() method, create separate tables for women and for men. Calculate the total number of patients with each type of disease and their percentage in the total number of patients.
 ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/c5e06cba-fa66-49ec-bbff-0a38a4f8d045)

Figure.1.6 The result of using ps.pivot_table


. Visualize the data using the PCA() method on two side by side
located figures: left - data marked according to the value of the diagnosis,
right - the data is labeled according to the KMeans method.
 ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/3860d648-4d4d-4d4d-91d5-a440e39a991b)

Figure 3.5 data clustering using the PCA method Figure 
![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/2ef42ef0-a54a-4b97-8dff-449247bbf309)

3.5 marked data marked according to the value of the diagnosis
 ![image](https://github.com/zot-imortal/PythonMedicineAnalytics-/assets/78374936/756a52aa-ec93-4287-ab8c-84e0b0e8d5bb)

Figure 3.6 labeled data are labeled according to the value of the Kmeans method

 

