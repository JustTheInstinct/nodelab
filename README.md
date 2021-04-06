# Installation
1. Clone Repository into desired directory
2. Replace /etc/nginx/default with the provided default file
3. Move nodeapp.service into /etc/systemd/ and enable it (or start for one time use per boot)
4. Enable the server within the repo directory through "node server.js" or "pm2 start server.js" (If node and/or pm2 is installed)
5. Use curl http://localhost:80 (Reverse Proxy) or curl http://localhost:3000 (Normal) in command line
