# Apex
Apex is a flavour of Java. When in doubt, check out the [Google Java Style Guide](https://google-styleguide.googlecode.com/svn/trunk/javaguide.html).

## Naming conventions

 1. Class names are proper case: `MyClassName`
 2. Variables are camel case: `myVariableName`
 3. Salesforce custom opjects are proper case and end with a `__c`: `MyCustomObject__c`
 4. Salesforce custom object fields are camel case and end with a `__c`: 'MyCustomField__c`
 5. Key words in SOQL statments are all caps: `SELECT Field FROM Table WHERE OtherField = true`


#Files
All file names should be proper case `JustLikeThis`. Unfortunately/Fortunately the names that you give to your files are restricted in length by Salesforce. This means that you may have to cut your .
 1. Pages should be descriptive and not contain the word "Page" : `PowerSearch.page`
 2. Controllers should start with the page name and end with "Controller": `PowerSearchController.cls`
 3. Triggers should *not* contain the word "Trigger" in them. 
 4. Triggers should also have at least one handle file. The Handler file should start with the Trigger name and end with "Handler".
