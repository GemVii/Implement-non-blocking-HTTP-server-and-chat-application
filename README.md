# Implement-non-blocking-HTTP-server-and-chat-application
Client processes and server processes. Multiple peer processes connect together. The non-blocking network communication.
To run this file:

1. Open 3 terminal and make sure they are in the right folder in terminal

2. Run each line below to the terminal correspondent:

  python start_backend.py --server-ip 127.0.0.1 --server-port 9000
  python start_proxy.py --server-ip 127.0.0.1 --server-port 8080 
  python start_sampleapp.py --server-ip 127.0.0.1 --server-port 8001

The first line is to run the backend, second line to run the proxy and last line to run the app

3. Then to start sending message, go to: http://127.0.0.1:8001/ (Icognito mode is recommended)
  And to you can open many message from many people by open more of the link
