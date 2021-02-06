# Cause of Mortality and Medical Transcript Analysis
## 1 Background
Every year, centers for disease control and prevention (CDC) provides detailed statistics of deaths and
their underlying causes in the United States. The CDC mortality data is used by various industries like
medical, health and insurance to provide better services. It provides the basis of numerous researches and
is widely cited in public papers.
Because of your outstanding knowledge, you are hired as a data scientist by a prestigeous insurance company. The VP of your department wants to launch a life insurance product but would like to do an analysis
on the cause of death in the US population first. 

## 2 Problems
2.1 Cause of Death in the U.S.
* What are the major causes of death in the US (show your evidence)?
* Are the major causes of death changing over time? Are there any significant increasing or decreasing trends? Can you explain the trends? How can you address the significance of the trends using statistical modeling method?
* For different ages what are the main causes of death? What are the main causes of death among
young people? What are the main cause of death among old people?
* Pick a few causes of death and estimate the probability of death due to those causes.

2.2 Medical Transcript
Determine if any patients have medical conditions that are associated with ICD codes of major causes of death.
* Design a similarity measure metric
* Calculate the similarity measure between ICD code descritption and medical transcirpts
* Assign ICD code to a medical transcripts only if the similarity score is above certain threshold.

## 3 Data
Database: CDC mortality data between 2005 and 2015 from https://www.kaggle.com/cdc/

## 4 Methodology
* Descriptive Analysis
* Time-series Analysis
* Probability Estimation - Decesion Tree and Logistic Regression
* NLP

## 5 Comments of Python Notebooks
**1 Data Overview** file includes the codes for descriptive analysis;

In the **2.1 Cause of Death in the US** file:\
**2.1.1 Major Causes.ipynb** shows the solving process of the question - What are the major causes of death in the US (show your evidence)?;\
**2.1.2 Trend Analysis of Causes of Mortality.ipynb* shows the codes of trend analysis of the major causes;\
**2.1.3 & 2.1.4 Cause by age & Prob_Decision Tree.ipynb** shows the codes of the analysis of major causes of death for different ages, and probability estimation of death using decision tree;\
**2.1.4 Prob_Logistic model.ipynb** shows the codes of variables selections and probability estimation of death using logistic regression.\

**2.2 Medical Transcript.ipynb** is the codes of the Medical Transcript analysis
