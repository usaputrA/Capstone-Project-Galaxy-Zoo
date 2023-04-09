# Capstone-Project-Galaxy-Zoo
In this project, we will analyze the Galaxy Zoo data provided by Mike Walmsley and associated data sets from NASA-Sloan Atlas (NSA). This data will be the only primary source for our analyses. You can find the data here: https://www.dropbox.com/sh/eytsiycznm4ubb1/AABJ1B-EQDMwd_32THIqlx40a?dl=0

## Can we identify whether the mean of two variables of an estimation for the galaxy's apparent brightness, `sersic_nmgy_r` and `mag_r`, are the same or not?
Our first question is if we can determine whether the mean of the two variables, `sersic_nmgy_r` and `mag_r`, used to estimate the galaxy's apparent brightness are equal or not. We will compare the means of the two variables in this manner using the proper hypothesis tests.

## Can we determine the variability for `redshift`?
The second question is if we can ascertain the `redshift` variability. This information is crucial for assessing the precision of distance estimates based on redshift and comprehending the ramifications of measurement mistakes. We will compute redshift-specific measures of variability using bootstrap and evaluate their importance in order to analyze this question.

## Depending on the galaxy's apparent brightness, does that correlate to how far away that galaxy is from us?
The final question we address is whether the galaxy's apparent brightness correlates with its distance from us. In the study of observational cosmology, this relationship has received a great deal of attention since it is crucial to our comprehension of the universe's large-scale structure. We will perform a simple linear regression method and correlation analysis between `sersic_nmgy_r` and `redshift` to answer the question.
