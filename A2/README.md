#HCDE410
Files for HCDE410 - Assignment A2

# A2 — Exploring sources of bias in data
**Data** This project uses data from the Wikipedia Talk Corpus study.

**Source:** [https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973?file=7394539]

**License / terms of use:** All metadata published by Figshare.com are available free of restriction under the Creative Commons CC0 1.0 Universal Public Domain Dedication.

## Questions I asked
Q1. What is the gender distribution of these workers?
Q2. What is the distribution of the workers by first language?
Q3. What is the distribution of these workers by age group?
Q4. what is the distribution of these workers by education level?
Q5. Analyze all_annotators in Sheets or Jupyter: Do any of the fields in this dataset have missing data? If so, which fields, and what % of the rows contain missing values?
Q6. Build a version of the all_annotators dataset without removing duplicates, then re-run the summary statistics from questions 1-4. How have these summary statistics changed?
Q7. In general, how do the demographics of these workers compare to those of English-speaking internet users overall? Why would it matter if the worker demographics don't match the demographics of the intended end users of the Perspective API?
Q8. Given what you now know about the Wikipedia Talk Corpus, what issues might arise if it was used to train a machine learning-driven "hostile speech detector" that could be used on any website or social media platform?
Q9. What % of workers who labelled the toxicity dataset do we have demographic data for?
Q10. What % of the comments in the toxicity dataset were labelled by male vs. female-identified workers?
Q11. What % of the comments in the toxicity dataset were labelled by people for whom English is NOT their first language?
Q12. Based on your findings from questions 9-11, how might this dataset present a biased view of "toxicity"? How would you expect such biases to impact how the Perspective API performs?
## How to re-run:
Open `A2.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).

