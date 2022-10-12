# that's hilarious!
<br>
An online party game with video call where players tell jokes and get points based on how the others react.
<br><br>

## Links
- [Try it out!](https://thats-hilairious.herokuapp.com/)

## What it does
that's hilaIrious is an online party game where friends can tell jokes and win points for how much they make their friends laugh, based on our algorithm which uses Face API. Players can join individual rooms, where they'll be able to see and chat with other players. 
<br><br>
Once the game is started, each player will have a turn to respond to a prompt, after which their response is revealed to the room and our algorithm calculates the player's score based on how much the others were laughing. At the end of the game, players can compare scores and see who was the funniest in the group!

## Technologies
It uses a Express.js backend server and a React frontend. Twilio is used to stream video and audio between the players, while Socket.io allows the backend and clients to communicate in order for game mechanics to proceed in real time. We use Face API, to analyze how much each player is laughing and generate a score from that.
