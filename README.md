# Create_Computer_Project
Project contains Manual test cases for Computer web page and Selenium automation scripts

Manual Test cases:
Test cases are created for CRUD operations and some (Not all) edge cases including update/created with invalid inputs.
Search from pagination and from input textbox

Automation:
CRUD operations are automated using Selenium WebDriver and TestNG framework
POM (Page Object Model) is the approach followed to desing the test cases

In Order to execute the scripts please follow the below steps:
(To run the project Eclipse is mandatory - along with eclipse TestNG the Selenium libraries should be imported in project also relevant verion of chromedirever and geckodriver should be downloaded (64 or 32 bit as per computer configuration)
1. Import the attached project in Eclipse.
2. Open the Project and go the the path com.utils(package) => BaseClass.java
3. Open the BaseClass.java file and change the value of pathtoChromedirver and pathtoFirefoxdirver with path of chrome driver and gecko driver file location
4. Right click on testNG.xml file and Select the option Run as TestNg Suite
5. Check the results.


Repository contatins:
1. Manaul Test cases
2. Automation Scripts for below test cases:
   Create_Computer_Valid_01
   Read_Computer_Valid_02
   Update_Computer_Valid_03
   Delete_Computer_Valid_04
3. Executed Results (TestNG HTML format) and Execution Screenshots
