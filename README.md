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

Go to the Level and place the 


![Table Example](https://github.com/archsourcing/plumbing-fixture-calcs/blob/main/media/Table%20Example.png)

You can insert up to 4 different Occupation types. 

On Properties, scroll down to Visibility where you can choose which rows you'd like to show information. The ones unticked will show hatched.

![Table properties](https://github.com/archsourcing/plumbing-fixture-calcs/blob/main/media/Table%20properties.gif)

At the bottom row you can manually input the total provided on the project to easily compare with the total required.

## Dynamo

Open Dynamo Player and Select the folder where you'd located the Routine.
Select Edit Inputs:
- Input the occupancy type (A-1,A-2,A-3,A-4,A-5,B,E,F1,F2,M,S-1,S-2) *INSTITUTIONAL AND RESIDENTIAL OCCUPANCY TYPES NOT INCLUDED*
- Select the Table Family
- Select the Row to receive the input
- Input the Area corresponding to the occupancy type

The press Play.
The inputs should immediately be visible on the selected family and row.

![Steps](https://github.com/archsourcing/plumbing-fixture-calcs/blob/main/media/Steps.gif)


## Comments
We'd love to hear any comments or questions you might have! Please report any issues you find.
