# Plivo CallBlast App!

## Schedule a batch call

### [Demo Running Here](http://callblast.plivo.com/)

### Features
- The messege can be provided as text and audio file.
- Heroku deployable

## Longer version
App runs on the cloud and takes following as argument,

 - A list of phone numbers in a file
 - The messege text to play.
 - Link to an audio file (mp3/wav)
 - order at which these are played
 - Time ad date to call numbers (GMT)
 - The users' plivo credentials
 - from number to use.
 - cps quota of user.

At the specified time plivo calls the user (at from number provided) to confirm the blast and if confirmed the calls are send in batches according to the cps quota.
