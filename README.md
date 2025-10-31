# A/B Test of Advertising Impact on Conversion

## The company wanted to reduce advertising costs and test whether turning off ads for some users would affect their purchase conversion.

An A/B test was conducted comparing two groups:
- Ad group: users who saw the advertisement
- PSA group: users who saw only the public service announcement

## Goal - to determine whether disabling ads changes the conversion rate.

## Data
user id: unique identifier of users
test group: 'ad' or 'psa'
converted: whether the user purchased the product (True/False)
total ads: number of ads seen by the user
most ads day: day of week with most ads seen
most ads hour: hour of day with most ads seen

## Metrics
Primary metric: conversion rate (converted)
Secondary metrics: total ads - to confirm users actually saw different amounts of ads
                   most ads day - to explore if day of week affects conversion

## Methodology
Random sampling: 3112 users per group to ensure balanced A/B test
Statistical tests for primary metric: Z-test, Chi-square, Bootstrap
Tests for secondary metrics: Mann-Whitney U test for total ads, descriptive analysis for most ads day

## Results
Conversion rate: no statistically significant difference between groups (p > 0.05)
Total ads: users in the Ad group saw significantly more ads than the PSA group
Most ads day: conversion did not vary meaningfully by day of week

## Conclusion
## The A/B test shows that disabling advertising did not significantly affect purchase conversion.
# Users in the Ad group indeed saw more ads, but the day of maximum ad exposure did not significantly influence conversion.

Recommendation: the company can consider reducing ad spend without risk of losing conversions.
