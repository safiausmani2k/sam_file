# Sam File_Validation

This is the data validation routine to check the extracted data in CSV format. It will try to identify the issue and perform sanity checks on the data. We are generating a few graphs to display trends in the data and to highlight possible issues.

# Run Instruction 
The Code is ingesting a local file from one level above working directory named as 'inputFile'. The folder is in zip format and required to be unzipped before running the code. Data is read into the data frame to generate checks and generating visuals. We are taking advantage of Python™ scripting to generate or retrieve data validate and display the data. 
The code could be run cell by cell or all cells together. Please be aware that no testing is done on data and Script. It is a POC or must be taken as WIP.
# Report
 The reports are generating by using the characteristics analyzed and investigated during the investigation phase.
 
# Efficiency Of The Code
Future consideration for improving the efficiency of the code  are as follows:
			1. Rely on an external package for critical code. 
			2.	Use keys for sorts.
			3.	Optimizing by utilising loops
		

# Future Enhancement

		1.	Standatrised columns and data types against predefined file schema.
		2.	Introduction to function, loop and OOP standards to optimes and encapsulate functionality and data.
		3.	Generate user-friendly messages after validation.
		4.	Auto-correction for common issues and standardize fixed values into a numeric display.
		5.	Report simplification. Display in summary dashboards that could be sliced diced and have a filter to check different attributes
