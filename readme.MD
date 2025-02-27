### Steps to run 

1. Clone the repo
2. Run `npx http-server .` in the root directory
3. Open `http://localhost:8080` in your browser
4. Click on the `Setup Web Push` button
5. Depending on browser support it will either to VAPID or APNS
6. Go to CT Dashboard and send notifications to test


### Reference

1. This is forked from https://github.com/jaysmehta/mywebsite, where we had implemented APNS creds for localhost and https://jaysmehta.github.io/ domains.
2. If we want to test the changes in a https domain, we can make changes to `singhkunal2050-testing` branch of https://github.com/jaysmehta/mywebsite and test our changes 
