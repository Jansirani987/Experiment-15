# Experiment-15
## The study of the Selenium Web Testing Tool reveals its effectiveness in automating web applications for testing purposes across different browsers and platforms.
What is Selenium? JavaScript framework that runs in your web browser Works anywhere JavaScript is supported Hooks for many other languages Java, Ruby, Python Can simulate a user navigating through pages and then assert for specific marks on the pages All you need to really know is HTML to start using it right away Selenium IDE Selenium Integrated Development Environment (IDE) is a Firefox plugin that lets testers to record their actions as they follow the workflow that they need to test. It provides a Graphical User Interface for recording user actions using Firefox which is used to learn and use Selenium, but it can only be used with Firefox browser as other browsers are not supported. However, the recorded scripts can be converted into various programming languages supported by Selenium and the scripts can be executed on other browsers as well. Selenium-IDEDownload

Step 1 − Launch Firefox and navigate to the following URL - http://seleniumhq.org/download/. Under the Selenium IDE section, click on the link that shows the current version number as shown below.

<img width="1036" height="356" alt="Screenshot (598)" src="https://github.com/user-attachments/assets/9976bb65-266a-4636-ab40-fe8541f8d6a3" />

Step 2 − Firefox add-ons notifier pops up with allow and disallow options. User has to allow the installation image

<img width="648" height="295" alt="Screenshot (599)" src="https://github.com/user-attachments/assets/6bdb3f93-8493-462d-a810-721ede7000ff" />

Step 3 − The add-ons installer warns the user about untrusted add-ons. Click 'Install Now'.

<img width="784" height="548" alt="Screenshot (600)" src="https://github.com/user-attachments/assets/2c9c79d2-a6f6-4777-bf17-f9c02da0c867" />


Step 4 − The Selenium IDE can now be accessed by navigating to Tools >>Selenium IDE.

<img width="727" height="326" alt="Screenshot (601)" src="https://github.com/user-attachments/assets/3b869445-44f4-4440-aa39-f4dad0a28393" />

Step 5 − The Selenium IDE can also be accessed directly from the quick access menu bar as shown below.

<img width="407" height="154" alt="Screenshot (602)" src="https://github.com/user-attachments/assets/b0bb7584-b2b3-4f44-b98d-32619a144f93" />

Selenium IDE Features This section deals with the features available in Selenium IDE. The following image shows the features of Selenium IDE with the help of a simple tool-tip.

<img width="722" height="502" alt="Screenshot (603)" src="https://github.com/user-attachments/assets/abd2a786-2a79-4eb0-aa5f-2d7a01d44cdb" />

<img width="391" height="495" alt="Screenshot (604)" src="https://github.com/user-attachments/assets/186071d6-81ba-4b1d-ba7a-d57101b17c6c" />

Creating Selenium IDE Tests This section deals with how to create IDE tests using recording feature. The following steps are involved in creating Selenium tests using IDE –

 Recording and adding commands in a test

 Saving the recorded test

 Saving the test suite

 Executing the recorded test

Recording and Adding Commands in a Test We will use www.ncalculators.com to demonstrate the features of Selenium. Step 1 − Launch the Firefox browser and navigate to the website - https://www.ncalculators.com/

Step 2 − Open Selenium IDE from the Tools menu and press the record button that is on the top- right corner.
<img width="652" height="298" alt="Screenshot (605)" src="https://github.com/user-attachments/assets/c15e4f33-04f8-4a72-a3d9-e36fdbcd3e81" />

Step 3 − Navigate to "Math Calculator" >> "Percent Calculator >> enter "10" as number1 and 50 as number2 and click "calculate".

<img width="644" height="167" alt="Screenshot (606)" src="https://github.com/user-attachments/assets/2bdfa216-cbc3-41ab-8f11-2b2ef0c0c11b" />

Step 4 − User can then insert a checkpoint by right clicking on the webelement and select "Show all available commands" >> select "assert text css=b 5"

<img width="640" height="329" alt="Screenshot (607)" src="https://github.com/user-attachments/assets/43bf407c-0064-4271-a44f-816c90d93811" />

Step 5 − The recorded script is generated and the script is displayed as shown below

<img width="659" height="374" alt="Screenshot (608)" src="https://github.com/user-attachments/assets/52e3c731-ba48-4ff5-a12f-7bc25b2db3ba" />

