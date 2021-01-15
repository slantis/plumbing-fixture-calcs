# What is this? 
Plumbing Fixtures calculations are boring and time consuming. We hope this dynamo automation will save you some time!

All calculations are compliant with the [2019 California Building Code & 2019 California Plumbing Code](https://up.codes/codes/california).

See below a quick 5 step guide on how to use it:

## Prerequisites:
- Having Revit Installed (we're on 2020)
- Having Dynamo Installed (Version 2.3)

## Download files

Download all the files from github or here

## Plumbing Fixture Table Family Usage
Go to the desired Level or Sheet and place the Family ("GA_Plubing Falicilities_Dyn.rfa" file)


![Table Example](https://github.com/archsourcing/plumbing-fixture-calcs/blob/main/media/Table%20Example.png)

You can insert up to 4 different Occupation types. 
Now select the amount of rows you will need in this level. Select the Family and scroll down to Visibility Instance parameters where you can choose which rows you'd like to show information. 
Check (or uncheck) according to how many rows you need. // The unchecked ones will auomatically show hatched.

![Table properties](https://github.com/archsourcing/plumbing-fixture-calcs/blob/main/media/Table%20properties.gif)

At the bottom row you can manually input the total provided on the project to easily compare with the total required.

Now let's populate the table using the dynamo player:

## Dynamo Player

You can read the whole step by step procedure or follow the GIF below: 

Open Dynamo Player and Select the folder where you located the Routine file (called "SET_PFcalcs Manual Area input - CPC2019-422.1.dyn")
Select Edit Inputs:
- Input the occupancy type (A-1,A-2,A-3,A-4,A-5,B,E,F1,F2,M,S-1,S-2) *INSTITUTIONAL AND RESIDENTIAL OCCUPANCY TYPES NOT INCLUDED*
- Select the Table Family
- Select the Row to receive the input
- Input the Area corresponding to the occupancy type

Then press Play. Whohooo, the inputs should immediately be visible on the selected family and row.

![Steps](https://github.com/archsourcing/plumbing-fixture-calcs/blob/main/media/Steps.gif)

## Feedback, Bugs, Comments? 
We would love to hear from you! 
