
## create with image with docker file
docker build -t [image_name]

## Run image 
docker run -d --name cicd_container -p 8080:8080 my-app

## [Run with Yml file]
docker compose up -d --build 

## Stop
docker compose down

## create git ignore file
npx gitignore node

## git initalize
git init
