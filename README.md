# Aviation Accident Analysis
Overview
This project will investigate aviation accident data to understand factors that may impact aircraft safety. This will look at differences between small and large airplanes to see which makes/models are safer.

Objectives

Cleaning data
Understand differences between small and large aircraft (20+ occupants)
Understand fatal and serious injuries for different makes/models
Investigate aircraft destruction
Look at how weather conditions and engine type impact aircraft damage/injuries.
Data Cleaning
Removed any columns containing more than 50% missing data.
Removed any accidents that happened before 1983.
Removed any aircraft that were amateur built.
Only selected rows where aircraft were identified as airplanes.
Standardised aircraft make, model and other categories.
Created injury and aircraft destruction variables.

Analysis

Small vs Large Aircraft
We can see there are differences in injury rates for different models of small and large aircraft. Some models have a lower mean fraction of fatalities and serious injuries.

Aircraft Makes
Some makes have lower injury and destruction rates. This could be something to consider.

Other factors affecting safety
Weather conditions and engine type were looked at.

Visualisations
Bar chart showing injury rates for different aircraft makes.
Violin and strip plot showing distribution of injury rates.
Bar chart showing aircraft destruction rates.
Chart showing weather conditions and engine type.

Recommendations
When selecting aircraft to use it should be considered how many injuries occur to occupants and how much destruction occurs. It should also be considered how many accidents were recorded for each make/model.

Files
Cleaning.ipynb
Data Analysis.ipynb

Conclusion
This analysis gives some useful insight into what happens in aircraft accidents and shows what factors should be considered when looking at aircraft safety. Further analysis could be done using flight hours and other data to give more reliable comparisons.

