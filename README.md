# Coursera Data Science Toolbox

## Course Notes

### What do data scientists do?

1. Define question
2. Define ideal data set
3. Determine what data you can access
4. Obtain the data
5. Clean the data
6. Exploratory data analysis
7. Statistical prediction/modeling
8. Interpret results
9. Challenge results
10. Synthesize/write up results
11. Create reproducible code
12. Distribute results to other people

### Getting Help

- Describe goals
- Be explicit
- Provide minimum info
- Follow up and post solutions
- User the forums rather than email

### CLI Basics

- pwd: print working directory to show path
- clear - clears the terminal screen
- ls: lists
- cd: change dir
- touch - create new file
- cp - copy
- cd - back to home
- cd .. - up one
- cp -r - recursively copy contents
- rm - remove
- mv - move
- date - print date
- echo - prints command

### Git Commands

- git add . - adds all new files
- git add -u - updates tracking for files that changed names or deleted
- git add -A - does both 
- git commit -m 'Message'
- git push - move it to github
- git checkout -b branchname
- git branch - see what branch your are on
- git checkout master - switch back to master branch type

### Types of DataSci Questions

In order of difficulty

1. Descriptive - Describe set of data, common, census data, not generalized w/o additional stats.
2. Exploratory - **Find relationships**, not confirm, define future projects, not final say, not for generalization/predictive, does not imply causation.
3. Inferential - **small set of data say something about bigger** population, common goal of stat. models, estimate quantity, uncertainty, depends on population, sampling scheme.
4. Predictive - use data on some obj to predict, X predicts Y does not mean X _causes_ Y, prediction very hard.
5. Casual - change one value how does that change the other var, randomized studies, average effects, 'gold standard' for data analysis
6. Mechanistic - rarely covered in DataSci, understand var changes that lead to other var changes, hard to infer, physical/engineering sci, measure errors.

### Definitions

Data: are values of qualitative or quantitative variables, belonging to a set of items.

- Set of items - population
- Qual - not ordered
- Quant - measured, scale
- Rarely structured

Most important thing is the question, data is second.

Big-data: may not contain (useable) data. No matter how big the data are.

Experimental Design: care about analysis plan.

1. Formulate question in advance - answer specific question in advance.

Statistical Inference - select small subset: population, probability, sample, descriptive. Want small variability with big differences.

Confounding - Correlation is not Causation

- Fix variable so it cannot be a confounder
- Stratify - use both equally 
- Randomize - assign randomly
- Prediction - training set, prediction function f(), separated distribution
- Prediction key quantities: positive/negative status( True Positive, False Positive, False Negative, True Negative )
- Data Dredging - change hypothesis until we find the answer we want

**Summary**

- Good experiments
		- Have replication
		- Measure variability
		- Generalize to the problem you care about
		- Are transparent
- Prediction is not inference
		- Both can be important
- Beware of data dredging




