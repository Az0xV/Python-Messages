# Messages
Messages contains 2 scripts that are connected by socket library which uses internet connection and open ports to communicate with each other. This is how to make it work in 5 steps:
1. Make sure you have python with socket library installed and an port opened.
2. Open `messagesServer.py`.
3. Then open `messagesClient.py`.
4. In the client console, the application asks for an IP address. If you do it locally, type: "127.0.0.0" (without quotes)
5. Type your username in that console, it could be anything.

And you done!
Now these scripts can talk to each other.
Open Third and Fourth `messagesClient.py`, connect them to the same network and talk between each other.
