This applications is built for IBM Call for Code challenge 2020 based on https://github.com/watson-developer-cloud/assistant-simple . Its a simple Node.js application that is connected to a COVID-19 chatbot using the Watson Assistant APIs.
## Prerequisites
. Sign up for an [IBM Cloud account](https://www.ibm.com/account/reg/us-en/signup?formid=urx-42793&eventid=cfc-2020?cm_mmc=OSocial_Blog-_-Audience+Developer_Developer
.  You should already have a Watson Assistant service created when you deployed the COVID bot. You need to get the credentials from that chatbot to use in your Node.js application:
    - Log in to your IBM Cloud account.
    - Go to resources and open your Watson Assistant service instance.
    - You will be taken to Watson Assistant launch page. Click **Service Credentials** to view the service credentials.
      ![Watson Assistant Credentials](readme_images/watson-assistant-credentials.png)
    - You will use these credentials to populate the `.env` file when configuring the application below. Copy and save the JSON somewhere or leave this window open.
