# Websockets 🔌

Websockets represent a persistent connection. Which is different from the standard call and response cycle we use most often.

Normally when we connect to a web server we make a temporary connection that sends a message, notes that the message was received and then closes down the connection.

When you create a connection with a websocket the connection is persistent and allows for data to be passed back and forth without the overhead of opening and closing a connection with each transaction.

What can you do with a websocket?

Things that update in real time

Mapping

Games


Websocket support:

https://caniuse.com/?search=websockets

This shows pretty good support.


## Websocket Resources

https://github.com/websockets/ws

Simple Websocket example in JS: https://dev.to/karlhadwen/node-js-websocket-tutorial-real-time-chat-room-using-multiple-clients-24ad
