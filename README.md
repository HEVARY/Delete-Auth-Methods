# Delete-Auth-Methods

## Overview
These APIs are used to get the auth methods of the user and delete the auth methods in Service Principal Context.

## Pre-requisites

1. Register app
[Reference link](https://learn.microsoft.com/en-us/azure/active-directory/develop/quickstart-register-app#register-an-application)
2. Add credentials
[Reference link](https://learn.microsoft.com/en-us/azure/active-directory/develop/quickstart-register-app#add-credentials)
3. Assign priviliged authentication administrator role to the app.

## API
Update Environment Details
<img width="882" alt="image" src="https://user-images.githubusercontent.com/37561062/199165897-5f432dfc-767f-4f08-8304-e3eb44a11a9c.png">

1. Request App Token using API
2. Get All User AuthMethods of the user
3. Delete Auth Methods
</br> FYI - I have just added ID for Phone Method (phoneMethods/3179e48a-750b-4051-897c-87b9720928f7), you can add more methods from GET CALL. 
