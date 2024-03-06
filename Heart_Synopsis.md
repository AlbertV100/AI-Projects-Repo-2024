**[Problem statement:]{.underline}**

Cardiovascular diseases are the leading cause of death globally. It is
therefore necessary to identify the causes and develop a system to
predict heart attacks in an effective manner. The data below has the
information about the factors that might have an impact on
cardiovascular health.

**[Dataset description:]{.underline}**

  ----------------------------------- -----------------------------------
  **[Variable]{.underline}**          **[Description]{.underline}**

  Age                                 Age in years

  Sex                                 1 = male; 0 = female

  cp\|                                Chest pain type

  trestbps                            Resting blood pressure (in mm Hg on
                                      admission to the hospital)

  chol                                Serum cholesterol in mg/dl

  fbs                                 Fasting blood sugar \> 120 mg/dl (1
                                      = true; 0 = false)

  restecg                             Resting electrocardiographic
                                      results

  thalach                             Maximum heart rate achieved

  exang                               Exercise induced angina (1 = yes; 0
                                      = no)

  oldpeak                             ST depression induced by exercise
                                      relative to rest

  slope                               Slope of the peak exercise ST
                                      segment

  ca                                  Number of major vessels (0-3)
                                      colored by fluoroscopy

  thal                                3 = normal; 6 = fixed defect; 7 =
                                      reversible defect

  Target                              1 or 0
  ----------------------------------- -----------------------------------

**[Synopsis: Cardio Vascular Disease Predictive analysis]{.underline}**

The Machine Learning project analysed a cardiovascular disease (CVD)
dataset comprising 303 instances and 14 features, including age, sex,
chest pain type (cp), resting blood pressure (trestbps), cholesterol
level (chol), and others. The project aimed to predict the risk of heart
disease using logistic regression and random forest classifiers.

**Exploratory Data Analysis (EDA)** involved visualizing feature
distributions, correlation matrices, and understanding relationships
between variables. Insights revealed associations between age and heart
disease occurrence, with higher instances in older individuals.
Furthermore, the analysis examined correlations between various features
and the target variable, uncovering potential predictors of CVD risk.

Modelling efforts employed **logistic regression and random forest
classifiers, achieving an accuracy of approximately 85% and 81%
respectively.**

The logistic regression model identified significant predictors such as
sex, chest pain type, maximum heart rate achieved (thalach),
exercise-induced angina (exang), and others. Random forest classifiers
yielded similar accuracy, demonstrating the robustness of the approach.

Overall, the project provided valuable insights into cardiovascular
disease prediction using machine learning techniques, offering potential
applications in healthcare decision-making and risk assessment.

Top of Form
