# How to Build RESTAPI using Node, MongoDB and Docker



## Technical Stack

- Nodejs
- Express
- MongoDB
- Docker

## How it works?



It is a REST API that creates , updates , delete and list all the subscribers

![image](https://user-images.githubusercontent.com/313480/184569837-9c49188a-595c-4bb9-a3da-b16114019a8e.png)



## Prerequisite

- Install Docker Desktop's

## Step 1 - Clone the repository

```
 git clone https://github.com/Open-Source-Chandigarh/Rest-Api-Nodejs.git
```

## Step 2 - Change directory to Rest-Api-Nodejs

```
 cd Rest-Api-Nodejs
```

## Step 3 - Create docker image

```
docker build -t rest .
```

## Step 4 - Run it on server

```
 docker run -p 3000:3000 rest
```


