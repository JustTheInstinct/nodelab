# Installation
1. Clone Repository into desired directory
2. Move nodeapp.service into /etc/systemd/ and enable it (or start for one time use per boot)
3. Enable the server within the repo directory through "node server.js" or "pm2 start server.js" (If node and/or pm2 is installed)
4. Use curl http://localhost:80 (Reverse Proxy) or curl http://localhost:3000 (Normal) in command line
