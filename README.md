# UT-Data-Science-Assignment
This repository is created for the "Data Science with KNIME" course at the University of Tehran.

Students should fork this repository and upload reqired assignment files due to the tasks introduced after each session.

The Final Score for each assignment is calculated as described here: You have 100 points at first. For missing each task's main activity you lose 10 points and having minor mistakes reduces 5 points of your starting points.This will be your score as "Completeness" of assignment. After calculating the completeness of assignment, you lose 2.5% of your score for each extra commit you had (each time you amend your assignment after getting instructor's feedback so the instrucor checks your assignment again = 1 extra commit) and 0.5% for each hour you delayed doing the assignment. A "Bonus Score" will be added to your assignment score if there is something creative or interesting in your assignment (The assignment score may not exceed 100).

The Final Score will be the average of all the assignments scores.

Good luck.

-------------------------------------

Session 2 Assignment: To complete this assignment you have to upload 2 files to your Github repository (forked) and share the link to your repo to complete tasks 1 to 4. Also you have to share the link to your KNIME forum profile whenever task 5 is completed.

Task 1: Read the "adult.csv" file using "File Reader" node. The output data MUST contain only first 30,000 rows and all columns MUST be labeled.
  
Task 2: Read "cars-85.xlsx" file using "Excel Reader (XLS)" node. In the output data, the first 2 columns MUST be skipped.

Task 3: Read "Iris.sqlite" database file using appropriate nodes. The output data MUST caontain only the following columns:
"sepal_length", "sepal_width", "petal_length", "petal_width", "class_Arr_1_"

Task 4: Add "Node Monitor" view to the right panel. Take a screenshot while this view is added in KNIME Analytics Platform.

Task 5: Sign up for a KNIME Forum account and achieve "Autobiographer" and "First Like" badges.

-------------------------------------

Session 3 Assignment: To complete this assignment you have to upload 1 file (.knwf) to your repo.

Task 1: Remove row limit in "File Reader" node and column limit in "Excel Reader". (These limitations were applied in the previous assignment)

Use Iris.sqlite to do the rest of tasks in a continuous workflow:

Task 2: Use "Color Manager" node to assign colors to Classes (setosa, versicolor, virginica) in Iris dataset.

Task 3: Use a "Scatter Plot" node and select "sepal_width" as x axis and "petal_width" as y axis and then select the one single point which is not close to other points in "setosa" class. Save changes as default configuration.

Task 4: Filter and exclude the row which was selected in the previous task.

Task 5: Use the "GroupBy" node to calculate the mean of "sepal_length", "sepal_width", "petal_length" and "petal_width" for each class in Iris dataset.

-------------------------------------

Session 4 Assignment: To complete this assignment you have to upload 1 file (.knwf) to your repo. Be aware that this is your final assignment and it's a bit challenging.

Task 1: Read adult.csv file and filter the dataset to include the following columns: "age", "education", "sex", "income".

Task 2: Create 2 partitions at the ratio of 3:1.

Task 3: Build a decision tree model to predict the "income" based on the other attributes.

Task 4: Evaluate the model by using the "Scorer" node.

Task 5: Use the "Table Creator" node to input your own personal values of the attributes and predict your income based on the model (Use another decision tree predictor node).

Special Task (25% of assignment score): Following task 1, in a separate flow, calculate the probability of your income being above 50K based on your own personal values of the attributes and the same records in the current dataset (The output of task 1).
