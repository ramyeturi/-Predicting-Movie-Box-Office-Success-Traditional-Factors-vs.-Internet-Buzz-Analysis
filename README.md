# Title: "Predicting Movie Box Office Success: Traditional Factors vs. Internet Buzz Analysis"

Abstract:

This project delves into the dynamics of predicting box office revenues for 62 wide-released movies from November 2008 to April 2009. It meticulously examines the interplay between conventional movie attributes and internet buzz variables in shaping financial outcomes. The research unfolds in several stages:

Data Exploration: We embark on a thorough exploration of the dataset, scrutinizing continuous variables like box office revenues, production budget, and star power rating. We evaluate skewness and apply log-transformations when required.

Initial Regression: We initiate our analysis with linear regression models, concentrating solely on traditional movie attributes. We gauge predictive efficacy using R-squared and adjusted R-squared metrics and establish variable significance through t-statistics.

Variable Selection: Significant variables identified in the initial regression inform the creation of a refined model, consolidating only the most influential factors.

Buzz Variable Analysis: A dedicated examination is conducted on internet buzz variables, including addict, cmngsoon, fandango, and cntwait3. Skewness is addressed through log-transformations.

Regression with Buzz Variables: A novel linear regression model emerges, incorporating both traditional attributes and internet buzz variables. We assess model performance through R-squared and adjusted R-squared values and examine variable significance.

Variable Selection with Buzz: The final model is curated, focusing exclusively on influential variables extracted from the buzz variable regression.

Model Comparison: We systematically compare and evaluate all models developed in the analysis, scrutinizing predictive power and variable significance.

Principal Component Analysis (PCA): PCA is applied to internet buzz variables, revealing their impact on predictive models. Eigenvalues and explained variance are calculated, and the optimal number of principal components is identified.

Regression with PCA: We build linear regression models using the selected principal components and assess their performance.

Model Comparison with PCA: Diverse combinations of principal components, guided by Kaiser's Rule and explained variance thresholds, are evaluated to determine the most effective model.

Combined PCA: PCA extends to include both internet buzz variables and other continuous variables. Regression models and comparisons follow suit.

Managerial Insights: Our analysis culminates in valuable managerial insights, shedding light on the relative importance of traditional attributes, internet buzz variables, and PCA in predicting movie box office revenues.

This project aims to provide nuanced insights into the complex world of box office predictions, helping industry professionals and data analysts navigate the intricate balance between traditional factors and internet buzz.
