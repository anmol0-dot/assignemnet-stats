🎓 Teachers Rating Dataset Analysis
🧭 Objective
The objective of this analysis is to explore a dataset of university instructors’ teaching evaluations using Python libraries such as *NumPy, **pandas, and *SciPy.
The goal is to perform statistical tests, evaluate relationships among variables, and interpret whether characteristics such as *gender, **tenure, and *beauty scores influence teaching evaluation outcomes.

📊 Dataset Description
The dataset contains information about university instructors and their teaching evaluation ratings.
It includes the following variables:

Professor Name: Instructor’s name (may appear multiple times for different courses)
Gender: Male or Female
Tenure: Indicates whether the professor is tenured (Yes/No)
Beauty: Attractiveness score of the instructor
Evaluation: Teaching evaluation score (scale of 1–5)
Students: Number of students in the class (contains one large outlier)
Age: Instructor’s age
Division: Type of course — “Lower” or “Upper” division
⚙ Tools Used
Python 3.x
NumPy
pandas
SciPy
Jupyter Notebook / Google Colab
🧪 Statistical Tests & Results
1️⃣ Gender and Evaluation (Independent T-Test)
T-statistic: -1.4065
P-value: 0.1622

This negative value indicates that the average Evaluation score for male professors is slightly lower than that for female professors.
However, the difference is small and not practically meaningful.

Since the p-value is *greater than 0.05, the result is *not statistically significant.
We therefore *fail to reject the null hypothesis, indicating that there is *no significant difference in the mean evaluation scores between male and female professors.

2️⃣ Tenure and Evaluation (Independent T-Test)
T-statistic: -0.1541
P-value: 0.8778

This negative value indicates that the average Evaluation score for tenured professors is slightly lower than that of non-tenured professors.
However, the difference in means is very small and not practically meaningful.

Since the p-value is *greater than 0.05, the result is *not statistically significant.
Therefore, we *fail to reject the null hypothesis, indicating that *tenure status does not have a significant effect on teaching evaluation scores.

3️⃣ Correlation Between Beauty and Evaluation
Correlation Coefficient: -0.0163
P-value: 0.8602

This value indicates a very weak negative linear relationship between Beauty and Evaluation.
In practical terms, as a professor’s beauty score increases, their evaluation score tends to slightly decrease, but the effect is negligible.

Since the p-value is *greater than 0.05, this correlation is *not statistically significant.
We therefore fail to reject the null hypothesis, suggesting that any relationship observed in the sample is likely due to random variation.

🧩 Conclusion
All statistical tests indicate that there are no significant relationships among the variables studied.
Gender and tenure do not meaningfully affect evaluation scores, and beauty has no significant correlation with teaching evaluations.

These findings suggest that, within this dataset, appearance, gender, and tenure do not substantially influence how professors are evaluated by students.
Any minor differences in averages are likely due to chance rather than genuine underlying effects.

📚 Summary
Gender → ❌ No significant effect on evaluations
Tenure → ❌ No significant effect on evaluations
Beauty → ❌ No significant correlation with evaluations
Overall, teaching evaluations appear independent of personal characteristics such as gender, tenure status, or beauty score.

--


