# stream
React-App for Streaming online video as like Twitch 

## Project-Discription a/c to folder

1. api folder used for creating api request it is as  *JSON-SERVER* . To run just run *npm install* to directory in terminal.

2. client folder have code for initialize interaction in Api to run different module as show streams, add stream, edit stream & delete stream.

3. rtmp server is used for setup video server for streaming video live for initial setup *Node-Media-Server* used with *OBS* media player. 

### For the first setup run `npm install` in both folder(client & api) to initial setup for required modules and requires OBS media player and configure it in setting with custom player and url for that will be rmtp://localhost:8000/live and id with be pass in STREAM KEY.

### Keys to remember:

1. Create google oauth key for client-id to enable Login with google.
2. Create Api server for *streams* which is in api folder.
3. Create RMTP server for media streaming.