SavingtheRecordedTest Step 1 − Save the Test Case by navigating to "File" >> "Save Test" and save the file in the location of your choice. The file is saved as .HTML as default. The test can also be saved with an extension htm, shtml, and xhtml.
<img width="639" height="312" alt="Screenshot (609)" src="https://github.com/user-attachments/assets/2b5c0dc0-5b7c-45d1-a44b-3d96409d4b86" />

SavingtheTest Suite A test suite is a collection of tests that can be executed as a single entity. Step 1 − Create a test suite by navigating to "File" >> "New Test Suite" as shown below.

<img width="675" height="323" alt="Screenshot (610)" src="https://github.com/user-attachments/assets/4a2f7f52-3fb1-4def-b4d1-1c939f97f90a" />

Step 2 − The tests can be recorded one by one by choosing the option "New Test Case" from the "File" Menu. Step 3 − The individual tests are saved with a name along with saving a "Test Suite".


<img width="657" height="296" alt="Screenshot (611)" src="https://github.com/user-attachments/assets/70e9d268-b45b-416a-9666-2a86357f5f1c" />

This section deals with debugging the Selenium IDE script. Debugging is the process of finding and fixing errors in the test script. It is a common step in any script development. To make the process more robust, we can make use a plugin "Power Debugger" for Selenium IDE. Step 1 − To install Power Debugger for Selenium IDE, navigate to https://addons.mozilla.org/en- US/firefox/addon/power-debugger-selenium-ide/ and click "Add to Firefox" as shown below.

<img width="654" height="354" alt="Screenshot (612)" src="https://github.com/user-attachments/assets/bdf9b3d2-8573-49c2-84ea-4fdfa014b7a9" />

Step 2 − Now launch 'Selenium IDE' and you will notice a new icon, "Pause on Fail" on recording toolbar as shown below. Click it to turn it ON. Upon clicking again, it


<img width="670" height="334" alt="Screenshot (614)" src="https://github.com/user-attachments/assets/7262c9ac-8007-4631-b437-512499a135de" />

Step 3 − Users can turn "pause on fail" on or off any time even when the test is running.

Step 4 − Once the test case pauses due to a failed step, you can use the resume/step buttons to continue the test execution. The execution will NOT be paused if the failure is on the last command of any test case.

Step 5 − We can also use breakpoints to understand what exactly happens during the step. To insert a breakpoint on a particular step, "Right Click" and select "Toggle Breakpoint" from the context- sensitive menu.

<img width="659" height="474" alt="Screenshot (615)" src="https://github.com/user-attachments/assets/51337bbb-e78a-406f-9784-994216ffca86" />

Step 6 − Upon inserting the breakpoint, the particular step is displayed with a pause icon as shown below.

<img width="637" height="421" alt="Screenshot (616)" src="https://github.com/user-attachments/assets/9c3e14b6-6b2b-4863-81e6-371e3adc10c6" />

Step 7 − When we execute the script, the script execution is paused where the breakpoint is inserted. This will help the user to evaluate the value/presence of an element when the execution is inprogress.



Inserting Verification Points

This section describes how to insert verification points in Selenium IDE. The test cases that we develop also need to check the properties of a web page. It requires assert and verify commands. There are two ways to insert verification points into the script. To insert a verification point in recording mode, "Right click" on the element and choose "Show all Available Commands" as shown below. 

![Uploading Screenshot (618).png…]()

We can also insert a command by performing a "Right-Click" and choosing "Insert New Command".


After inserting a new command, click 'Command' dropdown and select appropriate verification point from the available list of commands as shown below.

<img width="650" height="243" alt="Screenshot (620)" src="https://github.com/user-attachments/assets/95f2d4a4-434a-438e-86a7-aa1934aa7c16" />

