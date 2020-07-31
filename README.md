# WOM-C-feature-weightage-datapoint-membership-one-class-data

latestdata.csv.zip :    
The original source of the data is latestdata.csv file. It was too big to be uploaded so I uploaded it's compressed form.
                                     

df4_final_symptoms_per_person.csv  :
The raw data extracted from the "symptoms" column of latestdata.csv file is preprocessed into algorithm usable form (each symptom segregated into a seperate column) and is stored  as a pandas DataFrame in this file.

df3_correlation_final_symptoms.csv :
Inter-feature correlation values table. TO BE KEPT IN MIND:- the serial numbers 1,2,3... correspod to the columns starting from left to right . The serial no. 1 is the same as leftmost column "fatigue", serial no. 2 is same as second leftmost column and so on... when same symptom occurs in columna and row ( the value in table shows 1... which will later be converted to 0 as as correlation to itself yields 0).  
                                     
                                     
ml_covid_19_final.ipynb : 
The code file. The beginning portion enclosed under the headings of "final code" is the code related to this paper. Below it is extra code of experiments/trials /intermedate steps etc.
