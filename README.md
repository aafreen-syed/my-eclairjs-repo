# my-eclairjs-repo

Simple POC for eclairjs for wordcount program (on docker container available)

## Installation

```
$ npm install
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
## Built with/referring to

* [Eclairjs example online](http://www.techglows.com/write-your-first-node-js-express-app-with-eclairjs/)
* [Eclairjs github repo](https://github.com/EclairJS/eclairjs)
* [Eclairjs documenation](https://eclairjs.github.io/)


View webpage at - 

```
http://localhost:3000/
```
