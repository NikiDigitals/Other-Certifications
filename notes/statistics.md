- Topic: Statistics  
  Related courses:
  Business Intelligence & Data Analyst - CFI
  Financial modelling & valuation Analysis - CFI

  File created on: 09-10-2025  
  Last modified:  
  Type: notes  
  Topics/Tags
  Related projects:  
  Related journals:

## Overview

**Statistics** The process of collecting, summarising and interpreting data  
**Descriptive statistics** Quantitatively summarises past data in factual terms. Objective measures that describe sample data. Provides an output that can be used to summarise a set of observations.  
**inferential statistics** Applying statistical methods to examine a sample set to understand a larger population better. Deals with uncertainty and allows for making predictions or summarising uncertainty.

## Descriptive statistics

_Organising and summarising data_

**Measures of Central**

- Tendency to attempt to identify the central point of our data
  - Mean:(average) most meaningful with data distributed without a lot of outliers
  - Median:(middle) Useful to diminish the effect of outliers
  - mode: (most frequent) The outcome that occurs the most frequently

<img src="https://i.imgur.com/tQzHAol.png" alt="skews" width="50%">
<br>

**Measures of Dispersion**

- Tell how dispersed or spread out our data is, to give us insights into how meaningful the mean is.
- more dispersed data: Random results are further from the mean.
- Simplest way to measure:
  - Minimum (lowest value): understand the worst-case scenario
  - Maximum (highest value): understand the best-case scenario
  - Range (range between lowest and highest values) describes the full spectrum of possibilities.  
    <br>

**Measure in Quartiles**  
 Economists use this, for example, to study policy effects on different income levels.

- median is the middle of the dataset
- Quartiles take the median to divide the data into quarters.
- Variance - Measures how spread-out all data points are.

<img src="https://i.imgur.com/mWJWWcz.png" alt="Variance" width="50%">
<br>
Calculate the variance of the data set 3,6,15:

```
(3 + 6 + 15 ) /3 = 8            # calculate the mean

3 - 8 = - 5                     # calculate the deviations
6 - 8 = - 2
15 - 8 = 7

(-5)^2 = 25                     # Squared   deviations to make them positive
(-2)^2 = 4
(7)^2 = 49
Sum = 25 + 4 + 49 = 78

78/(3-1) = 78/2 = 39               # sample variance
```

**normal distribution** (Heights, IQ)

- Symmetrical
- Mwan, median and mode are the same
- The ends approach but never touch the x-axis
- Follows imperical rules

**Kurtosis**  
The measure focuses on the weight of distribution around the mean or tails.

<img src="https://i.imgur.com/6aRVzeQ.png" alt="skews" width="50%">
<br>

**Assymmetric & Other Distrubutions**
\*Common and often described in terms of **skewness**

- Skewness describes where the outliers tend to occur and where the data is clumped together.

<img src="https://i.imgur.com/s3u1Nyf.png" alt="Variance" width="50%">

- negative skewed distribution: outliers to the left of the mean pointing to the negative, and data is clumped to the right.
- Positive skewed distribution: outliers to the right of the mean and data clumped to the left.

### main approaches of inferential statistics

**Classical approach to inferential statistics** Assumes outcomes have a set chance of occurring. Usually, each event is equally likely to occur, and that is predictable.
**Frequentist** Assumes probability can be measured and described through observation of past events. (needs a big dataset)
**Bayesian** Attempts to incorporate external information into probabilities. Probabilities should be updated when new information becomes available.

- Different approaches might create different conclusions.
- It is essential to ensure the assumptions are suited to the approach being used.

## Reference list:

## Links to related topics
