# Surface efficacy rates from the CORD-19 dataset

Definition (courtesy of [Medical News Today](https://www.medicalnewstoday.com/articles/what-is-vaccine-efficacy)):
> Vaccine efficacy is the percentage reduction in a disease in a group of people who received a vaccination in a clinical trial. It differs from vaccine effectiveness, which measures how well a vaccine works when given to people in the community outside of clinical trials.

Sometimes the rates are directly evident:
>In a ring vaccination study at the end of the West Africa outbreak, the overall estimated rVSV-vectored vaccine efficacy was 100% and vaccine effectiveness was 64.6%

But often they are tricky to discern in a sentence structure, or, even worse, reference a table that is elsewhere in the text (or may not be part of the dataset):
> As shown in Table 1, with an estimated crude efficacy of 91.64%, the Gam-COVID-Vac outperformed pooled estimates for ChAdOx1 nCoV-19 (i.e. 71.62%), and was found to be directly comparable to mRNA-1273 and mRNA-BNT162b2 vaccines (i.e. 93.03% and 95.08%, respectively).

The CORD-19 open research dataset first became available in March, 2020, through the efforts of the White House and a coalition of leading research groups 
to created a freely available dataset of over 1,000,000 scholarly articles to encourage data mining and other text-based approaches to help in the fight against 
covid-19. There are great examples available at the associated [Kaggle Challenge](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge).
In addition, for efficacy rates in particular, there is a promising approach 
[described here](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0970-1).
