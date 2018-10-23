---
title: 'Empowering TB patients and providers: poster video at TBScience2018'
author: Ruoran Li
date: '2018-10-23'
slug: poster-video-at-tbscience2018
categories:
  - My Research
tags:
  - TB
  - policy
  - data science
  - implementation
  - routine data
  - prediction
  - research gap
  - contact investigation
  - prevention
---

We are presenting at [TBScience2018 conference](https://thehague.worldlunghealth.org/programme/preconference-side-events/tb-science-2018/), part of the [49th Union World Conference on Lung Health](https://thehague.worldlunghealth.org/).  

Here's our poster, poster #3384: ![TBScience2018 poster](/post/2018-10-23-empowering-tb-patients-and-providers-poster-video-at-tbscience2018_files/Prediction Poster v7.jpg)

__I've recorded a [screencast](https://www.youtube.com/watch?v=Fcla8eXRgh0) explaning the poster (7 minutes). __

## Transcripts:

Hello everyone! This is Ruoran Li. Here’s a five minutes overview of the poster we’re presenting at the TBScience 2018 conference. 

This research is a collaboration between Harvard TH Chan school of Public Health, Harvard Medical School, and Socios En Salud in Peru. 

Let’s get done to the details of this study. 

Worldwide, each year, around 40% of an estimated 10-million new TB cases are not diagnosed or reported to the healthcare system. Investigating contacts of TB patients is one important measure for the early diagnosis and treatment of people at high risk of having TB.

However, although contact investigation (CI) and preventive treatment (PT) are recommended by the WHO and many national guidelines, they are often not implemented in practice. 
Previous research has identified some barriers for adherence to CI and PT guidelines. For example, index patients and their contacts are less likely to adhere to CI and PT requirements, when they lack knowledge about the risk of disease spreading within a household. 
On the other hand, at the programmatic level, resources are often not allocated specifically to improve the outcome of contacts most at risk of TB disease. 

Therefore, knowing the individual disease risk of TB contacts would likely address these barriers and improve the uptake of CI and PT. 

In this poster, we propose to develop two prediction tools that are usable at the point of care of TB CI and PT uptake.

The first tool, shown on the left, can be used at the time of an index patient diagnosis. Using information collected from a index patient themselves, we can predict the risk of a particular contact of this patient having concurrent TB. This personalized risk information conveys to TB patients and care providers what potential risks are for each close contacts, this would allow more high risk contacts to be screened and treated for concurrent active disease. 

The second tool, shown on the right, can be used at the time after a TB contact was approached and assessed for active disease. For contacts who did not have active disease during contact investigation, we can determine their risk of developing incident TB disease within the next year.  This personalized risk information can help the healthcare providers to communicate future TB risk to contacts and improve their adherence to prescribed preventive treatment regimen. 

So now with the structure of the prediction tools explained, let’s go to the details of the methods and results. 

Between 2009 and 2012, we enrolled and followed up 14,044 household contacts of adult pulmonary TB patients in Lima, Peru. 
We assessed whether these contacts have TB disease at the time they’re enrolled, which is just after index patient diagnosis, and then at 2, 6 and 12 month after enrollment. For those who did not have disease and without positive TST results previously, we gave them TST at enrollment, and then at 6 and 12 month.
At baseline, you can see some patient and contact characteristics in the pie charts here. Of note is that this is a low HIV prevalence setting, with medium TB burden, and over a third of the contacts are overweight or obese.  

The map shows that we divided the population into a training and a validation cohort. In the training cohort, we used penalized logistic regression methods via cross validation and developed the two prediction models, one for concurrent TB, and the other for incident TB. We then tested how well the model performs in the validation cohort.

So here are the two nomograms we developed based on the final prediction models. To read this, for each contact, we can give him a score if he has a particular predictor level (this is the scale at the top). Adding up the scores for all predictors, we get a total score, that can be translated into a predicted risk of outcome, reading from the scale at the bottom.

On the left, we can see that many factors predict concurrent disease – those related to the index patients are in blue, the households in grey and contacts in red. And we can see the most important predictor is whether the contact coughed for at least a week prior to index patient diagnosis. It is worth noting that all these predictors can be obtained through asking index patients, so the results of this can inform subsequent contact investigation. 
On the right, we are at the point where we have done the initial investigation and have put contacts who have active TB on treatment. However, for contacts without active disease, some of them may be latently infected with TB, and are still at risk of developing disease. We want to predict their risk for incident TB.  We have more information to work with, such as the exact BMI of contacts, their comorbidities, and their TST results. You can read the full details of our prediction tools in the poster. 

Overall, our two prediction tools perform well in the validation cohort, with high areas under the ROC curves and good calibration. On the left, most contacts have a very low risk of concurrent TB disease of under 2%, but we can identify a small subset of contacts who have an over 10% risk of disease. Targeting more resources to improve the uptake of investigation for these contacts may prove fruitful. 
On the right, the risk categories for incident TB disease are less clear-cut, and we advise against setting a threshold for preventive treatment.  Providing information on the exact predicted risk for each individual contact may improve their understanding of the risk and benefit of taking preventive treatment, and therefore may improve their adherence to IPT. 

At last, if we were setting threshold-risk levels for decision making, with a decision curve analysis, we found that using our prediction tools would yield higher net benefit than current WHO guidelines for contact investigation and preventive treatment.

To summarize, we think all TB contacts should be investigated and adequately treated. for achieving this goal, we should empower TB patients, their contacts and healthcare providers for them to make informed decisions - we think our prediction models could deliver this information to them.   
You can find our key references and acknowledgement, together with my contact information at the bottom right. Thank you very much for your time, and please don’t hesitate to let us know if you have questions or suggestions.

