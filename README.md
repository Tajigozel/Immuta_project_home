# ImmutaProject Testing Framework 
Objective
Current scope of the framework will be limited to the following:
 - test and validate the credentials for login - automation and manual approach
 - test and verify "Immuta’s global policy feature" - automation approach 
 - test and verify "Immuta’s search feature" - manual approach found in excel sheet
 
 In current project I used behavior driven development framework with Java, Selenium and Cucumber. Test exceution is triggered from cucumber runner class when you execute "dry run" method. After you will see chrome browser window pop up that will be controlled by Selenium web driver and it will execute all step that I defined in step-definition folder.  
 Since I am using IntelliJ I created my framework using this tool. I am not sure if you have eclipse it will work the same with addditonal configurations or plugins. I used Maven as automation built tool. There's no specific IDE mentioned for me to use, so I went with what I worked with. After testing is complete the report is generating under target folder file cucumber.json and test details for verification.
