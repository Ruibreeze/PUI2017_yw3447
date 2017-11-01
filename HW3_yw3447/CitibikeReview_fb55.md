 ## HYPOTHESIS FORMULATION

You should state why your idea is interesting in your report, and what motivates it. 

The Null/Alt hypotheses refer to a RATIO, but it is not specified what the ratio is to be taken on. A ratio means numerator/denominator (division) 
I think here you intended to refer to the RATE. But rate is also the wrong word, 
because it implie number of occurrences in a given interval (of time, space, etc.). 

So what your question should be about is the Total Number of Trips longer than 15 minutes, to be compared with the  Total Number of Trips shorter than 15 minutes.


However, see below in the test selection.

The Null/Alternatively is formulated appropriately in accordance with the original question as far as the formulae go. 
The significance level alpha should be stated more clearly.


## DATA

The data supports the analysis but it is not properly pre-processed as it is still split by day of the week, while your question has no dependence on the day of the week (as it is stated anyways)
Further, in your last plot the data is normalized, to enable a specific comparison across days of the week, but that does no longer allow yhour original question to be answered: are there more or fewer short rides.

## STATISTICAL TEST

It is actually quite hard to answer your question as it is stated. A better Null would phrase the question as a tet of proportions:
H0: is the fraction of >15min trips over total number of trips >= fraction of <15min trips over total number of trips?

then your test wuld be a chi-square test for proportions, asme as we used in the employment of ex-convicts exercise, 
which is a non-parametric test for proportions




NOTE: For whichever test you chose, you want the one-tailed version

