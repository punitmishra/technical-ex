# technical-exercise
Part 1:
Using the automation framework provided, write automated tests in Selenium for CallidusCloud home page (http://www.calliduscloud.com). 

The test cases you write should be prioritized by the most important site features. Testing should not include any mobile components as that is not relevant to this position. Judgements should be made as to what does and doesn't make sense to automate, but also be prepared to discuss these decisions. The output of the exercise should be a simple explanation of the testing approach and planning, runnable test cases (including code/programmatic artifacts for automated tests), results from running these test cases, and discussion of directions for further testing. 

This technical exercise uses the java bindings for Selenium webdriver with TestNG as a testing framework, useful documentation for Selenium Webdriver/TestNG can be found here:
http://www.seleniumhq.org/docs/
http://testng.org/doc/documentation-main.html

The folder should have all the necessary jars in the lib folder, when imported onto eclipse all the dependencies will be downloaded as a maven project. A TechEx.java file under src with one example test is also included, one test case would be: 
- Get a list of all products of Callidus Cloud.
- Assert all product names, change when navigating to different product endpoints. 

Source code is partially complete, we would like to see atleast one complete working example. 

** Running from Eclipse **
Import workspace into Eclipse:
File > Import > General > Existing Projects into Workspace

Run as TestNG Test:
Right click TechEx in Project Explorer and select Run as TestNG Test

** Running from command line **
cd to bin folder and run the following commands
javac -classpath "../lib/*" -d ./ ../src/TechEx.java
java -cp ".:../lib/*" org.junit.runner.JUnitCore TechEx

Part 2:
The second part of this exercise is to write a high level testplan for all of http://www.calliduscloud.com, including figuring out how to prioritize testing effort, balance effort and risk and cover all the necessary items. This part of the exercise is not meant to be at the level of individual testcases; rather it should detail out the different testing areas that need to be covered to provide complete testing coverage of the site at a higher level. We would expect this to be fairly detailed and multiple pages.

Source code can be cloned from github here: 
https://github.com/punitmishra/technical-ex

Deliverables: This exercise has a duration of around 3-4 hours (If you take more time you need to justify the effort). At the end of three hours the complete zipped Selenium work and write-up should be sent back to me. 
