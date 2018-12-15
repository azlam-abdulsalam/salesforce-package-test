# salesforce-package-test
Test for Picklist Value changes through unlocked packaging

Steps to Reproduce 




1. Creating a version of the  package with this source code and deploy this into a org (Scratch/Sandbox)
2. Changing the values of Picklist  Question_Type__c.field-meta.xml 
2. Create a new version of the package
3. Check in the target org, the new package would have been deployed, but picklist values remain the same.




Try with Metadata Deployment

1. Convert to mdapi format
2. Deploy to the target org
3. Observe the picklist value has been changed




