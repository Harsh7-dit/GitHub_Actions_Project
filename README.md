# GitHub_Actions_Project
CI CD Using Github Actions

Instructions (YAML)

1. Whenever there is a PUSH 
2. SSH into my server
3. CD /home/app
4. docker compose up -d

## NodeJs Application 

Installation :-

// Node application
npm init
npm i express #Express Application 
npm i @types/express -D # Dev dependency

// Dockerization
Dockerfile
docker build -t api .
docker run -it --rm -p 8080:8080 api

// Docker compose 
docker compose up -d
docker compose down

npx gitignore Node = This will create a git ignore file to exclude the files such as packages,logs, 
