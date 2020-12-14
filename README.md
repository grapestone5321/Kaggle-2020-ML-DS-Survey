# Kaggle-2020-ML-DS-Survey
Kaggle-2020-ML-DS-Survey

## State of Machine Learning and Data Science 2020
https://storage.googleapis.com/kaggle-media/surveys/Kaggle%20State%20of%20Machine%20Learning%20and%20Data%20Science%202020.pdf

### Overview
For the fourth year, Kaggle surveyed its community of data enthusiasts to share trends within a quickly growing field. 

### Based on responses from 20,036 Kaggle members, we’ve created this report focused on the 13% (2,675 respondents) who are currently employed as data scientists

We can see a clear picture of what is common in the community but also the diverse attributes of its members. 




## End Date (Final Submission Deadline): 
01/06/2021 11:59 PM UTC

-------



## submission
To make a submission, complete the submission form. 

Only one submission will be judged per participant, so if you make multiple submissions we will review the last (most recent) entry.

### Submissions will be evaluated on the following:

- Composition - Is there a clear narrative thread to the story that’s articulated and supported by data? 

The subject should be well defined, well researched, and well supported through the use of data and visualizations.

- Originality - Does the reader learn something new through this submission? 

Or is the reader challenged to think about something in a new way? 

A great entry will be informative, thought provoking, and fresh all at the same time.

- Documentation - Are your code, and notebook, and additional data sources well documented so a reader can understand what you did? 

Are your sources clearly cited? 

A high quality analysis should be concise and clear at each step so the rationale is easy to follow and the process is reproducible

-------

## U.S.-India

### U.S.-India Relations 1947 – 2020
https://www.cfr.org/timeline/us-india-relations

### India in the ‘Asian century’: Thinking like a hegemon?
https://doc-research.org/2019/07/india-in-the-asian-century-thinking-like-a-hegemon/

-------


## numpy.where
numpy.where(condition[, x, y])

Return elements chosen from x or y depending on condition.

### Note
When only condition is provided, this function is a shorthand for np.asarray(condition).nonzero(). 

Using nonzero directly should be preferred, as it behaves correctly for subclasses. 

The rest of this documentation covers only the case where all three arguments are provided.

### Parameters
conditionarray_like, bool

Where True, yield x, otherwise yield y.

x, yarray_like

Values from which to choose. x, y and condition need to be broadcastable to some shape.

### Returns
outndarray

An array with elements from x where condition is True, and elements from y elsewhere.


-------

## pandas.Series.value_counts
### Series.value_counts(normalize=False, sort=True, ascending=False, bins=None, dropna=True)

### [source]:
https://github.com/pandas-dev/pandas/blob/v1.1.5/pandas/core/base.py#L1164-L1253


Return a Series containing counts of unique values.

The resulting object will be in descending order so that the first element is the most frequently-occurring element. 

Excludes NA values by default.

## Parameters
### normalize: bool, default False
If True then the object returned will contain the relative frequencies of the unique values.

### sort: bool, default True

Sort by frequencies.

### ascending: bool, default False

Sort in ascending order.

### bins: int, optional

Rather than count values, group them into half-open bins, a convenience for pd.cut, only works with numeric data.

### dropna: bool, default True

Don’t include counts of NaN.

## Returns
Series



-------
