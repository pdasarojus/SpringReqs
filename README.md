# SpringReqs
Spring SOA requirements


# Req1 : Create a field on Account named "Number of Contacts". Populate this field with the number of contacts related to an account.  
Step1: Create a custom field called "Number of Contacts" on the Account object of type Number and add it to page layout.
Step2: Create Apex trigger "No_ContactsOnAccount.apxt" and save.
Step3: Create an Account and contacts relating the Account and check the no. of contacts field updated on Account record.
Step4: Update: Add new contacts and add related Account later and check the no. of contacts field updated on Account record.
Step5: Delete: Delete the contact under the account and check the no. of contacts field updated on Account record.
Step6: Undelete: Undelete the contact and see the contact gets associated under related account and No. of contact field gets updated on Account record

# Req2: Build a basic lightning component that can query a list of 10 most recently created accounts and display it using a lightning app.  Named: LightningApp_Req2
Step1 : Create an Apex Controller "Recent_AccountsController.apxc"
Step2:  Create Lightning Component "RecentAccounts.cmp"
Step3:  Create Lightning Component Controller "RecentAccountsController.js"
Step4:  Create lightning App "RecentAccounts.app"
Step5: Check the preiew or add the lightning app into any Page and run.


# Req3:  Make a basic http callout and print the result using system.debug https://postman-echo.com/get?foo1=bar1&foo2=bar2 
Step1: Create new Remote site settings 
Step2: Add "https://postman-echo.com"
Step3: Save
Step4: Create Apex class "CalloutReq3.apxc"
Step5: Can Run through Aynonmous window Ctrl+E 
Step6: Run below code 
EchoCalloutReq3 tst = new EchoCalloutReq3();
tst.makeHttpEchoCallout();
Step7: Check the logs -> Select Debug Only -> Find the result

