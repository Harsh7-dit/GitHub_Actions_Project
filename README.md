# GitHub_Actions_Project
CI CD Using Github Actions

## Instructions (YAML)

1. Whenever there is a PUSH 
2. SSH into my server
3. CD /home/app
4. docker compose up -d

## NodeJs Application 

Installation :-

## Node application

npm init

npm i express #Express Application
 
npm i @types/express -D # Dev dependency

## Dockerization

Dockerfile

docker build -t api .

docker run -it --rm -p 8080:8080 api

## Docker compose 

docker compose up -d

docker compose down

## Node Ignore

npx gitignore Node = This will create a git ignore file to exclude the files such as packages,logs.

## Github Actions 

Make a .github/workflows in that make a .yaml file, make this at root folder

## SSH Connection 

Copy the public key from your local system into the remote(production) server.

Copy the private key from your local system into the github action file (.yaml) or github secerts 

## Github Actions 

When you push the updated code from local system, the github action deployment starts.


