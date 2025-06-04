# Exploratory-Data-Analysis-EDA- using Python
working on extracting insights using visual and statistical exploration by using Python and Jupyter Notebook on the Titanic Dataset.
we have the following datasets which is used for extracting insights is train.csv – Typically used for training and EDA, test.csv – Usually used for model evaluation.
Loading the train.csv where the dataset contains information about passengers aboard the Titanic, including demographics, fare, class, and survival.
The Descriptive statistics shows that .info() revealed missing data in Age, Cabin, and Embarked, .describe() highlighted a wide age range (0.42 to 80 years), and a skewed Fare distribution, value_counts() showed that about 38% survived, while 62% did not.
Survival by Sex where the Women had a much higher survival rate than men — a key indicator.
Survival by Passenger Class where the 1st class passengers had the highest survival rate; 3rd class the lowest.
Age Distribution where most passengers were aged 20–40. There’s a slight survival advantage for younger passengers.
Fare Distribution where most fares were below 100 and few passengers paid significantly more (right-skewed).
Boxplot (Age vs. Survival) where Survivors tend to be slightly younger on average.
Scatterplot (Fare vs. Age) where Survivors are concentrated in the younger age and higher fare groups.
Heatmap (Correlation) where Fare and Pclass moderately correlate with Survived. Age shows a weaker negative correlation.
The summary for the Titanic dataset is found that Gender is a strong indicator of survival — women were prioritized during rescue.
Passenger Class matters — higher class had better survival rates.
Fare correlates with survival to a moderate degree.
Age shows a trend — younger passengers had a slightly better chance.
Cabin is too sparse for reliable analysis without imputation.
