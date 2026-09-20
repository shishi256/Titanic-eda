## Initial Dataset Check
I first checked the size, structure and missing values in the
dataset. The dataset contains information about passengers,
including their age, gender, passenger class, fare and survival
status. Some columns contain missing values, so I will clean them
before starting the analysis.

## Age Distribution
The age distribution shows that most passengers were adults or
young adults. There were fewer passengers at the very low and
very high age ranges.

## Correlation Analysis
The heatmap helps compare the numerical variables with each other.
Survival has some relationship with passenger class and fare,
while some variables such as SibSp and Parch are also related to
FamilySize because they are used to calculate it.

## Key Observations
### 1. Passenger class mattered
Passengers in 1st class generally had a higher survival rate than
those in 2nd and 3rd class. This suggests that passenger class was
an important factor in the survival pattern.
### 2. Gender showed a clear difference
Female passengers had a much higher survival rate than male
passengers across the different classes. Gender therefore shows
one of the clearest differences in the dataset.
### 3. Age was not enough by itself
Most passengers were young adults and adults, but age alone does
not explain the survival pattern. Looking at age together with
class and gender gives a better understanding of the data.
### 4. Family size gives another useful clue
Passengers travelling with very small or very large families did
not show exactly the same survival pattern. The FamilySize feature
was useful for looking at this difference.

## Conclusion
This EDA helped me understand the main patterns in the Titanic
dataset. Passenger class and gender showed noticeable differences
in survival, while age and family size added some extra context.
Cleaning the missing values and creating new features made the
dataset easier to compare and visualize.