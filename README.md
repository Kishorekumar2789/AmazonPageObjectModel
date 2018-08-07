# AmazonPageObjectModel

1. This Automation Framework follows the design pattern of Page Object Model.
2. As of now, the Test data and Web Locators are maintained in two different property files.
3. On each Test execution these two property files were read by the corresponding Java Class and serve the data for Test Execution
4. I have created Fluent wait method in order to handle the dymanic web elements, to avoid selenium exception and to make sure the availability of DOM.
5. Configured the Framework with Extent Reports, to monitor the test case execution which give Pictorial representation of Automation Status
6. Final test execution reports were available in the following path: \AmazonAutomation\test-output\Amazon.html
