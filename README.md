# echoMonitor
Monitors packets forwarded from an Amazon Echo and acts on commands received

To install, run npm install

To run:
node PORT=8081 server.js

For ports bwlow 1024:
sudo node PORT=80 server.js

lightserver.js controls leds using GPIO and is a good starting point for other control programs