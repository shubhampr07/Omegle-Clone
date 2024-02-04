# Technology Used
1. Javascript
2. ReactJs
3. NodeJs
4. ExpressJs
5. Socket.io(For Real Time Communication)

# To run Locally in your system
1. clone this repository by git clone .
2. To run the frontend(client) - cd / client. then npm install to install the packages.
3. To run the backend(server) - cd / server.
4. start the client by using (npm start) command.
5. start the server by using npm start(It opens in 8000 Port).
6. Then head over to client side and open src/context/SocketProvider.jsx
7. then place your running port 8000 link in this => const socket = useMemo(() => io('localhost:8000'), []); like this.
8. and you are all set to use video call and audio call service.

# How to use this web app
1. users need to submit their name or email.id and same room number.
2. then click on join from both side.
3. after that if there users present it shows connected.
4. then after you get a option for send streams. click on send streams.
5. and all set you can use video/audio call service.


