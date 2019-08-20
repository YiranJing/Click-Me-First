# The Summery of Practical Skills I Leart at Douugh
Part-time Data Scientist Intern (two days per week)
Aug 13 2019 - Oct 31 2019 (12 weeks)

## Week 1: 
- Know my role in data team, and begin work on the multi-classification project.
- Learnt basic NLP tech, including bag of word and word Embeddings. 
- Begin the data cleaning for text classification. 

## Week 2:
- Realize the 'Imbalanced' classification can be NOT a problem in the practical, as long as we can find key featuers for the low frequency class.
- After realized that the 'perfect cleaned' data in text/NLP case is hopeless, try to find a 'smarter' and 'more efficient' way to clean and select (50k+) key features: good enough cleaned dataset + (pre-trained) embedding dataset + Naive Bayes baseline performance. 
- Understanding the limitation of trandictional regression model: Disgard logistic baseline, since based on the number of events per variable (EPV) rule, trandictional regression cannot handle lots of predictors, but we do have to use thoushands of featuers in text classification. 
- Split train and test dataset based on time-series data in the cross-sectional dataset, because in the daily operation, we always predict most recent data based on the old data. And the time horizon is important, the two years ago observations might not helpfel, because people could already change their comsumer behavor. 
- Add a numerical column to help text classification further.