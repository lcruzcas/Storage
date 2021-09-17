# Autograder-grading explanation (Homework # 2):
In general students will have three possible outcomes pushed back to their repositories for each test. 

* Test Passed (+= number of points)
* Test # Timed out (+= 0 points)
* Test # Failed  (+= 0 points)

Additional text that can appear in the .txt file such as: \no new line at the end or the file, or other. These messages are not relevant to the grade.

# For this homework there are a total of 100 points, divided in 8 tests, 4 for Problem 1 and 4 for Problem 2. 
For both problems, the grading script takes the code provided by the student in the repository, and compares the output to the one that appears in the solution. 
If the output is the expected it allocates the points. If the program does not run, because of a time out no points are given. Finally, if the output is different from the expected output is gives zero points. 
## Problem 1 will be tested four times, tests cases are: 

### Test case 1.1 (20 points)
```
data = [-4, -3.2, 0, 7.6, 1.0, 2.2, 30, 2.2, 1.9, -8.3, 6, 5]
hist = histogram(data, 10, -5, 10)
```
### Test case 1.2 (10 points)
```
data = [2,2,2,-3]
hist = histogram(data, 3, -2, 3)
```
### Test case 1.3 (10 points)
```
data = [-1,-1,-1,10,10]
hist = histogram(data, 5, 0, 10)
```
### Test case 1.4 (10 points)
```
data = [1,2,3,4,5,6]
hist = histogram(data, 6,1,7)
```
## Problem 2 will be tested four times, tests cases are: 

### Test case 2.1 (10 points)
```
name_to_day={'jack':14,'helen':2,'zach':20}
name_to_month={'jack':4,'helen':2,'zach':10}
name_to_year={'jack':2014,'helen':2002,'zach':1969}
name_to_all = birthdaycake(name_to_day, name_to_month, name_to_year)
```
### Test case 2.2 (10 points)
```
name_to_day={'jack':14,'helen':2,'zach':20, 'mark':15}
name_to_month={'jack':4,'helen':2,'zach':10, 'mark':12}
name_to_year={'jack':2014,'helen':2002,'zach':1969, 'mark':2004}
name_to_all = birthdaycake(name_to_day, name_to_month, name_to_year)
```
### Test case 2.3 (10 points)
```
name_to_day={'tom':2}
name_to_month={'tom':4}
name_to_year={'tom':1992}
name_to_all = birthdaycake(name_to_day, name_to_month, name_to_year)
```
### Test case 2.4 (20 points)
```
name_to_day={'sonali':22,'yunchoo':2,'kao':20, 'ben':15}
name_to_month={'sonali':12,'yunchoo':2,'kao':10, 'ben':5}
name_to_year={'sonali':2001,'yunchoo':2111,'kao':2001, 'ben':1540}
name_to_all = birthdaycake(name_to_day, name_to_month, name_to_year)
```


