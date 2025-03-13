The Open University is one of the largest universities in the world by number of enrolled students. In recent years, it has been working on developing an analytics platform called OU Analyse. This platform is designed to track student performance across its many programs, with the aim of reducing dropout and increasing student engagement and learning. Their analytics team is growing, and they have been actively looking to hire strong candidates. You have been shortlisted as one of them.
Business problem: As part of the interviewing process, you have been given an anonymized dataset and asked to compute the GPA (Grade Point Average) for all students in the October 2014 cohort and create a Tableau dashboard that includes their GPAs and demographic data.
Analytical context: You will be working with a subset of the OULA dataset, which contains demographic and assessment data for a number of UK-based students from the October 2014 cohort (coded as 2014J). The data is in the OULA.xlsx file (click on the file name to download the file). You will find four worksheets in this Excel file: =<a href="https://github.com/Huna96/Dashboard/blob/main/OULA.xlsx"> data set
student_info contains demographic information about students as well as which “module” (course) they were enrolled in and whether they received a pass, a fail, or dropped out.
modules lists the different modules that the students could enroll in. The actual names have been replaced with three-letter codes for privacy reasons.
assessments has a table with all the assessments for each module, indicating the weight that each assessment had in the final grade.
student_assessment contains the actual grades that each student received in each assessment on a 0-100 scale. Most students in this sample only enrolled in one course, but there are some who enrolled in more.
what i do : 
1- the student_assessment worksheet and complete Column F with the code_module to which each assessment corresponds. The modules associated with each assessment are in the assessments worksheet.
2- he student_assessment worksheet and complete Column G with the weight that is associated with each assessment.
3-Calculating the GPAs
4- Using the assessments worksheet, to calculate the sum of the weights for each code_module using a pivot table and Place it in the worksheet called Weight_Sums in Cell A1.
5- the student_assessment worksheet and complete Column H using the VLOOKUP() function with the sums of the weights
6- the GPAs from the pivot table in the gpas worksheet to a new column in the student_info worksheet. Call the new column student_module_gpa.
7- Complete Column M in the student_info worksheet. Use the header student_module_gpa for Column M. Using the GPAS pivot table, fill in the GPAs of each student by using INDEX() + MATCH() 


## Dashboard
