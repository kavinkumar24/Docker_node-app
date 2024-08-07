## Follow the below commands to make this as a containerize image

1. docker build -t node-aoo:1.0 .
2. docker images 
3. docker run -d -p 3000:3000 node-app
4. docker login
5. docker tag node-app:1.0 <username>/node-app:v1.0
6. docker push <username>/node-app:v1.0