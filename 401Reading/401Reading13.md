# 401 Reading 13

## Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.
    [Socket.IO - get-started](https://socket.io/get-started/chat/)
    - Sockets provides a two way channel of communication between client and server, like the chat bots you see on a llot of consumer sites 

2. What proof of life are we getting on the backend from the above app?
    - Whatever is set up as a console.log; in this case "listening on *:3000"

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
    - If you want to send a message to everyone except for a certain emitting socket, we have the broadcast flag for emitting from that socket

## Rooms

1. What is a room and how might a room be useful?
    [socket.io - Rooms](https://socket.io/docs/v4/rooms)
    - A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

2. How do you join a room?
    - io.on("connection", (socket) => {
      socket.join(room);
      });

3. how do you leave a room?
    - io.on("connection", (socket) => {
      socket.leave(room);
      });

## Namespaces

1. What is a Namespace and what does it allow you to do?
    [socket.io - Namespaces](https://socket.io/docs/v4/namespaces/)
    - A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

2. Each namespace potentially has its own what? (hint: 3 things)
    - event handlers
    - rooms
    - middlewares
    
3. Discuss a possible use case for separate namespaces
    - A special namespace can be created for Admins (or other authorized personel) to keep logic related to those users separated from the rest of the application.