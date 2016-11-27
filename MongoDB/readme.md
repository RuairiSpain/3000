docker run -d -p 27017:27017 .

docker run -d -p 27017:27017 -v /someLocalVolume:/data/db .



docker exec -it mongodb sh