## Media Server

`curl -sSL https://get.livekit.io | bash`

> livekit-server is installed to /usr/local/bin

`livekit-server --dev --redis-host 127.0.0.1:6379`

API key: devkey
API secret: secret

> By default LiveKit's signal server binds to 127.0.0.1:7880. If you'd like to access it from other devices on your network, pass in --bind 0.0.0.0

---

## Egress

**Recording**

`sudo systemctl start docker.service`

`docker-compose up`

---

<!-- 
Mux Streaming Service

Access Token ID: 855cf3d4-1380-4b5c-86ff-f9631c537069

Secret Key: jvauk3nG0gQ77/L9Wa8yoTJ5R23evYrtZQIXpiRtbUZNGFNIb0GtUCVkL7xozL89Uxwga89wiyz 
-->