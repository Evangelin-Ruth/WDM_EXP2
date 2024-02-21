### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
![image](https://github.com/Evangelin-Ruth/WDM_EXP2/assets/94219798/35b29719-c3bf-4769-b6e4-5ddaab4adb2a)

![image](https://github.com/Evangelin-Ruth/WDM_EXP2/assets/94219798/d7379d6a-bf66-4c3f-9e4a-e35ba3de62bb)

![image](https://github.com/Evangelin-Ruth/WDM_EXP2/assets/94219798/381120ed-43a9-4cbe-939a-e41b192c680f)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
![image](https://github.com/Evangelin-Ruth/WDM_EXP2/assets/94219798/43a6895d-7685-40d6-816d-5a6c73f002c8)
![image](https://github.com/Evangelin-Ruth/WDM_EXP2/assets/94219798/f2498454-a125-4458-93e4-c96e5fb3844d)
![image](https://github.com/Evangelin-Ruth/WDM_EXP2/assets/94219798/7601647c-c19d-4766-a1d0-46491d682b5d)

### RESULT: 
Thus association rules have been visualized for various datasets successfully.


