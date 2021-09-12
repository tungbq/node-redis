# node-redis: To implement basic Redis with Node

# Setup redis (using docker)
## Install docker on your machine
## Install docker-compose
## Run command: `docker-compose up -d`


# Start app
## `npm run dev`

# How to test our app and check Redis
## Open browser and go to: http://localhost:5000/repos/{YOUR_GITHUB_USER_NAME} (e.g: http://localhost:5000/repos/tungbq)
## Check redis server:
### 1. Start redis container CLI: `docker exec -it node-redis_redis_1 bash`
### 2. Start redis CLI: `redis-cli`
### 3. Get data: `GET tungbq`
