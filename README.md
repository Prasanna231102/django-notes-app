# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`



**##EC2 **

git clone https://github.com/Prasanna231102/django-notes-app.git

ls

cd django-notes-app/

sudo apt install docker.io              

docker ps.....permission denied

sudo usermod -aG docker $USER          {docker u install it dont have access of this notes app so we have to give permission to access docker write following command (add docker to a group of our user)}

sudo reboot

docker build -t notes-app .

docker run -d -p 8000:8000 notes-app:latest

allow 8000 port number in security group         {bcos in docker file 8000 is been exposed}

then ur ip and port number(:8000)
