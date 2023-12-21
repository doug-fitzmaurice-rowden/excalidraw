# excalidraw
Quick Docker & Excalidraw setup

# Steps
Install docker using the convenince script:
```
 curl -fsSL https://get.docker.com -o get-docker.sh
 sudo sh ./get-docker.sh --dry-run
```

Clone this repo, then in the `excalidraw` folder run:
```
docker compose up -d
```

Excalidraw should now be available on the hosts's IP address on port `9721`. 
If you want a different port, change that value in `docker-compose.yaml` and run:
```
docker compose down
docker compose up -d
```
