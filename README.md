In the main project directory, you can run:

npm run start
Runs the server code once using Node.

npm run server
Runs the server continuously using the nodemon package. The server will automatically restart when you change a file in the server code.

npm run dev
Uses concurrently to run both the server and the client at the same time. The client-side code (React) runs on Port 3000. The server-side code (Node) runs on Port 5000.
