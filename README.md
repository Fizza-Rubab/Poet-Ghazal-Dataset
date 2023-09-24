# Poet-Ghazal-Dataset
This repository serves as a public data set for shayari from notable Urdu Ghazal poets.

## Source
This dataset has been scraped from the most reliable platform for Urdu Poetry, [Rekhta](rekhta.org). Rekhta is an Indian literary website devoted to promoting and encouraging Urdu poetry and prose in the subcontinent.

## Classes and Count
A corpus of 17,609 couplets was collected from 15 different notable Urdu poets. These couplets (consisting of 2 misras concatenated together).

## Acquisition
The data acquisition process from Rekhta involved a blend of manual and automated techniques. We extracted the links to the ghazals of each poet, and visited those links using an automated program. Regular expressions and string processing to extract the couplets of the ghazals from the visited pages, resulting in a dataset of Urdu couplets from various poets. 

## Poet Selection
These 15 poets were selected for the following reasons:

1. Poets [1-8] wrote in the 19th-20th century, while poets [9-15] belonged to the 18th-19th century. This diversity exposes the model to a range of styles in word usage and dialect, facilitating pattern recognition and enhancing performance.
2. The chosen poets in the dataset possess a substantial number of ghazals, ensuring a sufficiently large dataset for training a deep learning model. Each poet has a minimum of 450 couplets, with Mir Taqi Mir having the highest count at 2986.
3. All selected poets hold significant popularity and esteem in Urdu literary circles. This ensures that the analysis and results of this research can be appreciated by readers beyond the realm of computer science.


