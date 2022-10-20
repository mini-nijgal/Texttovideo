# Texttovideo
To convert text to video AI software using API calls


Requirements
Node 8.10+
Pexels API key: https://www.pexels.com/api
Shotstack API key: https://dashboard.shotstack.io/register

Installation
Install node module dependencies:

cd api
npm install
Configuration
Copy the .env.dist file and rename it .env. Replace the environment variables below with your Pexels and Shotstack API key (staging key):

PEXELS_API_KEY=replace_with_your_pexels_key
SHOTSTACK_API_KEY=replace_with_your_shotstack_key
Run Locally
To start the API and serve the front end form (from the api directory):

cd api
npm run start
The visit http://localhost:3000
