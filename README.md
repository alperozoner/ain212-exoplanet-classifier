# ain214-final-project
### This is an exoplanet classifier for the final project of the AIN212 data science course. Publicly accessible data from NASA's exoplanet archive was used in the training and testing of the model.

### Conclusion

In this report, we have trained two classifier models, namely a kNN classifier and a logistic classifier on NASA's Kepler Objects of Interest (KOI) datasets. The logistic classifier outperformed the kNN classifier by around 5% in most metrics and has an overall accuracy of 0.83, and an AUC of 0.90, which is to show that it is indeed a very successful model. We can now say that our logistic classifier can very skillfully determine whether an observed Kepler object is an exoplanet or not with great certainty, given 20 variables about that certain object of course.

We are proud to say that we have practiced the very steps of data science from data collection, preprocessing and cleaning, exploration and analysis to predictive modelling, and finally to model evaluation and numerous visualizations to better explain the whole process. We hope that you have enjoyed reading this report as much as we enjoyed while creating it.

### Closing Remarks and Possible Improvements

We believe that we could have gone further by also clustering the data using agglomerative clustering technique we learnt in class, and comparing it with k-means, however we deemed that it would take a quite long time and space in the report. We also had wished to visualize the result of clustering of certain low-level variables such as "koi_teq", and "teq_prad", (the temperature and the radius of the given Kepler object) to better visualize and form a inuitive understanding about certain qualities that make an object qualify as an exoplanet. In this way, the reader could have a better intuitive scientific understanding about the nature of planets and their distinctive qualities from other heavenly objects such as moon, comets, and asteroids.

We should also note that certain variables used in this report are high-level data such as certain "flag" variables which are results of extensive scientific tests, rather than raw scientific data. This of course made our job easier, but we believe that it also made it harder for an average reader to understand what that data really means as most of their descriptions are something along the lines of: "The Kepler object shares the same epoch and epoch as another object and is judged to be the result of flux contamination or electronic interference in the aperture." This description is indeed very alien to an average reader. This could have been solved by including more low-level, raw scientific data by using another dataset. But honestly we haven't looked into that.

We hope that you agree with our remarks especially about the nature of scientific understanding we could have instilled the reader in this report but felt short in. We as the authors of this report, both love science and especially the observation of space itself, so we felt a little bit unfulfilled in this department.

Thank you for your time.
