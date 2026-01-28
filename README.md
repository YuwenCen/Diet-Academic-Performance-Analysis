# Diet-Academic-Performance-Analysis
In this research project, relationship between dietary habits and academic performance among college students are explored, employing a multifaceted methodological approach that included exploratory data analysis, multiple linear regression models, t-tests, and machine learning prediction models.

### Research Questions
- Are dietary habits associated with GPA?
- Can we predict GPA using only nutrition intake variables?

### Data
- Student Health Behavior and Academic Success survey dataset from 2018–2020 (n = 614)
- Features (weekly frequency): Fruit, Vegetables, Milk, Soda, Energy Drinks, Fast Food
- Target: Current GPA

### Methods
- EDA: distributions, boxplots, correlation heatmap  
- Inference: two-sample t-tests (high vs. low consumption groups)  
- Modeling: OLS multiple linear regression; ML classification (Linear SVM, Random Forest)

### Key Findings
- **Positive association with GPA:** Fruit, Milk (significant in OLS)
- **Negative association with GPA:** Fast Food, Energy Drinks (significant in OLS)
- **Weak/unclear after controls:** Vegetables, Soda
- **Prediction:** Diet-only models performed poorly (limited accuracy), suggesting GPA depends on additional factors beyond nutrition.

### Limitations
Self-reported survey data, single-university sample, class imbalance in GPA bins, and omitted variables (sleep/study habits/stress).

### Contributors
Evan Kauh, Julie Li, Angela Hu, **Yuwen Cen**, Adrian Mendoza
