# Creating a Realtime Tic Tac Toe Game in React
This project was done in reference to the tutorial in https://github.com/ocastroa/react-tictactoe . Using PubNub's React SDK, I connected 2 players to a game channel. Every move the players make is seen by both players in realtime. As compared to the original project in the tutorial, I heavily edited the UI of the game while learning from it. It enabled a deeper understanding of using React, as well as using the PubNub API.

## Setup
1. Sign up for a free PubNub account as you will need the Pub/Sub API keys.
2. Enable presence within your PubNub channel (where you get your Pub/Sub API keys is the right place)
3. Clone my repo
4. Open in Visual Studio Code (it's the one I use so it should work)
5. Go to App.js and replace the Publish and Subscribe keys you got from Step 1. (Currently my keys are within the code but it will not work if too many people are accessing it at once as I am using the Free Tier of PubNub. So, I highly recommend that you use your own channel.)
6. Go to the Terminal in Visual Studio Code
7. Type "npm install"
8. Type "npm start"
9. In the off chance that Visual Studio code prompts you to run "npm audit fix", try running "npm start" first. I have experienced it many times and more times than often, "npm audit fix" actually destroyed the code rather than help me.
10. Have fun and all the best!

**Disclaimer : The source code that was used to implement the project is no longer maintained. There may be errors or bugs that did not exist at the time of creation.**
