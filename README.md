# Docker Screeps
* Docker image to start a standalone screeps server.

### Environment Variables
* `STEAM_KEY` = Steam API key avaliable from: (http://steamcommunity.com/dev/apikey)

### Usage
````
docker run -d \
-e STEAM_KEY='mysecretapikey' \
mitcdh/screeps
````

### Structure
* `/screeps`: Screeps game directory

### Exposed Ports
* `21025`: Game server