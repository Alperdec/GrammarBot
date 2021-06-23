# GrammarBot
Grammar bot is a nuisance to most discord servers. He listens to the chat channel and checks for spelling errors and snarkily suggests words to fix those spelling errors.
Those who spell correctly are awarded points. Those who spell incorrectly are punished with removal of points. If one asks the grammarbot to display the leaderboard he does so willingly and happily.

## details
Grammarbot uses the spellcheck module I built: https://github.com/Alperdec/SpellChecker
to check and correct user's chats. In addition to this it is connected to a RESTful API built using **express** and **javascript** and stores points on **firestore**. 
The source code for this can be found in **/grammarbot/grammarbot-backend/functions/index.js**

The pointsystem module can be found in **util.py**

## notes

This project is not so aptly named as the bot solely checks for spelling errors and is ignorant when it comes to grammatical errors.
Future updates will include attempts at checking for grammatical errors.

