Data Cleaning Practice in Python

This repo is just me rolling up my sleeves and playing with a dirty dataset I pulled from Kaggle.
Nothing too fancy, nothing over-polished — just straight data wrangling, cleaning, and engineering to make sense of things.

*****************************************8
What I Did
*********************************

Imported the dataset (local CSV, not cloud magic).

Looked at the mess → missing values, duplicates, weird text entries.

Cleaned the Stars column → split it into stars and ratings because mixing them felt wrong.

Converted time into minutes → hours are cool but minutes give me precision.

Engineered new columns →

From dates: release_year, month, day, day_name, is_weekend

Plus: price buckets, listen length categories, rating density, etc.

Dropped NaNs to keep things tidy.

Ran sanity checks with .info(), .describe(), .unique() just to see what’s hiding in there.

Why This Repo Exists

To sharpen my pandas and data cleaning chops.

To leave behind a trail of code I can build on later.

To keep this code as a reminder of my earlier days of writing python code and compare progress (and see the trail of thought).

To get myself ready for ML Zoomcamp — makesure I’m not lost and avoid silly errors when machine learning kicks in.

*****************************

Next Steps
*******************************************

Do some groupby explorations (like: which day of the week gets more ratings, what genres are weekend favorites).

Maybe build visuals in the next phase (matplotlib/Power BI).

Push this dataset a bit further into ML territory just to see how it behaves.

****************************

Vibe
****************************
Straightforward. A bit messy. But practical.
If you’re also learning, you’ll feel right at home here.
