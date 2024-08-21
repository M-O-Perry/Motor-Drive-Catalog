# Motor-Drive-Catalog
Helps create a layout of motor driver groups and determines the best device to use for each motor


Motor – Drive Catalog

This tool is to help create a layout of motor driver groups and to determine the best device to use for each motor.

Instructions
To use this tool navigate to the GUI tab at the bottom, then select the type of motor from the drop down and select the number of axes that you want to have together. Other cells are locked as to prevent accidental damage.
 

Results
The tool will then provide you with multiple groups according to the number of motor and axes that you have defined, and provide the cable, filter, drive, fuse, and current draw of each group. It will also tell you how many drives will go in each group and what fuse you need for each group. 
Note that the groups are not symmetric, so the fuse and current draw will differ from group to group.



Maintenance
	To expand the data set of this catalog navigate to the Data tab at the bottom of the sheet.
Motors
To expand motors, right click on the last row of the motors table (blue table), hover over insert, then select “Insert Table Row Below”.
Proceed to fill in the information, and select the appropriate drive from the drives table. You can list additional compatible drives under the compatible drives column of the same table.

Drives
To expand motors, right click on the last row of the motors table (gray table), hover over insert, then select “Insert Table Row Below”.
Proceed to fill in the information.


The formulas used in the GUI start on row 50, but please do not alter them since they are deeply interconnected and can break easily.
The hiding aspect of the groups is done through conditional formatting. 
There is no VBA used.
