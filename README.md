- Create Organization
- set up authentication (MFA)
- create an Organization level webhook to send payload to a GitHub App upon "repository created" event
- create a GitHub App to listen on a specific URL and process incoming HTTP Post
- If the HTTP Post is valid, process payload and 
  - update protection rules on the "main" branch
  - create new issue assigned to the user id that created the repositiry
