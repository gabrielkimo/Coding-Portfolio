mtcarapp.R - 
  * This is a project in which I designed an app in R that would take the mtcars dataset from 
    R, and allow the user to create different types of plot from a chosen variable in the dataset, while also displaying 
    general summary statistics for the selected variable.
  * Functionality includes a bar to filter the plotted variable by it's corresponding MPG values for each 
    observation, and tooltips appear when hovering the mouse over anything the user can interact with; implemented using the
    plotly package in R.
  * I made sure to ensure compatability with the chosen variable and the desired plot type is verified by the app, protecting
    from most use-cases that would return an error or display a plot that is innaccurate/empty.

PSTAT100 FinalProject.rmd, PSTAT100 FinalProject.pdf, and titanic.csv -
  * The files PSTAT100 FinalProject.rmd and PSTAT100 FinalProject.pdf contain the code and generated report 
    respectively for a project where I worked in a group of three with our chosen data set, titanic.csv, in an effort to
    build predictive models.  
  * Over the course of the project I helped write the hypothesis portions of our research questions, performed the
    Shapiro-Wilk tests to check the assumptions necessary for different methods of hypothesis testing, collaborated with my
    team members using the results of the assumption checking to decide upon using the Wilcoxan Rank-Sum test and logistic
    regression (for hypothesis #1 and #2 respectively), and for hypothesis #2 I generated the ROC curve and found the AUC
    value to evaluate the logistic regression model's efficacy.
  * Helped one of the group members write the results section, providing clarity about certain test-statistics and suggesting
    which values would be important to include.

Final-Project-PSTAT-131-1.rmd, Final-Project-PSTAT-131-1.pdf, and heart-attack-risk-prediction-dataset.csv - 
  * The files Final-Project-PSTAT-131-1.rmd and Final-Project-PSTAT-131-1.pdf contain the code and generated report for a
    machine learning project where I worked with a partner used our chosen dataset, heart-attack-risk-prediction
    dataset.csv, with the goal of making predictions about a persons risk of suffering a heart attack.
  * We began by performing exploratory data analysis to identify any observations that were incomplete, and any variables
    that would need to be coerced to a different data type (i.e. a factor with two levels rather than a string), then
    randomly splitting our data into training and test sets for cross validation of predictions.
  * In this project I performed the Principal Component Analysis and dimension reduction, built the model using KNN
    Classification, and collaborated with my partner on the boosting model as well as the model evaluations.  Then with our
    model evaluations completed, we developed plans for improving the accuracy of our models predictions.
    
