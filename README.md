# Survival Analysis

The main goal of this respository is to present survival analysis models based on parametric and non-parametric estimators. The data for the studies are on the folder data. The examples that we have are:

- <b>Churn Analysis:</b> the goal of the study is to explore through survival analysis techniques the variables and their influence on the customer churn rate in order to propose an action plan to improve customer retention at Telco.

The source dataset was obtained from Kaggle (https://www.kaggle.com/blastchar/telco-customer-churn)

- <b>Duration of Hospitalization:</b> based on some variables we identify the parameters that have impact on the time a patient stays in a hospital.

- <b>Comparing drugs:</b> based on trials with 2 different drugs analyze the treatment group differ significantly in terms of survival to relapse.

- <b>Pharmako Smoking:</b> identify the variables that impact on the survival of patients who take a drug to stop smoking.

- <b>Lymphoma and Lung cancer:</b> builds models to predict the survival of patients with this type of cancer.

# Models

## 1. Kaplan Meier

The Kaplan–Meier estimator, also known as the product limit estimator, is a non-parametric statistic used to estimate the survival function from lifetime data. In medical research, it is often used to measure the fraction of patients living for a certain amount of time after treatment. In other fields, Kaplan–Meier estimators may be used to measure the length of time people remain unemployed after a job loss, the time-to-failure of machine parts, or how long fleshy fruits remain on plants before they are removed by frugivores.
 
Source: wikipedia

## 2. Cox Proportional Hazards

The Cox proportional-hazards model (Cox, 1972) is essentially a regression model commonly used statistical in medical research for investigating the association between the survival time of patients and one or more predictor variables.

the Cox model is a proportional-hazards model assumes that the hazard of the event in any group is a constant multiple of the hazard in any other.

Source:http://www.sthda.com/english/wiki/cox-proportional-hazards-model

## 3. RMST - Restricted Mean Survival Time

The restricted mean survival time (RMST), sometimes called the restricted mean event time, is an alternative measure
that is more often reliably estimable than the mean and median of the event time in certain situations. Also, it provides
a summary of the whole survival curve up to a time horizon, in contrast to the survival rate at a specified time (Royston
and Parmar 2013; Uno et al. 2014; Trinquart et al. 2016). The RMST has attracted practitioners for its straightforward
interpretation and its capability to deal with nonproportional hazards. When two survival curves cross, the difference
in the RMST between two groups still provides information about efficacy in a clinical trial, whereas the log-rank test
fails to detect the significance and the hazard ratio becomes meaningless.

Source: https://www.sas.com/content/dam/SAS/support/en/sas-global-forum-proceedings/2019/3013-2019.pdf

## 4. Survival Trees

Survival trees and forests are popular nonparametric alternatives to (semi) parametric models. They offer great flexibility
and can automatically detect certain types of interactions without the need to specify them beforehand. Moreover, a single tree can naturally group subjects according to their survival behavior based on their covariates. Prognostic groups can therefore be derived easily from survival trees. Moreover, survival trees are ideal candidates for combination by means of an ensemble method and can thus be transformed into very powerful predictive tools, such as survival forests.

Source: https://projecteuclid.org/download/pdfview_1/euclid.ssu/1315833185
