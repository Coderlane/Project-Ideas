# IRC Client

## Outline
I would like an IRC Client that allows for history and enhanced idling.

## Requirements
* Server side connects to IRC
* Holds updates by channel
* Client connects to server and receives what it missed
* Needs some sort of authentication
* Must be secure

## Suggestions
* If the user is offline and someone mentions their name in a channel, reply that they are offline.
  * Take advantage of IRC's built in [AWAY command][1]
* Make it look nice!
* Command-line UI?


[1]: http://en.wikipedia.org/wiki/List_of_Internet_Relay_Chat_commands#AWAY "Wikipedia IRC Commands - AWAY"
