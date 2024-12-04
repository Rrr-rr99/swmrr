
# Installation Guide

## How to Install

### Step 1: Update `config.json`

1. Open the `config.json` and add your mongodb url, youtube api & spotify [ You can get them from our Sever ].

### Step 2: Set Up Hosting Service

1. Go to your preferred hosting service. For this guide, we use [Render](https://render.com/).
2. In the Build & Deploy section, paste your repository URL.


### Step 3: Add Build and Start Commands
 Run the following commands to install dependencies and start your bot:

   npm install
   node index.js

### Step 4: Get Your Bot Token
Navigate to the Discord Developer Portal.
Find your application, and retrieve the bot token from the "Bot" section.

### Step 5: Set Environment Variable
Create an environment variable with the following details:
Key: TOKEN
Value: [your bot token]
Deploy your application using your hosting service’s deployment process.

### Step 6: Wait and Test
Wait approximately five minutes for your bot to deploy and start up.

Test your bot by sending commands to ensure it is operational.
