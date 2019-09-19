# matplotlib-challenge

In this challenge, data from a drug-based, anti-cancer pharmaceutical company have been analysed. The company is screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. My objective is to analyze the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

To analyse the data, the following plots were generated using matplotlib:

* A scatter plot that shows how the tumor volume changes over time for each treatment.
* A scatter plot that shows how the number of metastatic (cancer spreading) sites changes over time for each treatment.
* A scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
* A bar graph that compares the total % tumor volume change for each drug across the full 45 days.

#Observations made from the study:

1. Of the 5 drugs tested, Capomulin was the best candidate with a significant drop in the tumor volume. Its effect was evident from the very first day with a gradual decrease in tumor volume. Administration of Infubinol, Ketapril, and Placebo, on the other hand, showed similar response for the first 10 days, after which, promoted significant cell proliferation leading to increase in the mean tumor volume. (Refer: Plot 1).

2. An anti-cancer agent should effectively control metastasis, i.e., spread of tumor to different body sites. While none of the drugs could completely stop metastatis, Capomulin outperformed all drugs in controlling the spread, followed by Infubinol. Placebo and Ketapril showed similar and very poor response by the end of 45th day.(Refer: Plot 2)

3.Survival rate of mice was highest (~85%) with Capomulin treatment, followed by Ketapril and Placebo with almost similar survival rate (~43%), Lowest rate of survival was seen for mice treatment with Infubinol.(Refer: Plot 3)

Thus, Capomulin is the best drug candidate that outperformed other drugs in all metrics. Tumor volume decreased by ~20% with the administration of Capomulin, while for the rest, tumor volume increased by more than 40% in the 45 days treatment regime.
