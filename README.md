node app file
#to run nodejs application on docker
npm install in project directory

sudo docker build -t bhagyshri2001/nodejs-image-demo .
docker images
#crete container
sudo docker run --name nodejs-image-demo -p 80:8080 -d bhagyshri2001/nodejs-image-demo
#check running container
docker ps
# to chek on live
https://serverip
