# SimpleDataDrivenFramework
Its a Data driven framework where test input and output values are read from data files (CVS files, Excel files) and are loaded into variables in captured or manually coded scripts. In this framework, variables are used for both input values and output verification values. Navigation through the program, reading of the data files, and logging of test status and information are all coded in the test script. This is similar to table-driven testing (which is discussed shortly) in that the test case is contained in the data file and not in the script; the script is just a "driver," or delivery mechanism, for the data. In data-driven testing, only test data is contained in the data files.

# Tools:
• Selenium Web Driver
• Java
• TestNG
• Maven
• Log4j
• ReportNG
• ExtentReports

# Enviroment & CI :  
AWS EC2, Jenkins, Docker

Execution:

    mvn clean test