Given below are the mostly used verification commands that help us check if a particular step has passed or failed. • verifyElementPresent • assertElementPresent • verifyElementNotPresent • assertElementNotPresent • verifyText • assertText • verifyAttribute • assertAttribute • verifyChecked • assertChecked • verifyAlert • • • assertAlert verifyTitle a ssertTitle Synchronization Points During script execution, the application might respond based on server load, hence it is required for the application and script to be in sync. Given below are few a commands that we can use to ensure that the script and application are in sync.  waitForAlertNotPresent  waitForAlertPresent  waitForElementPresent  waitForElementNotPresent  waitForTextPresent  waitForTextNotPresent  waitForPageToLoad  waitForFrameToLoad Selenium Pattern Matching □ This section deals with how to work with regular expressions using IDE. Like locators, patterns are a type of parameter frequently used by Selenium. It allows users to describe patterns with the help of special characters. Many a time, the text that we would like to verify are dynamic; in that case, pattern matching is very useful. Pattern matching is used with all the verification point commands - verifyTextPresent, verifyTitle, verifyAlert, assertConfirmation, verifyText, and verifyPrompt. There are three ways to define a pattern –  Globbing Globbing  regular expressions, and  exact patterns. Most techies who have used file matching patterns in Linux or Windows while searching for a certain file type like *.doc or *.jpg. would be familiar with term "globbing" Globbing in Selenium supports only three special characters: *, ?, and [ ]. • * − matches any number of characters. • ? − matches a single character. □ [ ] − called a character class, lets you match any single character found within the brackets. [0- 9] matches any digit. To specify a glob in a Selenium command, prefix the pattern with the keyword 'glob:'. For example, if you would like to search for the texts "tax year 2013" or "tax year 2014", then you can use the golb "tax year *" as shown below. However the usage of "glob:" is optional while specifying a text pattern because globbing patterns are the default in Selenium.


<img width="528" height="57" alt="Screenshot (621)" src="https://github.com/user-attachments/assets/00c6f5b4-de7f-45bd-b6ee-be59ede65d57" />


ExactPatterns Patterns with the prefix 'exact:' will match the given text as it is. Let us say, the user wants an exact match with the value string, i.e., without the glob operator doing its work, one can use the 'exact' pattern as shown below. In this example the operator '*' will work as a normal character rather than apattern- matching wildcard


<img width="543" height="60" alt="Screenshot (622)" src="https://github.com/user-attachments/assets/a93ed4c5-f923-46fd-91d0-ccaa119b8fbd" />

character.

Regular Expressions Regular expressions are the most useful among the pattern matching techniques available. Selenium supports the complete set of regular expression patterns that Javascript supports. Hence the users are no longer limited by *, ? and [] globbing patterns. To use RegEx patterns, we need to prefix with either "regexp:" or "regexpi:". The prefix "regexpi" is case- insensitive. The glob: and the exact: patterns are the subsets of the Regular Expression patterns. Everything that is done with glob: or exact: can be accomplished with the help of RegExp. Example For example, the following will test if an input field with the id 'name' contains the string 'tax year', 'Tax Year',



<img width="546" height="56" alt="Screenshot (623)" src="https://github.com/user-attachments/assets/8188f36d-9ee2-4eec-90be-0e968386fc7c" />


or 'tax Year'. image

Selenium User Extensions The Java script that allows users to customize or add new functionality. It is easy to extend Selenium IDE by adding customized actions, assertions, and locator-strategies. It is done with the help of JavaScript by adding methods to the Selenium object prototype. On startup, Selenium will automatically look through the methods on these prototypes, using name patterns to recognize which ones are actions, assertions, and locators. Let us add a 'while' Loop in Selenium IDE with the help of JavaScript. Step 1 − To add the js file, first navigate to https://github.com/darrenderidder/sideflow/blob/master/sideflow.js and copy the script and place save it as


<img width="667" height="369" alt="Screenshot (624)" src="https://github.com/user-attachments/assets/8a5fec19-8587-43c9-8e55-5de9692b73c3" />


<img width="668" height="370" alt="Screenshot (625)" src="https://github.com/user-attachments/assets/f751912d-1301-4a7b-a10e-c5beb8e82976" />

Step 3 − Click the 'Browse' button under 'Selenium Core Extensions' area and point to the js file that we have saved in Step 1.

Step 4 − Restart Selenium IDE.

Step 5 − Now you will have access to a few more commands such as "Label", "While" etc.

Step 6 − Now we will be able to create a While loop within Selenium IDE and it will execute as shown below.


<img width="669" height="309" alt="Screenshot (626)" src="https://github.com/user-attachments/assets/53119c74-f910-4d43-b3b8-77cdbaa49217" />

## Result:
Thus, the study of selenium web testing tool is conducted and the results were noted.



