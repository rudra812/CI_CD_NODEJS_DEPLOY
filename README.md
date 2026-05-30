
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

## git stage change
git add .

## git commit
git commit -m "first commit"

## git add repository
git remote add origin https://github.com/rudra812/CI_CD_NODEJS_DEPLOY.git


## Hostinger deploy app procedure

sudo apt-get update
sudo apt-get upgrade

docker install

git clone

docker compose up -d --build

docker compose down




