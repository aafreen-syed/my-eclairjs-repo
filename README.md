# my-eclairjs-repo

Simple POC for eclairjs for wordcount (on docker container provided)

## Installation

```
$npm install
```

Pull docker image containing dependencies for eclairjs

```
docker pull eclairjs/minimal-gateway:0.9
```
Run docker with sharing data folder 

```
sudo docker run -p 8888:8888 -v <path to repo>/data/:/data eclairjs/minimal-gateway:0.9
sudo docker run -p 8888:8888 -v ~/my-eclairjs-repo/data/:/data eclairjs/minimal-gateway:0.9
```

## Run application

```
node --harmony app.js
```

View webpage at - 

```
http://localhost:3000/
```
