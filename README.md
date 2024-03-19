                                                      INSURANCE CLAIM PROBLEM STATEMENT
Description
Case Study for presentation : An insurance company in US is reviewing its insurance claim/charges and tyring to do a cause and effect analysis for future business decisions. It has collected data for its customers’ age, gender, bmi, number of children/dependants, smoking habit, region they belong to, charges/bills claimed under the insurance.

 

(Ensure that you are interpreting the operations at all steps as you shall be presenting your findings as an assignment) – .

Perform the basic Exploratory Data Analysis on the sample data. (10) marks
Identify the categorical and continuous variables
Make Histograms and box plots for continuous variables, do a correlation analysis.
Make relevant Pivot tables and charts for :
               1) Male/Female ratio and which gender has more smokers

               2) Charges vs Age

               3) Charges vs BMI

               4) Charges for Smokers vs Non-smokers

5) Region-wise Smokers vs non-smokers analysis with one or more pivot table and charts

6) Region-wise charges for smokers vs non-smokers

7) Has charges got something to do with no. of dependants ?

8) Do a similar dependants-charges analysis, Region-wise

9) Do atleast one more pivot table and chart of your own choice, if needed

Give your understanding from the patterns observed in point (b)
Give your interpretation for observations made in point ( c )
Edit the data as following, to obtain dummy variables: (5 marks)
Sex : Replace all the “Males” with “1” and “Females” with “0”, creating numerical entries for gender this way will help you do analysis further. You can use Replace with “Match entire cell content option. Do a replace all to save time.
Smoker: Replace all the “Smokers” with “1” and “Non-smokers” with “0”.
Region: We always create one less category column for the dummy data w.r.t the categories available for that original variable. So for Region, we will create three dummy columns, assuming “Northeast” as zero and omit the column for it. Now create three columns for “northwest”, “Southeast”, “Southwest”. Whichever row has “northwest” region as an entry will take “1” as an entry otherwise “0” in “northwest” column. Similarily in “Southeast” column, which ever row had “southeast” as an entry will take “1” as the new entry and “0” for the rest columns. Do a similar operation on “Southwest” column.
Screenshot 2022-08-29 170718.png

              

3) Do a descriptive summary analysis for the edited data. Perform a Multiple Linear Regression analysis to identify which variables decide the insurance charges/billed insurance claim.   

Give your interpretation for the above anslysis, do another set of regression analysis by dropping insignificant variables, if needed.                                                                                      (5 marks)
