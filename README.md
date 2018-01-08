# API Particulier Courtier Docker
## Install

```
git submodule init
git submodule update

docker-compose run back rake db:reset

cd ./front
npm install
```

## Run
```
docker-compose up
```
The front app is accessible at http://localhost:4200
