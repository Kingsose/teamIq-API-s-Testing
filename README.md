# teamIq-API-s-Testing
## TeamIQ API Testing
This repository contains Postman API tests for the TeamIQ application.
Collection: All Payload
This collection covers the full user flow from organization signup to user registration.
Requests
1. Sign Up
Creates a new organization with a randomly generated email, name and password.
2. Login
Logs in with the organization credentials and saves the auth token automatically.
3. Onboarding Complete
Updates the organization profile with company details like logo, description, sector and social media handles.
4. Invitation
Sends an invitation to a new intern with a randomly generated email and saves the invitation code.
5. Register User
Registers the invited intern using the invitation code from the previous request.
How to Use

Import the collection file into Postman
Set up your environment and add the baseurl_global variable with the base URL:

   https://teamiq-backend.onrender.com

Run the requests in order from top to bottom as each one depends on the previous

Environment Variables
VariableDescriptionbaseurl_globalThe base URL of the APIauthTokenAuto-set after loginemail_envAuto-generated emailpassword_envAuto-generated passwordinvcode_envAuto-set after invitation
